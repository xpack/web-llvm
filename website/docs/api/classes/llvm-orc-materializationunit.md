---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/materializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MaterializationUnit` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> represents a set of symbol definitions that can be materialized as a group, or individually discarded (when overriding definitions are encountered). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::MaterializationUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">llvm/ExecutionEngine/Orc/MaterializationUnit.h</a>"
</div>

## Derived Classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-coffplatform-cpp-/coffheadermaterializationunit">COFFHeaderMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/dsohandlematerializationunit">DSOHandleMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit">ELFNixPlatformCompleteBootstrapMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-indirectionutils-cpp-/compilecallbackmaterializationunit">CompileCallbackMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machoplatform-cpp-/machoplatformcompletebootstrapmaterializationunit">MachOPlatformCompleteBootstrapMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/absolutesymbolsmaterializationunit">AbsoluteSymbolsMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> implementation for pre-existing absolute symbols. <a href="/web-llvm/docs/api/classes/llvm/orc/absolutesymbolsmaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/basicobjectlayermaterializationunit">BasicObjectLayerMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materializes the given object file (represented by a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> instance) by calling 'emit' on the given <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/basicobjectlayermaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> is a convenient base class for MaterializationUnits wrapping LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/mu">MU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmaterializationunit">LazyReexportsMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A materialization unit that builds lazy re-exports. <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphmaterializationunit">LinkGraphMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for wrapping LinkGraphs. <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphmaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/reexportsmaterializationunit">ReExportsMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A materialization unit for symbol aliases. <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsmaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/redirectablematerializationunit">RedirectableMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/redirectablematerializationunit">RedirectableMaterializationUnit</a> materializes redirectable symbol by invoking <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager/#adeba1076cb445206426dd27c5158c16c">RedirectableSymbolManager::emitRedirectableSymbols</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablematerializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/sectcreatematerializationunit">SectCreateMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simplemachoheadermu">SimpleMachOHeaderMU</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1233ea2ef51205e4954cdc12e7bc2d81">MaterializationUnit</a> (Interface I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1519092c27c674e6c01e52e99162fb6">~MaterializationUnit</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">getName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of this materialization unit. <a href="#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4801b1c74dd252cadcf1ff1fd9852a83">getSymbols</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of symbols that this source provides. <a href="#a4801b1c74dd252cadcf1ff1fd9852a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d1933cb59ec5527b4c025ae7027216">getInitializerSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the initialization symbol for this <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> (if any). <a href="#a99d1933cb59ec5527b4c025ae7027216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799a73fe8db7676284a0dca2186f77fe">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#a799a73fe8db7676284a0dca2186f77fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c8d446cce25395b56f033db03591f7">doDiscard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITDylibs to notify MaterializationUnits that the given symbol has been overridden. <a href="#ab8c8d446cce25395b56f033db03591f7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4422939861947e307e5505b6816c5db4">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e85ae8dcec80a8805612128628be8bc">discard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Name)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#a2e85ae8dcec80a8805612128628be8bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a387220b1a2a52bb23b83009c9c33527a">SymbolFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">InitSymbol</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5d75c54ddbca56c0c801d4b7e2870d">ID</a></td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> represents a set of symbol definitions that can be materialized as a group, or individually discarded (when overriding definitions are encountered).</p>


<p>MaterializationUnits are used when providing lazy definitions of symbols to JITDylibs. The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will call materialize when the address of a symbol is requested via the lookup method. The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will call discard if a stronger definition is added or already present.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>.</p>

</div>
</div>

### JITDylib {#a235f764fe0f700836f89667ef5a0033b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Reference <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/simplemachoheadermu/#a9b2bd40158d493fc5bd571af23329bbc">llvm::orc::SimpleMachOHeaderMU::createHeaderBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-coffplatform-cpp-/coffheadermaterializationunit/#ad598ae3f4a503e581b7d8edd6955a74d">anonymous{COFFPlatform.cpp}::COFFHeaderMaterializationUnit::discard</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/dsohandlematerializationunit/#a1b0f1503f6a7f152379990de504168b3">anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::discard</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit/#a7539ff05ec4033c095ff06e83ef4fa25">anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::discard</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoplatform-cpp-/machoplatformcompletebootstrapmaterializationunit/#a0181a59c56d2557e17f8f9cfa257a3b9">anonymous{MachOPlatform.cpp}::MachOPlatformCompleteBootstrapMaterializationUnit::discard</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablematerializationunit/#a6a0f0c139fbc1606bec46f2f79193fc2">llvm::orc::RedirectableMaterializationUnit::discard</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simplemachoheadermu/#af2e38e6bc6fc5323e70d9df63a599bfc">llvm::orc::SimpleMachOHeaderMU::discard</a>, <a href="#ab8c8d446cce25395b56f033db03591f7">doDiscard</a>, <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmaterializationunit/#a04de50b8263e48804efa81f83c76ff58">llvm::orc::LazyReexportsMaterializationUnit::LazyReexportsMaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsmaterializationunit/#aab64c7f0c4f378e1fa034cd086a1bd1a">llvm::orc::ReExportsMaterializationUnit::ReExportsMaterializationUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MaterializationUnit() {#a1233ea2ef51205e4954cdc12e7bc2d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MaterializationUnit::MaterializationUnit (<a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">Interface</a> I)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">InitSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a387220b1a2a52bb23b83009c9c33527a">SymbolFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/absolutesymbolsmaterializationunit/#acb286488c413b795f16a624997c45b95">llvm::orc::AbsoluteSymbolsMaterializationUnit::AbsoluteSymbolsMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/basicobjectlayermaterializationunit/#a33634ae43a80c70e47d2113ef6e8d872">llvm::orc::BasicObjectLayerMaterializationUnit::BasicObjectLayerMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-coffplatform-cpp-/coffheadermaterializationunit/#aa19b6984b69ff0700da9c5684ed3ca8d">anonymous{COFFPlatform.cpp}::COFFHeaderMaterializationUnit::COFFHeaderMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectionutils-cpp-/compilecallbackmaterializationunit/#ae695a068d5751f1ff3bb75f7ec56ce56">anonymous{IndirectionUtils.cpp}::CompileCallbackMaterializationUnit::CompileCallbackMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/dsohandlematerializationunit/#a517e8b3a196c8ae3af7c297f059081fd">anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::DSOHandleMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit/#a3d86f46ab83f3ab13b0276437b6e7783">anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::ELFNixPlatformCompleteBootstrapMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#abd7587e443a02c59f86f70c0cd9ca04d">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmaterializationunit/#a04de50b8263e48804efa81f83c76ff58">llvm::orc::LazyReexportsMaterializationUnit::LazyReexportsMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphmaterializationunit/#ad7d27030c7a788b8d325c152bd89a576">llvm::orc::LinkGraphMaterializationUnit::LinkGraphMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphmaterializationunit/#af4503a4bbbb5f677ff9bb4819b2e8bde">llvm::orc::LinkGraphMaterializationUnit::LinkGraphMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoplatform-cpp-/machoplatformcompletebootstrapmaterializationunit/#a531622757f4d64c10f90aed489658351">anonymous{MachOPlatform.cpp}::MachOPlatformCompleteBootstrapMaterializationUnit::MachOPlatformCompleteBootstrapMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/mu/#a8d109ba81511e8f29201fa169b6529b7">llvm::orc::LazyReexportsManager::MU::MU</a>, <a href="/web-llvm/docs/api/classes/llvmorclazycallthroughmanagerref/orccapimaterializationunit/#a9a4c7a8eb402130db2164aeaacce8009">LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::OrcCAPIMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablematerializationunit/#a5b753e5b1dfdf2a6b8bbbbd98019bf84">llvm::orc::RedirectableMaterializationUnit::RedirectableMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsmaterializationunit/#aab64c7f0c4f378e1fa034cd086a1bd1a">llvm::orc::ReExportsMaterializationUnit::ReExportsMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sectcreatematerializationunit/#a5924de0e3f852c0a9094833762d362ec">llvm::orc::SectCreateMaterializationUnit::SectCreateMaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/simplemachoheadermu/#adf2eaaacb1f7426942728e7c1bb59066">llvm::orc::SimpleMachOHeaderMU::SimpleMachOHeaderMU</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MaterializationUnit() {#af1519092c27c674e6c01e52e99162fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::orc::MaterializationUnit::~MaterializationUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doDiscard() {#ab8c8d446cce25395b56f033db03591f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MaterializationUnit::doDiscard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
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

<p>Called by JITDylibs to notify MaterializationUnits that the given symbol has been overridden.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">getName</a>, <a href="#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">InitSymbol</a>, <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a> and <a href="#a387220b1a2a52bb23b83009c9c33527a">SymbolFlags</a>.</p>

</div>
</div>

### getInitializerSymbol() {#a99d1933cb59ec5527b4c025ae7027216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolStringPtr &amp; llvm::orc::MaterializationUnit::getInitializerSymbol ()</td>
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

<p>Returns the initialization symbol for this <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> (if any).</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Reference <a href="#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">InitSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a7a6c3b4432af35ad1b0c9843105f5e4d">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a6ceb8793145f063bcb5e204c1251649e">llvm::orc::COFFPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a454ad1d1eb28a3dfc9ed6383417df7bb">llvm::orc::ELFNixPlatform::notifyAdding</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a9933be5a0082912958e7328de0ca90e1">llvm::orc::MachOPlatform::notifyAdding</a>.</p>

</div>
</div>

### getName() {#a1c2e2986d77d9e3cc3d1c64e6e8f35ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::orc::MaterializationUnit::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of this materialization unit.</p>


<p>Useful for debugging output.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Referenced by <a href="#ab8c8d446cce25395b56f033db03591f7">doDiscard</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a6ceb8793145f063bcb5e204c1251649e">llvm::orc::COFFPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a454ad1d1eb28a3dfc9ed6383417df7bb">llvm::orc::ELFNixPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a9933be5a0082912958e7328de0ca90e1">llvm::orc::MachOPlatform::notifyAdding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afb6397bf4f8685b94232a9b6f72d4ed2">llvm::orc::operator&lt;&lt;</a>.</p>

</div>
</div>

### getSymbols() {#a4801b1c74dd252cadcf1ff1fd9852a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolFlagsMap &amp; llvm::orc::MaterializationUnit::getSymbols ()</td>
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

<p>Return the set of symbols that this source provides.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Reference <a href="#a387220b1a2a52bb23b83009c9c33527a">SymbolFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a7a6c3b4432af35ad1b0c9843105f5e4d">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::notifyAdding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afb6397bf4f8685b94232a9b6f72d4ed2">llvm::orc::operator&lt;&lt;</a>.</p>

</div>
</div>

### materialize() {#a799a73fe8db7676284a0dca2186f77fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::MaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a4422939861947e307e5505b6816c5db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MaterializationUnit::anchor ()</td>
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



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### discard() {#a2e85ae8dcec80a8805612128628be8bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::MaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementations of this method should discard the given symbol from the source (e.g.</p>


<p>if the source is an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and the symbol is a function, delete the function body or mark it available externally).</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### InitSymbol {#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::MaterializationUnit::InitSymbol</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Referenced by <a href="#ab8c8d446cce25395b56f033db03591f7">doDiscard</a>, <a href="#a99d1933cb59ec5527b4c025ae7027216">getInitializerSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="#a1233ea2ef51205e4954cdc12e7bc2d81">MaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvmorclazycallthroughmanagerref/orccapimaterializationunit/#a9a4c7a8eb402130db2164aeaacce8009">LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::OrcCAPIMaterializationUnit</a>.</p>

</div>
</div>

### SymbolFlags {#a387220b1a2a52bb23b83009c9c33527a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlagsMap llvm::orc::MaterializationUnit::SymbolFlags</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>


<p>Referenced by <a href="#ab8c8d446cce25395b56f033db03591f7">doDiscard</a>, <a href="#a4801b1c74dd252cadcf1ff1fd9852a83">getSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a> and <a href="#a1233ea2ef51205e4954cdc12e7bc2d81">MaterializationUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a0f5d75c54ddbca56c0c801d4b7e2870d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::orc::MaterializationUnit::ID</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/materializationunit-h">MaterializationUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
