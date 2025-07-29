---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/elflinkgraphbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFLinkGraphBuilder` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> building code that's specific to the given ELFT, but common across all architectures. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ELFT&gt;
class llvm::jitlink::ELFLinkGraphBuilder&lt;ELFT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ExecutionEngine/JITLink/ELFLinkGraphBuilder.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase">ELFLinkGraphBuilderBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common link-graph building code shared between all ELFFiles. <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elf-aarch64-cpp-/elflinkgraphbuilder-aarch64">ELFLinkGraphBuilder_aarch64&lt;ELFT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elf-loongarch-cpp-/elflinkgraphbuilder-loongarch">ELFLinkGraphBuilder_loongarch&lt;ELFT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-i386">ELFLinkGraphBuilder_i386&lt;ELFT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-riscv">ELFLinkGraphBuilder_riscv&lt;ELFT&gt;</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee4beef41a86602d2a0edd01e20984ac">ELFSectionIndex</a> = unsigned</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b1342668a45fba8cd3c7c1a7509d27f">ELFSymbolIndex</a> = unsigned</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44183bd7c3c8b8ef95c900932f2db0f1">ELFFile</a> = <a href="/web-llvm/docs/api/classes/llvm/object/elffile">object::ELFFile</a>&lt; ELFT &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4209efe05789ea6287d2499d5366763f">ELFLinkGraphBuilder</a> (const object::ELFFile&lt; ELFT &gt; &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, Triple TT, SubtargetFeatures Features, StringRef FileName, LinkGraph::GetEdgeKindNameFunction GetEdgeKindName)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder">ELFLinkGraphBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59375089c93523c99145a7d1598c3ce5">setProcessDebugSections</a> (bool ProcessDebugSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug sections are included in the graph by default. <a href="#a59375089c93523c99145a7d1598c3ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59a33017f4335b8fe1884ac2b18f2660">buildGraph</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to construct and return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>. <a href="#a59a33017f4335b8fe1884ac2b18f2660">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32d66ea16f81504e5f47b4ff58b54314">addRelocations</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call to derived class to handle relocations. <a href="#a32d66ea16f81504e5f47b4ff58b54314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RelocHandlerFunction&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d2f87d599884cbc4bbdbd1fa68052f9">forEachRelaRelocation</a> (const typename ELFT::Shdr &amp;RelSect, RelocHandlerFunction &amp;&amp;Func)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RelocHandlerFunction&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b05ea912d8cd67c968c579e3d81cef7">forEachRelRelocation</a> (const typename ELFT::Shdr &amp;RelSect, RelocHandlerFunction &amp;&amp;Func)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a99d320250072eedb3e17ccf91357b8f8">isRelocatable</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac488cf57d13cfa6309bd3f4c8ed27064">setGraphBlock</a> (ELFSectionIndex SecIndex, Block *B)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6875308e07f4d36dac6d14117fad5e88">getGraphBlock</a> (ELFSectionIndex SecIndex)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a644dc80a1e7705eadfa4ef5f14954d49">setGraphSymbol</a> (ELFSymbolIndex SymIndex, Symbol &amp;Sym)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0e826b8ee88a20e683abeda705d6b7c">getGraphSymbol</a> (ELFSymbolIndex SymIndex)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ee48f5c596e107166173613128666e1">getSymbolLinkageAndScope</a> (const typename ELFT::Sym &amp;Sym, StringRef Name) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fd">Scope</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c78295b0d539ecf0607c3f8361bb2ab">makeTargetFlags</a> (const typename ELFT::Sym &amp;Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target flags on the given <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a5c78295b0d539ecf0607c3f8361bb2ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c3c8f5f6792a7ddc3d09ceca86b7ad2">getRawOffset</a> (const typename ELFT::Sym &amp;Sym, TargetFlagsType Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the physical offset of the symbol on the target platform. <a href="#a1c3c8f5f6792a7ddc3d09ceca86b7ad2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a634163eb7e686efd2bfb3cead4d5e362">prepare</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3ffb18516cfadbf9131f7d6b17fad71">graphifySections</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cd958aefa56450fda2165d5a34886cf">graphifySymbols</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26f5b43b8d19608b2184891f5c3e843e">excludeSection</a> (const typename ELFT::Shdr &amp;Sect) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override in derived classes to suppress certain sections in the link graph. <a href="#a26f5b43b8d19608b2184891f5c3e843e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RelocHandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad88274d0bf0c267fe58d1d4647d1a80e">forEachRelaRelocation</a> (const typename ELFT::Shdr &amp;RelSect, RelocHandlerMethod &amp;&amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse all matching ELFT::Rela relocation records in the given section. <a href="#ad88274d0bf0c267fe58d1d4647d1a80e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RelocHandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ae3085c347c24448e24fc102a5ca956">forEachRelRelocation</a> (const typename ELFT::Shdr &amp;RelSect, RelocHandlerMethod &amp;&amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse all matching ELFT::Rel relocation records in the given section. <a href="#a0ae3085c347c24448e24fc102a5ca956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ClassT, typename RelocHandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a41cf965b327ab7e2dfa2f8a6fea08881">forEachRelaRelocation</a> (const typename ELFT::Shdr &amp;RelSect, ClassT *Instance, RelocHandlerMethod &amp;&amp;Method)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse all matching rela relocation records in the given section. <a href="#a41cf965b327ab7e2dfa2f8a6fea08881">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ClassT, typename RelocHandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b8257f8b8b97f0b835fbda61458c2cb">forEachRelRelocation</a> (const typename ELFT::Shdr &amp;RelSect, ClassT *Instance, RelocHandlerMethod &amp;&amp;Method)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse all matching rel relocation records in the given section. <a href="#a6b8257f8b8b97f0b835fbda61458c2cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a325728a6d5c1a376a01c854a48b11476">Obj</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ELFFile::Elf_Shdr_Range</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf47db6e6e0a52a325e54b980d852423">Sections</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ELFFile::Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09e023b2edff4ce22b4de39c1ffef5dd">SymTabSec</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d5c4f277b10a3dcc3eb7cffc1e4f840">SectionStringTab</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8c8851bb8f3e9ae67ed0d376d40790f">ProcessDebugSections</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#aee4beef41a86602d2a0edd01e20984ac">ELFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afef696919d9aa78d08cf025c7416c2b9">GraphBlocks</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#a8b1342668a45fba8cd3c7c1a7509d27f">ELFSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa15106b1fb70f2a8e36a2d9d85ebbb18">GraphSymbols</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFFile::Elf_Shdr *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; typename ELFFile::Elf_Word &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30673853025c7fba1dd45aa76b5bb352">ShndxTables</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> building code that's specific to the given ELFT, but common across all architectures.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### ELFSectionIndex {#aee4beef41a86602d2a0edd01e20984ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFSectionIndex =  unsigned</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>

</div>
</div>

### ELFSymbolIndex {#a8b1342668a45fba8cd3c7c1a7509d27f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFSymbolIndex =  unsigned</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ELFFile {#a44183bd7c3c8b8ef95c900932f2db0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFFile =  object::ELFFile&lt;ELFT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFLinkGraphBuilder() {#a4209efe05789ea6287d2499d5366763f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFLinkGraphBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">object::ELFFile</a>&lt; ELFT &gt; &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ab689952831ce5e7f898c8d961bf37f22">LinkGraph::GetEdgeKindNameFunction</a> GetEdgeKindName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#aa28fe44618f3ca26c656b19d95ec740f">llvm::jitlink::ELFLinkGraphBuilderBase::ELFLinkGraphBuilderBase</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-elf-aarch64-cpp-/elflinkgraphbuilder-aarch64/#ab07fca3cb5c79b4000e48e4d3585aef7">anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::ELFLinkGraphBuilder_aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-i386/#aa39bb6cf20da3df36666a4d5de8f0a31">llvm::jitlink::ELFLinkGraphBuilder_i386&lt; ELFT &gt;::ELFLinkGraphBuilder_i386</a>, <a href="/web-llvm/docs/api/classes/anonymous-elf-loongarch-cpp-/elflinkgraphbuilder-loongarch/#a18d961ea503b8f12b610174e273068ff">anonymous{ELF_loongarch.cpp}::ELFLinkGraphBuilder_loongarch&lt; ELFT &gt;::ELFLinkGraphBuilder_loongarch</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-riscv/#a297f45e62b904349a932f3923358bf50">llvm::jitlink::ELFLinkGraphBuilder_riscv&lt; ELFT &gt;::ELFLinkGraphBuilder_riscv</a> and <a href="#a59375089c93523c99145a7d1598c3ce5">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setProcessDebugSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRelocations() {#a32d66ea16f81504e5f47b4ff58b54314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::addRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call to derived class to handle relocations.</p>


<p>These require architecture specific knowledge to map to JITLink edge kinds.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a59a33017f4335b8fe1884ac2b18f2660">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph</a>.</p>

</div>
</div>

### buildGraph() {#a59a33017f4335b8fe1884ac2b18f2660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; LinkGraph &gt; &gt; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to construct and return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="#a32d66ea16f81504e5f47b4ff58b54314">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::addRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#a62dc7478d5f4af01d7eb558a3cb588c5">llvm::jitlink::ELFLinkGraphBuilderBase::G</a>, <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>, <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>, <a href="#a99d320250072eedb3e17ccf91357b8f8">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::isRelocatable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#acc01b07763ec8c4b7acd6ffaa69b1c0c">prepare</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a85b7da2fbe9dbb9291c2ebeba26baa11">llvm::jitlink::createLinkGraphFromELFObject_aarch32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a2a0dc55fe67dc6e71c079367865cd57a">llvm::jitlink::createLinkGraphFromELFObject_i386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af23db7aa950c030363b723a4558961f7">llvm::jitlink::createLinkGraphFromELFObject_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a1f68b000ad84d40757482a867e804ce9">llvm::jitlink::createLinkGraphFromELFObject_riscv</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ade7e70a675849d2a83bd269102ab6f55">llvm::jitlink::createLinkGraphFromELFObject_x86_64</a>.</p>

</div>
</div>

### forEachRelaRelocation() {#a3d2f87d599884cbc4bbdbd1fa68052f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RelocHandlerFunction&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelaRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, RelocHandlerFunction &amp;&amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>

</div>
</div>

### forEachRelRelocation() {#a9b05ea912d8cd67c968c579e3d81cef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RelocHandlerFunction&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, RelocHandlerFunction &amp;&amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>

</div>
</div>

### setProcessDebugSections() {#a59375089c93523c99145a7d1598c3ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFLinkGraphBuilder &amp; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setProcessDebugSections (bool ProcessDebugSections)</td>
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

<p>Debug sections are included in the graph by default.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> setProcessDebugSections(false) to ignore them if debug info is not needed.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="#a4209efe05789ea6287d2499d5366763f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFLinkGraphBuilder</a> and <a href="#aa8c8851bb8f3e9ae67ed0d376d40790f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ProcessDebugSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### excludeSection() {#a26f5b43b8d19608b2184891f5c3e843e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::excludeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; Sect)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Override in derived classes to suppress certain sections in the link graph.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>.</p>

</div>
</div>

### forEachRelaRelocation() {#ad88274d0bf0c267fe58d1d4647d1a80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RelocHandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelaRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, RelocHandlerMethod &amp;&amp; Func)</td>
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

<p>Traverse all matching ELFT::Rela relocation records in the given section.</p>


<p>The handler function Func should be callable with this signature: <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">Error(const typename ELFT::Rela &amp;,
        const typename ELFT::Shdr &amp;, Section &amp;)</a></p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a41cf965b327ab7e2dfa2f8a6fea08881">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelaRelocation</a>.</p>

</div>
</div>

### forEachRelaRelocation() {#a41cf965b327ab7e2dfa2f8a6fea08881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ClassT, typename RelocHandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelaRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, ClassT * Instance, RelocHandlerMethod &amp;&amp; Method)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Traverse all matching rela relocation records in the given section.</p>


<p>Convenience wrapper to allow passing a member function for the handler.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Reference <a href="#ad88274d0bf0c267fe58d1d4647d1a80e">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelaRelocation</a>.</p>

</div>
</div>

### forEachRelRelocation() {#a0ae3085c347c24448e24fc102a5ca956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RelocHandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, RelocHandlerMethod &amp;&amp; Func)</td>
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

<p>Traverse all matching ELFT::Rel relocation records in the given section.</p>


<p>The handler function Func should be callable with this signature: <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">Error(const typename ELFT::Rel &amp;,
        const typename ELFT::Shdr &amp;, Section &amp;)</a></p>


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6b8257f8b8b97f0b835fbda61458c2cb">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelRelocation</a>.</p>

</div>
</div>

### forEachRelRelocation() {#a6b8257f8b8b97f0b835fbda61458c2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ClassT, typename RelocHandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; RelSect, ClassT * Instance, RelocHandlerMethod &amp;&amp; Method)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Traverse all matching rel relocation records in the given section.</p>


<p>Convenience wrapper to allow passing a member function for the handler.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Reference <a href="#a0ae3085c347c24448e24fc102a5ca956">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::forEachRelRelocation</a>.</p>

</div>
</div>

### getGraphBlock() {#a6875308e07f4d36dac6d14117fad5e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block * llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getGraphBlock (<a href="#aee4beef41a86602d2a0edd01e20984ac">ELFSectionIndex</a> SecIndex)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Reference <a href="#afef696919d9aa78d08cf025c7416c2b9">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphBlocks</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>.</p>

</div>
</div>

### getGraphSymbol() {#af0e826b8ee88a20e683abeda705d6b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol * llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getGraphSymbol (<a href="#a8b1342668a45fba8cd3c7c1a7509d27f">ELFSymbolIndex</a> SymIndex)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Reference <a href="#aa15106b1fb70f2a8e36a2d9d85ebbb18">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphSymbols</a>.</p>

</div>
</div>

### getRawOffset() {#a1c3c8f5f6792a7ddc3d09ceca86b7ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual orc::ExecutorAddrDiff llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getRawOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Sym &amp; Sym, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the physical offset of the symbol on the target platform.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>.</p>

</div>
</div>

### getSymbolLinkageAndScope() {#a6ee48f5c596e107166173613128666e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::pair&lt; Linkage, Scope &gt; &gt; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getSymbolLinkageAndScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Sym &amp; Sym, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda7a1920d61156abc05a60135aefe8bc67">llvm::jitlink::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda7acdf85c69cc3c5305456a293524386e">llvm::jitlink::Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda509820290d57f333403f490dde7316f4">llvm::jitlink::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77af266d61f5074811ef82444eeeff11c89">llvm::ELF::STB_GNU_UNIQUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fac43e0fd449c758dab8f891d8e19eb1a9">llvm::jitlink::Strong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5a443262fcc164a05e17cef6868ab529d3">llvm::ELF::STV_INTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5aec3ecfdbfbbe90889a70c56df29b263a">llvm::ELF::STV_PROTECTED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fa7324e3727807d95037eb19d304fd91ec">llvm::jitlink::Weak</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>.</p>

</div>
</div>

### graphifySections() {#af3ffb18516cfadbf9131f7d6b17fad71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a26f5b43b8d19608b2184891f5c3e843e">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::excludeSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#a62dc7478d5f4af01d7eb558a3cb588c5">llvm::jitlink::ELFLinkGraphBuilderBase::G</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6a777f2725a7af3806c6bb86c58bc0b5c8">llvm::orc::NoAlloc</a>, <a href="#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>, <a href="#aa8c8851bb8f3e9ae67ed0d376d40790f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ProcessDebugSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>, <a href="#aaf47db6e6e0a52a325e54b980d852423">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Sections</a>, <a href="#a7d5c4f277b10a3dcc3eb7cffc1e4f840">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SectionStringTab</a>, <a href="#ac488cf57d13cfa6309bd3f4c8ed27064">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcaa675d440c8d52c279366ca75fcb2d173">llvm::ELF::SHT_ARM_EXIDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca297934c88ffed33d2a236e1779419a9c">llvm::ELF::SHT_NULL</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a1129c0e4d43f2d121652a7302712cff6">llvm::orc::Write</a>.</p>


<p>Referenced by <a href="#a59a33017f4335b8fe1884ac2b18f2660">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph</a>.</p>

</div>
</div>

### graphifySymbols() {#a6cd958aefa56450fda2165d5a34886cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda7a1920d61156abc05a60135aefe8bc67">llvm::jitlink::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#a62dc7478d5f4af01d7eb558a3cb588c5">llvm::jitlink::ELFLinkGraphBuilderBase::G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#a51864540ec78e616ea71900324ab7137">llvm::jitlink::ELFLinkGraphBuilderBase::getCommonSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0123e359eccc453af98b12d2b5ce2516">llvm::object::getExtendedSymbolTableIndex</a>, <a href="#a6875308e07f4d36dac6d14117fad5e88">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getGraphBlock</a>, <a href="#a1c3c8f5f6792a7ddc3d09ceca86b7ad2">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getRawOffset</a>, <a href="#a6ee48f5c596e107166173613128666e1">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getSymbolLinkageAndScope</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda509820290d57f333403f490dde7316f4">llvm::jitlink::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a5c78295b0d539ecf0607c3f8361bb2ab">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::makeTargetFlags</a>, <a href="#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aaf47db6e6e0a52a325e54b980d852423">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Sections</a>, <a href="#a7d5c4f277b10a3dcc3eb7cffc1e4f840">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SectionStringTab</a>, <a href="#a644dc80a1e7705eadfa4ef5f14954d49">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a18b158617442f1bf35e5b3d38135ee59">llvm::ELF::SHN_XINDEX</a>, <a href="#a30673853025c7fba1dd45aa76b5bb352">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ShndxTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fac43e0fd449c758dab8f891d8e19eb1a9">llvm::jitlink::Strong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179ab453d9dfef54b0c7fd0cbaf82b4ba9d6">llvm::ELF::STT_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a09e023b2edff4ce22b4de39c1ffef5dd">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SymTabSec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fa7324e3727807d95037eb19d304fd91ec">llvm::jitlink::Weak</a>.</p>


<p>Referenced by <a href="#a59a33017f4335b8fe1884ac2b18f2660">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph</a>.</p>

</div>
</div>

### isRelocatable() {#a99d320250072eedb3e17ccf91357b8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::isRelocatable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a> and <a href="#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>.</p>


<p>Referenced by <a href="#a59a33017f4335b8fe1884ac2b18f2660">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph</a>.</p>

</div>
</div>

### makeTargetFlags() {#a5c78295b0d539ecf0607c3f8361bb2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual TargetFlagsType llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::makeTargetFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Sym &amp; Sym)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the target flags on the given <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>.</p>

</div>
</div>

### prepare() {#a634163eb7e686efd2bfb3cead4d5e362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilderbase/#a62dc7478d5f4af01d7eb558a3cb588c5">llvm::jitlink::ELFLinkGraphBuilderBase::G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>, <a href="#aaf47db6e6e0a52a325e54b980d852423">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Sections</a>, <a href="#a7d5c4f277b10a3dcc3eb7cffc1e4f840">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SectionStringTab</a>, <a href="#a30673853025c7fba1dd45aa76b5bb352">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ShndxTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca973f4a1893cca71a0ec69aa145189486">llvm::ELF::SHT_SYMTAB_SHNDX</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a09e023b2edff4ce22b4de39c1ffef5dd">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SymTabSec</a>.</p>

</div>
</div>

### setGraphBlock() {#ac488cf57d13cfa6309bd3f4c8ed27064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphBlock (<a href="#aee4beef41a86602d2a0edd01e20984ac">ELFSectionIndex</a> SecIndex, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#afef696919d9aa78d08cf025c7416c2b9">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphBlocks</a>.</p>


<p>Referenced by <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>.</p>

</div>
</div>

### setGraphSymbol() {#a644dc80a1e7705eadfa4ef5f14954d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphSymbol (<a href="#a8b1342668a45fba8cd3c7c1a7509d27f">ELFSymbolIndex</a> SymIndex, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Sym)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa15106b1fb70f2a8e36a2d9d85ebbb18">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphSymbols</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GraphBlocks {#afef696919d9aa78d08cf025c7416c2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ELFSectionIndex, Block *&gt; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphBlocks</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6875308e07f4d36dac6d14117fad5e88">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getGraphBlock</a> and <a href="#ac488cf57d13cfa6309bd3f4c8ed27064">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphBlock</a>.</p>

</div>
</div>

### GraphSymbols {#aa15106b1fb70f2a8e36a2d9d85ebbb18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ELFSymbolIndex, Symbol *&gt; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::GraphSymbols</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#af0e826b8ee88a20e683abeda705d6b7c">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::getGraphSymbol</a> and <a href="#a644dc80a1e7705eadfa4ef5f14954d49">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setGraphSymbol</a>.</p>

</div>
</div>

### Obj {#a325728a6d5c1a376a01c854a48b11476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFFile&amp; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a4209efe05789ea6287d2499d5366763f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFLinkGraphBuilder</a>, <a href="/web-llvm/docs/api/classes/anonymous-elf-aarch64-cpp-/elflinkgraphbuilder-aarch64/#ab07fca3cb5c79b4000e48e4d3585aef7">anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::ELFLinkGraphBuilder_aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-i386/#aa39bb6cf20da3df36666a4d5de8f0a31">llvm::jitlink::ELFLinkGraphBuilder_i386&lt; ELFT &gt;::ELFLinkGraphBuilder_i386</a>, <a href="/web-llvm/docs/api/classes/anonymous-elf-loongarch-cpp-/elflinkgraphbuilder-loongarch/#a18d961ea503b8f12b610174e273068ff">anonymous{ELF_loongarch.cpp}::ELFLinkGraphBuilder_loongarch&lt; ELFT &gt;::ELFLinkGraphBuilder_loongarch</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-riscv/#a297f45e62b904349a932f3923358bf50">llvm::jitlink::ELFLinkGraphBuilder_riscv&lt; ELFT &gt;::ELFLinkGraphBuilder_riscv</a>, <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>, <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>, <a href="#a99d320250072eedb3e17ccf91357b8f8">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::isRelocatable</a> and <a href="#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>.</p>

</div>
</div>

### ProcessDebugSections {#aa8c8851bb8f3e9ae67ed0d376d40790f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ProcessDebugSections = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a> and <a href="#a59375089c93523c99145a7d1598c3ce5">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::setProcessDebugSections</a>.</p>

</div>
</div>

### Sections {#aaf47db6e6e0a52a325e54b980d852423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFFile::Elf_Shdr_Range llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Sections</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>, <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a> and <a href="#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>.</p>

</div>
</div>

### SectionStringTab {#a7d5c4f277b10a3dcc3eb7cffc1e4f840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SectionStringTab</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>, <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a> and <a href="#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>.</p>

</div>
</div>

### ShndxTables {#a30673853025c7fba1dd45aa76b5bb352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const typename ELFFile::Elf_Shdr *, ArrayRef&lt;typename ELFFile::Elf_Word&gt; &gt; llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ShndxTables</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a> and <a href="#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>.</p>

</div>
</div>

### SymTabSec {#a09e023b2edff4ce22b4de39c1ffef5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFFile::Elf_Shdr* llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::SymTabSec = nullptr</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a>.</p>


<p>Referenced by <a href="#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a> and <a href="#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elflinkgraphbuilder-h">ELFLinkGraphBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
