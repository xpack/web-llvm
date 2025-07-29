---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolize/llvmsymbolizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LLVMSymbolizer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::symbolize::LLVMSymbolizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">llvm/DebugInfo/Symbolize/Symbolize.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ddcbed43cc341e9a77a13b2f5c5084">ObjectPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f13246dbb1bf0a0544be9235e67a66">LLVMSymbolizer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4429064c9ae9ba7631bb1e4eb62aa441">LLVMSymbolizer</a> (const Options &amp;Opts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdca06adf505798c2388e3a5f9e6e843">~LLVMSymbolizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470d2db86d3df75e22b547906ca11f8a">symbolizeCode</a> (const ObjectFile &amp;Obj, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d7493b2608bb193bdd978351aa6e6d">symbolizeCode</a> (StringRef ModuleName, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9fa9004a0495935beb6e18497aa5b15">symbolizeCode</a> (ArrayRef&lt; uint8_t &gt; BuildID, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c142501ceaf80a4cec850facc43fef">symbolizeInlinedCode</a> (const ObjectFile &amp;Obj, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7016c3d38bcc526fded52588ffe69907">symbolizeInlinedCode</a> (StringRef ModuleName, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2c35a9c8998091fce4148344172bce">symbolizeInlinedCode</a> (ArrayRef&lt; uint8_t &gt; BuildID, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diglobal">DIGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30dcb9a6b361365791c5cf0286550a9">symbolizeData</a> (const ObjectFile &amp;Obj, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diglobal">DIGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb2edf3550f2ffc4b717975692ede34">symbolizeData</a> (StringRef ModuleName, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diglobal">DIGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912d766e8aac2870683b8103df360a9b">symbolizeData</a> (ArrayRef&lt; uint8_t &gt; BuildID, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5af875d56b4ad947a488f347d754eaa">symbolizeFrame</a> (const ObjectFile &amp;Obj, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a186dd84b1547b0a7bd2834242b7d1">symbolizeFrame</a> (StringRef ModuleName, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564f1273920edf3313a78f97e45e220a">symbolizeFrame</a> (ArrayRef&lt; uint8_t &gt; BuildID, object::SectionedAddress ModuleOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f4f2aabb99792d97308004be63e439">findSymbol</a> (const ObjectFile &amp;Obj, StringRef Symbol, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5865973931a02218d697845ce4673095">findSymbol</a> (StringRef ModuleName, StringRef Symbol, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8b49521a823a616246336e733879be">findSymbol</a> (ArrayRef&lt; uint8_t &gt; BuildID, StringRef Symbol, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55acc9d1e9e674ff72434597c181ecd1">flush</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ed8ab9b40fc7e7570f10a81a9c3fc1">pruneCache</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afebf63c3ae5d72cba8af7b99c6f8dc42">setBuildIDFetcher</a> (std::unique_ptr&lt; BuildIDFetcher &gt; Fetcher)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed363690d82a9bc955ab653a37e75090">getOrCreateModuleInfo</a> (StringRef ModuleName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> or an error if loading debug info failed. <a href="#aed363690d82a9bc955ab653a37e75090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92ceceab9c7f68c89cbf1f5787310ef9">symbolizeCodeCommon</a> (const T &amp;ModuleSpecifier, object::SectionedAddress ModuleOffset) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a208108b36ecced362a6a32d804f1c96d">symbolizeInlinedCodeCommon</a> (const T &amp;ModuleSpecifier, object::SectionedAddress ModuleOffset) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42239cedf7f25e58667fe50fafc982e1">symbolizeDataCommon</a> (const T &amp;ModuleSpecifier, object::SectionedAddress ModuleOffset) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diglobal">DIGlobal</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bb4a9fa4839f4969eb41207fe19ef03">symbolizeFrameCommon</a> (const T &amp;ModuleSpecifier, object::SectionedAddress ModuleOffset) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32bff1857371256bfa4aa9c6c778d696">findSymbolCommon</a> (const T &amp;ModuleSpecifier, StringRef Symbol, uint64_t Offset) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ae9d2ddbf250fe11d9a32f2effb2aa">getOrCreateModuleInfo</a> (const ObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad379b71a5d1602cd581bc13c4833e5d1">getOrCreateModuleInfo</a> (ArrayRef&lt; uint8_t &gt; BuildID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> or an error if loading debug info failed. <a href="#ad379b71a5d1602cd581bc13c4833e5d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883f0b3b726c4cb51965890931f68d39">createModuleInfo</a> (const ObjectFile *Obj, std::unique_ptr&lt; DIContext &gt; Context, StringRef ModuleName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bbc42f1bdd81935b37c19c1cf89b1a">lookUpDsymFile</a> (const std::string &amp;Path, const MachOObjectFile *ExeObj, const std::string &amp;ArchName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8845a4de1806304f7b853d557c83ca7">lookUpDebuglinkObject</a> (const std::string &amp;Path, const ObjectFile *Obj, const std::string &amp;ArchName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac64c09b55f171e9e43d32e23fcff14b6">lookUpBuildIDObject</a> (const std::string &amp;Path, const ELFObjectFileBase *Obj, const std::string &amp;ArchName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55618f08e372e722b0a4c48f665259ac">findDebugBinary</a> (const std::string &amp;OrigPath, const std::string &amp;DebuglinkName, uint32_t CRCHash, std::string &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5071e7bbb9ed376491e14aaddf102ab1">getOrFindDebugBinary</a> (const ArrayRef&lt; uint8_t &gt; BuildID, std::string &amp;Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; ObjectPair &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa657872c37ff728ef6799d06c06ef9a0">getOrCreateObjectPair</a> (const std::string &amp;Path, const std::string &amp;ArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns pair of pointers to object and debug object. <a href="#aa657872c37ff728ef6799d06c06ef9a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22811292e60698391f49fd4c92c23cd">getOrCreateObject</a> (const std::string &amp;Path, const std::string &amp;ArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to object file at specified path, for a specified architecture (e.g. <a href="#ac22811292e60698391f49fd4c92c23cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb48ed61776b2dbb931b653433304ad4">recordAccess</a> (CachedBinary &amp;Bin)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the LRU cache order when a binary is accessed. <a href="#afb48ed61776b2dbb931b653433304ad4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> &gt;, std::less&lt;&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4158917ec1b252b9c6bf61e4ddd1c0f">Modules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2c428a3f219a229554ad5272b2fec1">BuildIDPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::pair&lt; std::string, std::string &gt;, ObjectPair &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73f3db799eb247a77262339cc69f2b3">ObjectPairForPathArch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains cached results of getOrCreateObjectPair(). <a href="#aa73f3db799eb247a77262339cc69f2b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-llvm/docs/api/classes/llvm/symbolize/cachedbinary">CachedBinary</a>, std::less&lt;&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d05c706bada57e65728eab3c20998a8">BinaryForPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains parsed binary for each path, or parsing error. <a href="#a8d05c706bada57e65728eab3c20998a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/cachedbinary">CachedBinary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ef46cc070f15afb0d4d603a7daa8f5">LRUBinaries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of cached binaries in LRU order. <a href="#aa4ef46cc070f15afb0d4d603a7daa8f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67aa9383e4dd845892ba57ae08efb42">CacheSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sum of the sizes of the cached binaries. <a href="#ac67aa9383e4dd845892ba57ae08efb42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::pair&lt; std::string, std::string &gt;, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96eed8e558a9a1988475980b06eec303">ObjectForUBPathAndArch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parsed object file for path/architecture pair, where "path" refers to Mach-O universal binary. <a href="#a96eed8e558a9a1988475980b06eec303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/symbolize/llvmsymbolizer/options">Options</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afffef45b87055f831ab47afc9ac6077b">Opts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/buildidfetcher">BuildIDFetcher</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26578ee1e7ef8f1619de068c69ffd05c">BIDFetcher</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a25cb56878fe4f0431c046d1a67fcf">DemangleName</a> (StringRef Name, const SymbolizableModule *DbiModuleDescriptor)</td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ObjectPair {#a26ddcbed43cc341e9a77a13b2f5c5084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::symbolize::LLVMSymbolizer::ObjectPair =  std::pair&lt;const ObjectFile *, const ObjectFile *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLVMSymbolizer() {#a39f13246dbb1bf0a0544be9235e67a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::symbolize::LLVMSymbolizer::LLVMSymbolizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### LLVMSymbolizer() {#a4429064c9ae9ba7631bb1e4eb62aa441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::symbolize::LLVMSymbolizer::LLVMSymbolizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/symbolize/llvmsymbolizer/options">Options</a> &amp; Opts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LLVMSymbolizer() {#afdca06adf505798c2388e3a5f9e6e843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::symbolize::LLVMSymbolizer::~LLVMSymbolizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findSymbol() {#a07f4f2aabb99792d97308004be63e439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILineInfo &gt; &gt; llvm::symbolize::LLVMSymbolizer::findSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### findSymbol() {#a5865973931a02218d697845ce4673095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILineInfo &gt; &gt; llvm::symbolize::LLVMSymbolizer::findSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### findSymbol() {#a7f8b49521a823a616246336e733879be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILineInfo &gt; &gt; llvm::symbolize::LLVMSymbolizer::findSymbol (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### flush() {#a55acc9d1e9e674ff72434597c181ecd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::LLVMSymbolizer::flush ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrCreateModuleInfo() {#aed363690d82a9bc955ab653a37e75090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolizableModule * &gt; llvm::symbolize::LLVMSymbolizer::getOrCreateModuleInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> or an error if loading debug info failed.</p>


<p>Only one attempt is made to load a module, and errors during loading are only reported once. Subsequent calls to get module info for a module that failed to load will return nullptr.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6fbfbccaef05e07b2b1615224d5e20bdab6ec7abeb6ae29cc35a4b47475e12afe">llvm::DWARFContext::Process</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>.</p>

</div>
</div>

### pruneCache() {#a06ed8ab9b40fc7e7570f10a81a9c3fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::LLVMSymbolizer::pruneCache ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>.</p>

</div>
</div>

### setBuildIDFetcher() {#afebf63c3ae5d72cba8af7b99c6f8dc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::LLVMSymbolizer::setBuildIDFetcher (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/buildidfetcher">BuildIDFetcher</a> &gt; Fetcher)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### symbolizeCode() {#a470d2db86d3df75e22b547906ca11f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DILineInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeCode() {#a71d7493b2608bb193bdd978351aa6e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DILineInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeCode() {#ac9fa9004a0495935beb6e18497aa5b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DILineInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeCode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeData() {#ad30dcb9a6b361365791c5cf0286550a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIGlobal &gt; llvm::symbolize::LLVMSymbolizer::symbolizeData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeData() {#a0eb2edf3550f2ffc4b717975692ede34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIGlobal &gt; llvm::symbolize::LLVMSymbolizer::symbolizeData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeData() {#a912d766e8aac2870683b8103df360a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIGlobal &gt; llvm::symbolize::LLVMSymbolizer::symbolizeData (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeFrame() {#ad5af875d56b4ad947a488f347d754eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILocal &gt; &gt; llvm::symbolize::LLVMSymbolizer::symbolizeFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeFrame() {#a75a186dd84b1547b0a7bd2834242b7d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILocal &gt; &gt; llvm::symbolize::LLVMSymbolizer::symbolizeFrame (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeFrame() {#a564f1273920edf3313a78f97e45e220a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILocal &gt; &gt; llvm::symbolize::LLVMSymbolizer::symbolizeFrame (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeInlinedCode() {#a10c142501ceaf80a4cec850facc43fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIInliningInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeInlinedCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeInlinedCode() {#a7016c3d38bcc526fded52588ffe69907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIInliningInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeInlinedCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeInlinedCode() {#a0b2c35a9c8998091fce4148344172bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIInliningInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeInlinedCode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createModuleInfo() {#a883f0b3b726c4cb51965890931f68d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolizableModule * &gt; llvm::symbolize::LLVMSymbolizer::createModuleInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Obj, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> &gt; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### findDebugBinary() {#a55618f08e372e722b0a4c48f665259ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::LLVMSymbolizer::findDebugBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; OrigPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; DebuglinkName, uint32_t CRCHash, std::string &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### findSymbolCommon() {#a32bff1857371256bfa4aa9c6c778d696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILineInfo &gt; &gt; llvm::symbolize::LLVMSymbolizer::findSymbolCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; ModuleSpecifier, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrCreateModuleInfo() {#a17ae9d2ddbf250fe11d9a32f2effb2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolizableModule * &gt; llvm::symbolize::LLVMSymbolizer::getOrCreateModuleInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrCreateModuleInfo() {#ad379b71a5d1602cd581bc13c4833e5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolizableModule * &gt; llvm::symbolize::LLVMSymbolizer::getOrCreateModuleInfo (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> or an error if loading debug info failed.</p>


<p>Unlike the above, errors are reported each time, since they are more likely to be transient.</p>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrCreateObject() {#ac22811292e60698391f49fd4c92c23cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ObjectFile * &gt; llvm::symbolize::LLVMSymbolizer::getOrCreateObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to object file at specified path, for a specified architecture (e.g.</p>


<p>if path refers to a Mach-O universal binary, only one object file from it will be returned).</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrCreateObjectPair() {#aa657872c37ff728ef6799d06c06ef9a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; LLVMSymbolizer::ObjectPair &gt; llvm::symbolize::LLVMSymbolizer::getOrCreateObjectPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns pair of pointers to object and debug object.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### getOrFindDebugBinary() {#a5071e7bbb9ed376491e14aaddf102ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::LLVMSymbolizer::getOrFindDebugBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BuildID, std::string &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### lookUpBuildIDObject() {#ac64c09b55f171e9e43d32e23fcff14b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFile * llvm::symbolize::LLVMSymbolizer::lookUpBuildIDObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">ELFObjectFileBase</a> * Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### lookUpDebuglinkObject() {#aa8845a4de1806304f7b853d557c83ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFile * llvm::symbolize::LLVMSymbolizer::lookUpDebuglinkObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### lookUpDsymFile() {#a25bbc42f1bdd81935b37c19c1cf89b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFile * llvm::symbolize::LLVMSymbolizer::lookUpDsymFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * ExeObj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### recordAccess() {#afb48ed61776b2dbb931b653433304ad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::LLVMSymbolizer::recordAccess (<a href="/web-llvm/docs/api/classes/llvm/symbolize/cachedbinary">CachedBinary</a> &amp; Bin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the LRU cache order when a binary is accessed.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeCodeCommon() {#a92ceceab9c7f68c89cbf1f5787310ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DILineInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeCodeCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; ModuleSpecifier, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeDataCommon() {#a42239cedf7f25e58667fe50fafc982e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIGlobal &gt; llvm::symbolize::LLVMSymbolizer::symbolizeDataCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; ModuleSpecifier, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeFrameCommon() {#a9bb4a9fa4839f4969eb41207fe19ef03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; DILocal &gt; &gt; llvm::symbolize::LLVMSymbolizer::symbolizeFrameCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; ModuleSpecifier, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

### symbolizeInlinedCodeCommon() {#a208108b36ecced362a6a32d804f1c96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DIInliningInfo &gt; llvm::symbolize::LLVMSymbolizer::symbolizeInlinedCodeCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; ModuleSpecifier, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BIDFetcher {#a26578ee1e7ef8f1619de068c69ffd05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BuildIDFetcher&gt; llvm::symbolize::LLVMSymbolizer::BIDFetcher</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### BinaryForPath {#a8d05c706bada57e65728eab3c20998a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, CachedBinary, std::less&lt;&gt; &gt; llvm::symbolize::LLVMSymbolizer::BinaryForPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains parsed binary for each path, or parsing error.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### BuildIDPaths {#a7a2c428a3f219a229554ad5272b2fec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::string&gt; llvm::symbolize::LLVMSymbolizer::BuildIDPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### CacheSize {#ac67aa9383e4dd845892ba57ae08efb42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::symbolize::LLVMSymbolizer::CacheSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sum of the sizes of the cached binaries.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### LRUBinaries {#aa4ef46cc070f15afb0d4d603a7daa8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">simple_ilist&lt;CachedBinary&gt; llvm::symbolize::LLVMSymbolizer::LRUBinaries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of cached binaries in LRU order.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### Modules {#ac4158917ec1b252b9c6bf61e4ddd1c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, std::unique_ptr&lt;SymbolizableModule&gt;, std::less&lt;&gt; &gt; llvm::symbolize::LLVMSymbolizer::Modules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### ObjectForUBPathAndArch {#a96eed8e558a9a1988475980b06eec303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::pair&lt;std::string, std::string&gt;, std::unique_ptr&lt;ObjectFile&gt; &gt; llvm::symbolize::LLVMSymbolizer::ObjectForUBPathAndArch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parsed object file for path/architecture pair, where "path" refers to Mach-O universal binary.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### ObjectPairForPathArch {#aa73f3db799eb247a77262339cc69f2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::pair&lt;std::string, std::string&gt;, ObjectPair&gt; llvm::symbolize::LLVMSymbolizer::ObjectPairForPathArch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains cached results of getOrCreateObjectPair().</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

### Opts {#afffef45b87055f831ab47afc9ac6077b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Options llvm::symbolize::LLVMSymbolizer::Opts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### DemangleName() {#a06a25cb56878fe4f0431c046d1a67fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::symbolize::LLVMSymbolizer::DemangleName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a> * DbiModuleDescriptor)</td>
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



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule/#a89baf7e7fedad506270275e18daf866c">llvm::symbolize::SymbolizableModule::isWin32Module</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa7783c233c06a0bc69d1e35e551d9d66">llvm::microsoftDemangle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab12675c360e3040ee3927f7711edd1ccaf63bf19593a1d3c30c0e4a439342b01a">llvm::MSDF_NoAccessSpecifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab12675c360e3040ee3927f7711edd1ccacb2b9790f4b31c5f9721a5d3ee3dcfd0">llvm::MSDF_NoCallingConvention</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab12675c360e3040ee3927f7711edd1ccabd781b5e13efab5f5fcbba7dc64a0fe2">llvm::MSDF_NoMemberType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab12675c360e3040ee3927f7711edd1cca87b2c7c04f2b3b41116e790d024a2815">llvm::MSDF_NoReturnType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a08b5f002009fefdfceb3a1ce19c9cd74">llvm::nonMicrosoftDemangle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolize-h">Symbolize.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
