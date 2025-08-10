---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/ppc64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `ppc64` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::ppc64 { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/ppc64/pltcallstubreloc">PLTCallStubReloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/ppc64/pltcallstubinfo">PLTCallStubInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/ppc64/toctablemanager">TOCTableManager&lt;Endianness&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/ppc64/plttablemanager">PLTTableManager&lt;Endianness&gt;</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_ppc64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#a62e5186b5b7eee2c22dd5735802711d8">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64">ppc64</a> fixups and other ppc64-specific edge kinds. <a href="#a62e5186b5b7eee2c22dd5735802711d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PLTCallStubKind { <a href="#ad77331299bb93a60ec6b68f67ba1f647">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/ppc64/pltcallstubinfo">PLTCallStubInfo</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a> (PLTCallStubKind StubKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af983cbd42b003b50f4493f08537760">createAnonymousPointer</a> (LinkGraph &amp;G, Section &amp;PointerSection, Symbol *InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab69bfee9fa1bf844067b1fd7dcbe7c0f">createAnonymousPointerJumpStub</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol, PLTCallStubKind StubKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b4e81f6af068dca6146fc28dc7798c">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64">ppc64</a> edge. <a href="#ad7b4e81f6af068dca6146fc28dc7798c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe519e4252b73db73b60ecaba996ed66">ha</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb8c6422f71e2ff4c020b69edba7092">lo</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60b257f5642b6ef298f4823e1bd9c40">hi</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10bf34cf16f827b66aedff324e95414c">high</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3235e98ccd48375ccab823a6d229158c">higha</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ff5cbb9c9e7caf609d3199804b85f6">higher</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0eed5611facff97fe3426e8198c9627">highera</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d46208c1ad00cc97abe97c1d5d70a8">highest</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ebd214c57a62bd47c6d9f4511f19f3">highesta</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a83d1d9a3a78b81e6e828a5a0d1ab14">readPrefixedInstruction</a> (const char *Loc)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0e3eba95ca2e695b6174ee43ddee641">writePrefixedInstruction</a> (char *Loc, uint64_t Inst)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a> (char *FixupPtr, int64_t Value, Edge::Kind K)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a393f897c1439c03e7ef35e7874a8a1">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const Symbol *TOCSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a5a393f897c1439c03e7ef35e7874a8a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d013b0f3408b60743d2745805183a2">NullPointerContent</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca7d2cf36e95f28dad5821a6ced5c65">PointerJumpStubContent_big</a>[20] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c9344825e3374055c1aa2c37a9d215">PointerJumpStubContent_little</a>[20] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f712e85ea0e1addd169a2c6808d21e">PointerJumpStubNoTOCContent_big</a>[32] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935c849316d2a5f519f6a895003682d9">PointerJumpStubNoTOCContent_little</a>[32] = ...</td>
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

## Enumerations

### EdgeKind\_ppc64 {#a62e5186b5b7eee2c22dd5735802711d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::ppc64::EdgeKind_ppc64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64">ppc64</a> fixups and other ppc64-specific edge kinds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer64<a id="a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c"></a></td>
<td class="doxyEnumItemDescription"> (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32<a id="a62e5186b5b7eee2c22dd5735802711d8a551e5ee00d86159689c751384e0874b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16<a id="a62e5186b5b7eee2c22dd5735802711d8aceeb19fca5512a7bac0edb124d677750"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16DS<a id="a62e5186b5b7eee2c22dd5735802711d8a8f5996ed66d0d92daf46f2fbcd810d9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HA<a id="a62e5186b5b7eee2c22dd5735802711d8a194531e549577b0a60dfcde0ee7ba465"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HI<a id="a62e5186b5b7eee2c22dd5735802711d8a76cb12acd953fa95131b4471830dcf63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGH<a id="a62e5186b5b7eee2c22dd5735802711d8a70d7af46f4e6ae2b676950db87b87927"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGHA<a id="a62e5186b5b7eee2c22dd5735802711d8ac6064856e55e6f9e0ff9b3fd1fed57fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGHER<a id="a62e5186b5b7eee2c22dd5735802711d8a2c9f1b52b5ccfe7f34adb6e923687983"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGHERA<a id="a62e5186b5b7eee2c22dd5735802711d8a772ad43e2c0d77f207102325ee4680bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGHEST<a id="a62e5186b5b7eee2c22dd5735802711d8ae8ee95c893ebc6351b6c33738b48ff48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16HIGHESTA<a id="a62e5186b5b7eee2c22dd5735802711d8a9656b2b0a80db7f69fdaa2ca318dd1ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16LO<a id="a62e5186b5b7eee2c22dd5735802711d8aaca9eac93e67b54778b4a6056e6f3282"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16LODS<a id="a62e5186b5b7eee2c22dd5735802711d8a225a688021e96cd255bc56385b59b601"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer14<a id="a62e5186b5b7eee2c22dd5735802711d8af0c13241ad3d51030689f69aa6b3e880"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta64<a id="a62e5186b5b7eee2c22dd5735802711d8a04a96d6936e50e40ca5d4f101fc130be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta34<a id="a62e5186b5b7eee2c22dd5735802711d8a208d06ad3405d944c445dd9cb4b876aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32<a id="a62e5186b5b7eee2c22dd5735802711d8aee4b6a1a62914c9ea1ae1f178f83e7ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta32<a id="a62e5186b5b7eee2c22dd5735802711d8a860bed662bc02f169596d8a5141e3f80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta16<a id="a62e5186b5b7eee2c22dd5735802711d8a5f85bdc567e9b6b38963eca9237ae400"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta16HA<a id="a62e5186b5b7eee2c22dd5735802711d8abbda2820184655cc00350aebe61880da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta16HI<a id="a62e5186b5b7eee2c22dd5735802711d8a8cbcf10b41068ab29122ef0108fcb5bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta16LO<a id="a62e5186b5b7eee2c22dd5735802711d8ae227773b26af6f85b016098e383dccbd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOC<a id="a62e5186b5b7eee2c22dd5735802711d8aa4e4e080965998564544a54e6c728978"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16<a id="a62e5186b5b7eee2c22dd5735802711d8a8a7a362088847a5e0059b58af40a76cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16DS<a id="a62e5186b5b7eee2c22dd5735802711d8a3ca4cb6a48fe17c9863ea50a2ae5c33b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16HA<a id="a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16HI<a id="a62e5186b5b7eee2c22dd5735802711d8a2e9e9771983fb7a73a196e34ffe971b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16LO<a id="a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCDelta16LODS<a id="a62e5186b5b7eee2c22dd5735802711d8a6fec2953052b733a1b502bf262ce6cb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta34<a id="a62e5186b5b7eee2c22dd5735802711d8aa84f7972c0a12e1bf6aa019b58256350"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallBranchDelta<a id="a62e5186b5b7eee2c22dd5735802711d8a780cf19d32608305f3ff9f6bc608fc5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallBranchDeltaRestoreTOC<a id="a62e5186b5b7eee2c22dd5735802711d8a9d234b4c87550cd262b57c5ce985bcd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestCall<a id="a62e5186b5b7eee2c22dd5735802711d8a66cef4072aff701e2e6a9ad3fd97949c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestCallNoTOC<a id="a62e5186b5b7eee2c22dd5735802711d8a3dd07b851b91e43558e5afbf6e7dc405"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescInGOTAndTransformToTOCDelta16HA<a id="a62e5186b5b7eee2c22dd5735802711d8a1d56faaaf3676f55c53f948247267ee7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescInGOTAndTransformToTOCDelta16LO<a id="a62e5186b5b7eee2c22dd5735802711d8ac5d30e291a54fa2a02d0e940b6e6caf3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescInGOTAndTransformToDelta34<a id="a62e5186b5b7eee2c22dd5735802711d8af8e4dff79b8ebb15b6a0507ea61530e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>

</div>
</div>

### PLTCallStubKind {#ad77331299bb93a60ec6b68f67ba1f647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::ppc64::PLTCallStubKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LongBranch<a id="ad77331299bb93a60ec6b68f67ba1f647a00314ccb6ef794d99abe2185ea102cf8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LongBranchSaveR2<a id="ad77331299bb93a60ec6b68f67ba1f647a2f746789376d61bd3da51bbcee7bc71b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LongBranchNoTOC<a id="ad77331299bb93a60ec6b68f67ba1f647ad3d94b74f7d44e83de7fc936daea0455"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### applyFixup() {#a5a393f897c1439c03e7ef35e7874a8a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ppc64::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * TOCSymbol)</td>
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

<p>Apply fixup expression for edge to block content.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a780cf19d32608305f3ff9f6bc608fc5e">CallBranchDelta</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a9d234b4c87550cd262b57c5ce985bcd2">CallBranchDeltaRestoreTOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a5f85bdc567e9b6b38963eca9237ae400">Delta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8abbda2820184655cc00350aebe61880da">Delta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8cbcf10b41068ab29122ef0108fcb5bd">Delta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae227773b26af6f85b016098e383dccbd">Delta16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aee4b6a1a62914c9ea1ae1f178f83e7ec">Delta32</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a208d06ad3405d944c445dd9cb4b876aa">Delta34</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a04a96d6936e50e40ca5d4f101fc130be">Delta64</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="#ad7b4e81f6af068dca6146fc28dc7798c">getEdgeKindName</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a860bed662bc02f169596d8a5141e3f80">NegDelta32</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8af0c13241ad3d51030689f69aa6b3e880">Pointer14</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aceeb19fca5512a7bac0edb124d677750">Pointer16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8f5996ed66d0d92daf46f2fbcd810d9d">Pointer16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a194531e549577b0a60dfcde0ee7ba465">Pointer16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a76cb12acd953fa95131b4471830dcf63">Pointer16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a70d7af46f4e6ae2b676950db87b87927">Pointer16HIGH</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac6064856e55e6f9e0ff9b3fd1fed57fa">Pointer16HIGHA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2c9f1b52b5ccfe7f34adb6e923687983">Pointer16HIGHER</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a772ad43e2c0d77f207102325ee4680bb">Pointer16HIGHERA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae8ee95c893ebc6351b6c33738b48ff48">Pointer16HIGHEST</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a9656b2b0a80db7f69fdaa2ca318dd1ed">Pointer16HIGHESTA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aaca9eac93e67b54778b4a6056e6f3282">Pointer16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a225a688021e96cd255bc56385b59b601">Pointer16LODS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c">Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a1fda585fbf18128d11d28fa4c5b0ad7d">llvm::support::endian::read32</a>, <a href="#a9a83d1d9a3a78b81e6e828a5a0d1ab14">readPrefixedInstruction</a>, <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aa4e4e080965998564544a54e6c728978">TOC</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8a7a362088847a5e0059b58af40a76cd">TOCDelta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a3ca4cb6a48fe17c9863ea50a2ae5c33b">TOCDelta16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3">TOCDelta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2e9e9771983fb7a73a196e34ffe971b4">TOCDelta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f">TOCDelta16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a6fec2953052b733a1b502bf262ce6cb9">TOCDelta16LODS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a532f663ee4cfcf65d78284c90327b43c">llvm::support::endian::write32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ad9d1f26310997ed6b5adfa0366c7ded3">llvm::support::endian::write64</a> and <a href="#aa0e3eba95ca2e695b6174ee43ddee641">writePrefixedInstruction</a>.</p>

</div>
</div>

### createAnonymousPointer() {#a4af983cbd42b003b50f4493f08537760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::ppc64::createAnonymousPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; PointerSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a91d013b0f3408b60743d2745805183a2">NullPointerContent</a> and <a href="#a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c">Pointer64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/ppc64/toctablemanager/#aab224327b17591ab707664d09956264d">llvm::jitlink::ppc64::TOCTableManager&lt; Endianness &gt;::createEntry</a>.</p>

</div>
</div>

### createAnonymousPointerJumpStub() {#ab69bfee9fa1bf844067b1fd7dcbe7c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::ppc64::createAnonymousPointerJumpStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol, <a href="#ad77331299bb93a60ec6b68f67ba1f647">PLTCallStubKind</a> StubKind)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/ppc64/pltcallstubinfo/#a4ead91bd05783deb4fe35ea66d433cd8">llvm::jitlink::ppc64::PLTCallStubInfo::Content</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/ppc64/pltcallstubinfo/#ad47b86a7439fc74cabb28ab1847c1bc9">llvm::jitlink::ppc64::PLTCallStubInfo::Relocs</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/ppc64/plttablemanager/#ad23651cc8e91d89610342d91ccf43ce1">llvm::jitlink::ppc64::PLTTableManager&lt; Endianness &gt;::createEntry</a>.</p>

</div>
</div>

### getEdgeKindName() {#ad7b4e81f6af068dca6146fc28dc7798c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::ppc64::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64">ppc64</a> edge.</p>


<p>For debugging purposes only.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>References <a href="#a62e5186b5b7eee2c22dd5735802711d8a780cf19d32608305f3ff9f6bc608fc5e">CallBranchDelta</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a9d234b4c87550cd262b57c5ce985bcd2">CallBranchDeltaRestoreTOC</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a5f85bdc567e9b6b38963eca9237ae400">Delta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8abbda2820184655cc00350aebe61880da">Delta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8cbcf10b41068ab29122ef0108fcb5bd">Delta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae227773b26af6f85b016098e383dccbd">Delta16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aee4b6a1a62914c9ea1ae1f178f83e7ec">Delta32</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a208d06ad3405d944c445dd9cb4b876aa">Delta34</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a04a96d6936e50e40ca5d4f101fc130be">Delta64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a860bed662bc02f169596d8a5141e3f80">NegDelta32</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8af0c13241ad3d51030689f69aa6b3e880">Pointer14</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aceeb19fca5512a7bac0edb124d677750">Pointer16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8f5996ed66d0d92daf46f2fbcd810d9d">Pointer16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a194531e549577b0a60dfcde0ee7ba465">Pointer16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a76cb12acd953fa95131b4471830dcf63">Pointer16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a70d7af46f4e6ae2b676950db87b87927">Pointer16HIGH</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac6064856e55e6f9e0ff9b3fd1fed57fa">Pointer16HIGHA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2c9f1b52b5ccfe7f34adb6e923687983">Pointer16HIGHER</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a772ad43e2c0d77f207102325ee4680bb">Pointer16HIGHERA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae8ee95c893ebc6351b6c33738b48ff48">Pointer16HIGHEST</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a9656b2b0a80db7f69fdaa2ca318dd1ed">Pointer16HIGHESTA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aaca9eac93e67b54778b4a6056e6f3282">Pointer16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a225a688021e96cd255bc56385b59b601">Pointer16LODS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a551e5ee00d86159689c751384e0874b4">Pointer32</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c">Pointer64</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a66cef4072aff701e2e6a9ad3fd97949c">RequestCall</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a3dd07b851b91e43558e5afbf6e7dc405">RequestCallNoTOC</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aa84f7972c0a12e1bf6aa019b58256350">RequestGOTAndTransformToDelta34</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8af8e4dff79b8ebb15b6a0507ea61530e6">RequestTLSDescInGOTAndTransformToDelta34</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a1d56faaaf3676f55c53f948247267ee7">RequestTLSDescInGOTAndTransformToTOCDelta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac5d30e291a54fa2a02d0e940b6e6caf3">RequestTLSDescInGOTAndTransformToTOCDelta16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aa4e4e080965998564544a54e6c728978">TOC</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8a7a362088847a5e0059b58af40a76cd">TOCDelta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a3ca4cb6a48fe17c9863ea50a2ae5c33b">TOCDelta16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3">TOCDelta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2e9e9771983fb7a73a196e34ffe971b4">TOCDelta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f">TOCDelta16LO</a> and <a href="#a62e5186b5b7eee2c22dd5735802711d8a6fec2953052b733a1b502bf262ce6cb9">TOCDelta16LODS</a>.</p>


<p>Referenced by <a href="#a5a393f897c1439c03e7ef35e7874a8a1">applyFixup</a> and <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### ha() {#afe519e4252b73db73b60ecaba996ed66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::ppc64::ha (uint64_t x)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### hi() {#ae60b257f5642b6ef298f4823e1bd9c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::ppc64::hi (uint64_t x)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### high() {#a10bf34cf16f827b66aedff324e95414c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::high (uint64_t x)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### higha() {#a3235e98ccd48375ccab823a6d229158c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::higha (uint64_t x)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### higher() {#a86ff5cbb9c9e7caf609d3199804b85f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::higher (uint64_t x)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### highera() {#ad0eed5611facff97fe3426e8198c9627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::highera (uint64_t x)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### highest() {#ac6d46208c1ad00cc97abe97c1d5d70a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::ppc64::highest (uint64_t x)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### highesta() {#a60ebd214c57a62bd47c6d9f4511f19f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::ppc64::highesta (uint64_t x)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### lo() {#a0bb8c6422f71e2ff4c020b69edba7092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::lo (uint64_t x)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>Referenced by <a href="#a1b090e84230aaa1ea8df579d5ca9efcd">relocateHalf16</a>.</p>

</div>
</div>

### pickStub() {#a33ec230e070e9dc242e28bf8fd9c28f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PLTCallStubInfo llvm::jitlink::ppc64::pickStub (<a href="#ad77331299bb93a60ec6b68f67ba1f647">PLTCallStubKind</a> StubKind)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="#a62e5186b5b7eee2c22dd5735802711d8abbda2820184655cc00350aebe61880da">Delta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae227773b26af6f85b016098e383dccbd">Delta16LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ad77331299bb93a60ec6b68f67ba1f647a00314ccb6ef794d99abe2185ea102cf8">LongBranch</a>, <a href="#ad77331299bb93a60ec6b68f67ba1f647ad3d94b74f7d44e83de7fc936daea0455">LongBranchNoTOC</a>, <a href="#ad77331299bb93a60ec6b68f67ba1f647a2f746789376d61bd3da51bbcee7bc71b">LongBranchSaveR2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a6ca7d2cf36e95f28dad5821a6ced5c65">PointerJumpStubContent_big</a>, <a href="#a65c9344825e3374055c1aa2c37a9d215">PointerJumpStubContent_little</a>, <a href="#a30f712e85ea0e1addd169a2c6808d21e">PointerJumpStubNoTOCContent_big</a>, <a href="#a935c849316d2a5f519f6a895003682d9">PointerJumpStubNoTOCContent_little</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3">TOCDelta16HA</a> and <a href="#a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f">TOCDelta16LO</a>.</p>


<p>Referenced by <a href="#ab69bfee9fa1bf844067b1fd7dcbe7c0f">createAnonymousPointerJumpStub</a>.</p>

</div>
</div>

### readPrefixedInstruction() {#a9a83d1d9a3a78b81e6e828a5a0d1ab14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::ppc64::readPrefixedInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Loc)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7787225426474d5f50e2f0c4e3c16b1c">llvm::support::endian::read64</a>.</p>


<p>Referenced by <a href="#a5a393f897c1439c03e7ef35e7874a8a1">applyFixup</a>.</p>

</div>
</div>

### relocateHalf16() {#a1b090e84230aaa1ea8df579d5ca9efcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ppc64::relocateHalf16 (char * FixupPtr, int64_t Value, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="#a62e5186b5b7eee2c22dd5735802711d8a5f85bdc567e9b6b38963eca9237ae400">Delta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8abbda2820184655cc00350aebe61880da">Delta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8cbcf10b41068ab29122ef0108fcb5bd">Delta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae227773b26af6f85b016098e383dccbd">Delta16LO</a>, <a href="#ad7b4e81f6af068dca6146fc28dc7798c">getEdgeKindName</a>, <a href="#afe519e4252b73db73b60ecaba996ed66">ha</a>, <a href="#ae60b257f5642b6ef298f4823e1bd9c40">hi</a>, <a href="#a10bf34cf16f827b66aedff324e95414c">high</a>, <a href="#a3235e98ccd48375ccab823a6d229158c">higha</a>, <a href="#a86ff5cbb9c9e7caf609d3199804b85f6">higher</a>, <a href="#ad0eed5611facff97fe3426e8198c9627">highera</a>, <a href="#ac6d46208c1ad00cc97abe97c1d5d70a8">highest</a>, <a href="#a60ebd214c57a62bd47c6d9f4511f19f3">highesta</a>, <a href="#a0bb8c6422f71e2ff4c020b69edba7092">lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aceeb19fca5512a7bac0edb124d677750">Pointer16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8f5996ed66d0d92daf46f2fbcd810d9d">Pointer16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a194531e549577b0a60dfcde0ee7ba465">Pointer16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a76cb12acd953fa95131b4471830dcf63">Pointer16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a70d7af46f4e6ae2b676950db87b87927">Pointer16HIGH</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac6064856e55e6f9e0ff9b3fd1fed57fa">Pointer16HIGHA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2c9f1b52b5ccfe7f34adb6e923687983">Pointer16HIGHER</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a772ad43e2c0d77f207102325ee4680bb">Pointer16HIGHERA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ae8ee95c893ebc6351b6c33738b48ff48">Pointer16HIGHEST</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a9656b2b0a80db7f69fdaa2ca318dd1ed">Pointer16HIGHESTA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8aaca9eac93e67b54778b4a6056e6f3282">Pointer16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a225a688021e96cd255bc56385b59b601">Pointer16LODS</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a8a7a362088847a5e0059b58af40a76cd">TOCDelta16</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a3ca4cb6a48fe17c9863ea50a2ae5c33b">TOCDelta16DS</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3">TOCDelta16HA</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a2e9e9771983fb7a73a196e34ffe971b4">TOCDelta16HI</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f">TOCDelta16LO</a>, <a href="#a62e5186b5b7eee2c22dd5735802711d8a6fec2953052b733a1b502bf262ce6cb9">TOCDelta16LODS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a854c0fc7eb648278c0ae83f30a778d90">llvm::support::endian::write16</a>.</p>


<p>Referenced by <a href="#a5a393f897c1439c03e7ef35e7874a8a1">applyFixup</a>.</p>

</div>
</div>

### writePrefixedInstruction() {#aa0e3eba95ca2e695b6174ee43ddee641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::ppc64::writePrefixedInstruction (char * Loc, uint64_t Inst)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ad9d1f26310997ed6b5adfa0366c7ded3">llvm::support::endian::write64</a>.</p>


<p>Referenced by <a href="#a5a393f897c1439c03e7ef35e7874a8a1">applyFixup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NullPointerContent {#a91d013b0f3408b60743d2745805183a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::ppc64::NullPointerContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {0x00, 0x00, 0x00, 0x00,
                                    0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>Referenced by <a href="#a4af983cbd42b003b50f4493f08537760">createAnonymousPointer</a>.</p>

</div>
</div>

### PointerJumpStubContent\_big {#a6ca7d2cf36e95f28dad5821a6ced5c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::ppc64::PointerJumpStubContent_big</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    (char)0xf8, 0x41,       0x00, 0x18,       
    0x3d,       (char)0x82, 0x00, 0x00,       
    (char)0xe9, (char)0x8c, 0x00, 0x00,       
    0x7d,       (char)0x89, 0x03, (char)0xa6, 
    0x4e,       (char)0x80, 0x04, 0x20,       
}
</div>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>Referenced by <a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a>.</p>

</div>
</div>

### PointerJumpStubContent\_little {#a65c9344825e3374055c1aa2c37a9d215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::ppc64::PointerJumpStubContent_little</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x18,       0x00, 0x41,       (char)0xf8, 
    0x00,       0x00, (char)0x82, 0x3d,       
    0x00,       0x00, (char)0x8c, (char)0xe9, 
    (char)0xa6, 0x03, (char)0x89, 0x7d,       
    0x20,       0x04, (char)0x80, 0x4e,       
}
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>Referenced by <a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a>.</p>

</div>
</div>

### PointerJumpStubNoTOCContent\_big {#a30f712e85ea0e1addd169a2c6808d21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::ppc64::PointerJumpStubNoTOCContent_big</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x7d,       (char)0x88, 0x02, (char)0xa6, 
    0x42,       (char)0x9f, 0x00, 0x05,       
    0x7d,       0x68,       0x02, (char)0xa6, 
    0x7d,       (char)0x88, 0x03, (char)0xa6, 
    0x3d,       (char)0x8b, 0x00, 0x00,       
    (char)0xe9, (char)0x8c, 0x00, 0x00,       
    0x7d,       (char)0x89, 0x03, (char)0xa6, 
    0x4e,       (char)0x80, 0x04, 0x20,       
}
</div>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>Referenced by <a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a>.</p>

</div>
</div>

### PointerJumpStubNoTOCContent\_little {#a935c849316d2a5f519f6a895003682d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::ppc64::PointerJumpStubNoTOCContent_little</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    (char)0xa6, 0x02,       (char)0x88, 0x7d,       
    0x05,       (char)0x00, (char)0x9f, 0x42,       
    (char)0xa6, 0x02,       0x68,       0x7d,       
    (char)0xa6, 0x03,       (char)0x88, 0x7d,       
    0x00,       0x00,       (char)0x8b, 0x3d,       
    0x00,       0x00,       (char)0x8c, (char)0xe9, 
    (char)0xa6, 0x03,       (char)0x89, 0x7d,       
    0x20,       0x04,       (char)0x80, 0x4e,       
}
</div>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a>.</p>


<p>Referenced by <a href="#a33ec230e070e9dc242e28bf8fd9c28f9">pickStub</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ppc64-h">ppc64.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ppc64-cpp">ppc64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
