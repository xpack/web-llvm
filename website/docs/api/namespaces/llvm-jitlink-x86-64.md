---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/x86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `x86_64` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::x86_64 { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/gottablemanager">GOTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global Offset Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/gottablemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/plttablemanager">PLTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/plttablemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_x86_64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#aebb5822f6bda55afbca20f322d73a2a1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents x86-64 fixups and other x86-64-specific edge kinds. <a href="#aebb5822f6bda55afbca20f322d73a2a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b9b4bde645a27a83435303ac1e06e69">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given x86-64 edge. <a href="#a2b9b4bde645a27a83435303ac1e06e69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4640b55f4a0124796c017fc725e87add">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const Symbol *GOTSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a4640b55f4a0124796c017fc725e87add">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895327287e36f2118e7d50fdef340700">createAnonymousPointer</a> (LinkGraph &amp;G, Section &amp;PointerSection, Symbol *InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new pointer block in the given section and returns an anonymous symbol pointing to it. <a href="#a895327287e36f2118e7d50fdef340700">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b140dca7fc910c208b9bc103461f24e">createPointerJumpStubBlock</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub block that jumps via the pointer at the given symbol. <a href="#a8b140dca7fc910c208b9bc103461f24e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef00497bf1e3eecf0e6565364ad15c24">createAnonymousPointerJumpStub</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it. <a href="#aef00497bf1e3eecf0e6565364ad15c24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ac1d2bccf8bda89eb237edc25a74c0">createReentryTrampolineBlock</a> (LinkGraph &amp;G, Section &amp;TrampolineSection, Symbol &amp;ReentrySymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a block of N reentry trampolines. <a href="#a37ac1d2bccf8bda89eb237edc25a74c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53467f0fe1d815298a88cb6c0d7b8420">createAnonymousReentryTrampoline</a> (LinkGraph &amp;G, Section &amp;TrampolineSection, Symbol &amp;ReentrySymbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61404d428edea90fb2c5b180daf5361">optimizeGOTAndStubAccesses</a> (LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize the GOT and Stub relocations if the edge target address is in range. <a href="#ac61404d428edea90fb2c5b180daf5361">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a3b0ce55e5217546f5140e284e5ae3">PointerSize</a> = 8</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64">x86_64</a> pointer size. <a href="#a73a3b0ce55e5217546f5140e284e5ae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49410e3ce0c5b98847f643624370778">NullPointerContent</a>[PointerSize] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>x86-64 null pointer content. <a href="#aa49410e3ce0c5b98847f643624370778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd96e0def723945c3f358d87e5d7a054">PointerJumpStubContent</a>[6] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>x86-64 pointer jump stub content. <a href="#acd96e0def723945c3f358d87e5d7a054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb329db9130636bd0da16c88649d3268">ReentryTrampolineContent</a>[5] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>x86-64 reentry trampoline. <a href="#acb329db9130636bd0da16c88649d3268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### EdgeKind\_x86\_64 {#aebb5822f6bda55afbca20f322d73a2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::x86_64::EdgeKind_x86_64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents x86-64 fixups and other x86-64-specific edge kinds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer64<a id="aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4"></a></td>
<td class="doxyEnumItemDescription">A plain 64-bit pointer value relocation (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32<a id="aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3"></a></td>
<td class="doxyEnumItemDescription">A plain 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32Signed<a id="aebb5822f6bda55afbca20f322d73a2a1a34c4628fc868b9a8285b84ac203ff65f"></a></td>
<td class="doxyEnumItemDescription">A signed 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16<a id="aebb5822f6bda55afbca20f322d73a2a1a9373b13e8458a9e8381f56fc053a90fb"></a></td>
<td class="doxyEnumItemDescription">A plain 16-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer8<a id="aebb5822f6bda55afbca20f322d73a2a1a21a771aa9e28a965fcfc0f7116afdb52"></a></td>
<td class="doxyEnumItemDescription">A plain 8-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta64<a id="aebb5822f6bda55afbca20f322d73a2a1a0813e2e217bec0a3795f7e0bf463bbdc"></a></td>
<td class="doxyEnumItemDescription">A 64-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32<a id="aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c"></a></td>
<td class="doxyEnumItemDescription">A 32-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta16<a id="aebb5822f6bda55afbca20f322d73a2a1a07c726345490ba4b773b1a3f4d82d58f"></a></td>
<td class="doxyEnumItemDescription">A 16-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta8<a id="aebb5822f6bda55afbca20f322d73a2a1af668cb8ac335e5d9af3fc8e311b6e0aa"></a></td>
<td class="doxyEnumItemDescription">An 8-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta64<a id="aebb5822f6bda55afbca20f322d73a2a1a839d55b90b99a051adaac5b1acff9916"></a></td>
<td class="doxyEnumItemDescription">A 64-bit negative delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta32<a id="aebb5822f6bda55afbca20f322d73a2a1abd3d0bdbcb54e70a617ffa080e3befee"></a></td>
<td class="doxyEnumItemDescription">A 32-bit negative delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Size64<a id="aebb5822f6bda55afbca20f322d73a2a1a8234b7c99627f2565403c5ae878c2fca"></a></td>
<td class="doxyEnumItemDescription">A 64-bit size relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Size32<a id="aebb5822f6bda55afbca20f322d73a2a1aaa0c7a1bad5278edf861978dd8ee784b"></a></td>
<td class="doxyEnumItemDescription">A 32-bit size relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta64FromGOT<a id="aebb5822f6bda55afbca20f322d73a2a1a01de57a850e4e1dcca112b0916082457"></a></td>
<td class="doxyEnumItemDescription">A 64-bit GOT delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32<a id="aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel32<a id="aebb5822f6bda55afbca20f322d73a2a1a7cb0483abb6a27356f946cb706c696a9"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32ToPtrJumpStub<a id="aebb5822f6bda55afbca20f322d73a2a1ab397b16e783227e075cdb27c9afbcdc4"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative branch to a pointer jump stub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32ToPtrJumpStubBypassable<a id="aebb5822f6bda55afbca20f322d73a2a1abbcdf6b67a662a9bd7b37181b24a3c6f"></a></td>
<td class="doxyEnumItemDescription">A relaxable version of BranchPCRel32ToPtrJumpStub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta32<a id="aebb5822f6bda55afbca20f322d73a2a1a1b3a2e2ef0509b193690450206228b2b"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Delta32 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta64<a id="aebb5822f6bda55afbca20f322d73a2a1a60f7bd35a2ff8c19770fee91581e3929"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Delta64 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta64FromGOT<a id="aebb5822f6bda55afbca20f322d73a2a1a75c226be11a3474c2fec6ed507d60a12"></a></td>
<td class="doxyEnumItemDescription">A GOT entry offset within GOT getter/constructor, transformed to Delta64FromGOT pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel32GOTLoadRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1a2669dc43fc00ceeba47db937ae286b4b"></a></td>
<td class="doxyEnumItemDescription">A PC-relative load of a GOT entry, relaxable if GOT entry target is in-range of the fixup</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel32GOTLoadREXRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1a81bb18739548bc2a716e15d451114be1"></a></td>
<td class="doxyEnumItemDescription">A PC-relative REX load of a GOT entry, relaxable if GOT entry target is in-range of the fixup</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPCRel32GOTLoadREXRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1ab5f29838f6d74e9a4bb9453ac240204d"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to PCRel32ToGOTLoadREXRelaxable pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPCRel32GOTLoadRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1aa6cfcfc8b35fd783c173adbaf7cb0dd6"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to PCRel32ToGOTLoadRelaxable pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel32TLVPLoadREXRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1a78ad01c24da93121cfe0a5249a1ece6d"></a></td>
<td class="doxyEnumItemDescription">A PC-relative REX load of a Thread Local Variable Pointer (TLVP) entry, relaxable if the TLVP entry target is in-range of the fixup</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescInGOTAndTransformToDelta32<a id="aebb5822f6bda55afbca20f322d73a2a1a11eeb5ae49b11ea2ebf2a6ac6c4c7bd8"></a></td>
<td class="doxyEnumItemDescription">TODO: Explain the generic edge kind</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLVPAndTransformToPCRel32TLVPLoadREXRelaxable<a id="aebb5822f6bda55afbca20f322d73a2a1a746f39ee3f37365c07571ccce236198d"></a></td>
<td class="doxyEnumItemDescription">A TLVP entry getter/constructor, transformed to Delta32ToTLVPLoadREXRelaxable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstPlatformRelocation<a id="aebb5822f6bda55afbca20f322d73a2a1add715d49e2474eaf459ccdfa6cc7e9f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### applyFixup() {#a4640b55f4a0124796c017fc725e87add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::x86_64::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * GOTSymbol)</td>
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

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4">BranchPCRel32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ab397b16e783227e075cdb27c9afbcdc4">BranchPCRel32ToPtrJumpStub</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1abbcdf6b67a662a9bd7b37181b24a3c6f">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a07c726345490ba4b773b1a3f4d82d58f">Delta16</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c">Delta32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a0813e2e217bec0a3795f7e0bf463bbdc">Delta64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a01de57a850e4e1dcca112b0916082457">Delta64FromGOT</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1af668cb8ac335e5d9af3fc8e311b6e0aa">Delta8</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="#a2b9b4bde645a27a83435303ac1e06e69">getEdgeKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1abd3d0bdbcb54e70a617ffa080e3befee">NegDelta32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a839d55b90b99a051adaac5b1acff9916">NegDelta64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a7cb0483abb6a27356f946cb706c696a9">PCRel32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a2669dc43fc00ceeba47db937ae286b4b">PCRel32GOTLoadRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a81bb18739548bc2a716e15d451114be1">PCRel32GOTLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a78ad01c24da93121cfe0a5249a1ece6d">PCRel32TLVPLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a9373b13e8458a9e8381f56fc053a90fb">Pointer16</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3">Pointer32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34c4628fc868b9a8285b84ac203ff65f">Pointer32Signed</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">Pointer64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a21a771aa9e28a965fcfc0f7116afdb52">Pointer8</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1aaa0c7a1bad5278edf861978dd8ee784b">Size32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a8234b7c99627f2565403c5ae878c2fca">Size64</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createAnonymousPointer() {#a895327287e36f2118e7d50fdef340700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::x86_64::createAnonymousPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; PointerSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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

<p>Creates a new pointer block in the given section and returns an anonymous symbol pointing to it.</p>


<p>If InitialTarget is given then an Pointer64 relocation will be added to the block pointing at InitialTarget.</p>


<p>The pointer block will have the following default values: alignment: 64-bit alignment-offset: 0 address: highest allowable (~7U)</p>


<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aa49410e3ce0c5b98847f643624370778">NullPointerContent</a> and <a href="#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">Pointer64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/gottablemanager/#a6fcfa4e41f60a2eff5ae2d8e6f6f1882">llvm::jitlink::x86_64::GOTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af86dbecbbb47825e36f9af37bd6868ca">llvm::jitlink::getAnonymousPointerCreator</a>.</p>

</div>
</div>

### createAnonymousPointerJumpStub() {#aef00497bf1e3eecf0e6565364ad15c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::x86_64::createAnonymousPointerJumpStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it.</p>


<p>Return the anonymous symbol.</p>


<p>The stub block will be created by createPointerJumpStubBlock.</p>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="#a8b140dca7fc910c208b9bc103461f24e">createPointerJumpStubBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/x86-64/plttablemanager/#a7d421a5c7f5d50c66e9d27e3b83b7031">llvm::jitlink::x86_64::PLTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6e58d27e8cd9ba5dadc9194100b69be4">llvm::jitlink::getPointerJumpStubCreator</a>.</p>

</div>
</div>

### createAnonymousReentryTrampoline() {#a53467f0fe1d815298a88cb6c0d7b8420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::x86_64::createAnonymousReentryTrampoline (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; TrampolineSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; ReentrySymbol)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="#a37ac1d2bccf8bda89eb237edc25a74c0">createReentryTrampolineBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#acb329db9130636bd0da16c88649d3268">ReentryTrampolineContent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/#a65b27dfd43dad3af09bd244752f7eadf">llvm::orc::JITLinkReentryTrampolines::Create</a>.</p>

</div>
</div>

### createPointerJumpStubBlock() {#a8b140dca7fc910c208b9bc103461f24e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::x86_64::createPointerJumpStubBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub block that jumps via the pointer at the given symbol.</p>


<p>The stub block will have the following default values: alignment: 8-bit alignment-offset: 0 address: highest allowable: (~5U)</p>


<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4">BranchPCRel32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#acd96e0def723945c3f358d87e5d7a054">PointerJumpStubContent</a>.</p>


<p>Referenced by <a href="#aef00497bf1e3eecf0e6565364ad15c24">createAnonymousPointerJumpStub</a>.</p>

</div>
</div>

### createReentryTrampolineBlock() {#a37ac1d2bccf8bda89eb237edc25a74c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::x86_64::createReentryTrampolineBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; TrampolineSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; ReentrySymbol)</td>
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

<p>Create a block of N reentry trampolines.</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4">BranchPCRel32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#acb329db9130636bd0da16c88649d3268">ReentryTrampolineContent</a>.</p>


<p>Referenced by <a href="#a53467f0fe1d815298a88cb6c0d7b8420">createAnonymousReentryTrampoline</a>.</p>

</div>
</div>

### getEdgeKindName() {#a2b9b4bde645a27a83435303ac1e06e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::x86_64::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given x86-64 edge.</p>


<p>For debugging purposes only.</p>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a>.</p>


<p>References <a href="#aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4">BranchPCRel32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ab397b16e783227e075cdb27c9afbcdc4">BranchPCRel32ToPtrJumpStub</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1abbcdf6b67a662a9bd7b37181b24a3c6f">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a07c726345490ba4b773b1a3f4d82d58f">Delta16</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c">Delta32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a0813e2e217bec0a3795f7e0bf463bbdc">Delta64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a01de57a850e4e1dcca112b0916082457">Delta64FromGOT</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1af668cb8ac335e5d9af3fc8e311b6e0aa">Delta8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1abd3d0bdbcb54e70a617ffa080e3befee">NegDelta32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a839d55b90b99a051adaac5b1acff9916">NegDelta64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a7cb0483abb6a27356f946cb706c696a9">PCRel32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a2669dc43fc00ceeba47db937ae286b4b">PCRel32GOTLoadRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a81bb18739548bc2a716e15d451114be1">PCRel32GOTLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a78ad01c24da93121cfe0a5249a1ece6d">PCRel32TLVPLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a9373b13e8458a9e8381f56fc053a90fb">Pointer16</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3">Pointer32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34c4628fc868b9a8285b84ac203ff65f">Pointer32Signed</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">Pointer64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a21a771aa9e28a965fcfc0f7116afdb52">Pointer8</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a1b3a2e2ef0509b193690450206228b2b">RequestGOTAndTransformToDelta32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a60f7bd35a2ff8c19770fee91581e3929">RequestGOTAndTransformToDelta64</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a75c226be11a3474c2fec6ed507d60a12">RequestGOTAndTransformToDelta64FromGOT</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1aa6cfcfc8b35fd783c173adbaf7cb0dd6">RequestGOTAndTransformToPCRel32GOTLoadRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ab5f29838f6d74e9a4bb9453ac240204d">RequestGOTAndTransformToPCRel32GOTLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a746f39ee3f37365c07571ccce236198d">RequestTLVPAndTransformToPCRel32TLVPLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1aaa0c7a1bad5278edf861978dd8ee784b">Size32</a> and <a href="#aebb5822f6bda55afbca20f322d73a2a1a8234b7c99627f2565403c5ae878c2fca">Size64</a>.</p>


<p>Referenced by <a href="#a4640b55f4a0124796c017fc725e87add">applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aea6b603e2ebc1d8020432d707a3075df">llvm::jitlink::getCOFFX86RelocationKindName</a> and <a href="#ac61404d428edea90fb2c5b180daf5361">optimizeGOTAndStubAccesses</a>.</p>

</div>
</div>

### optimizeGOTAndStubAccesses() {#ac61404d428edea90fb2c5b180daf5361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::x86_64::optimizeGOTAndStubAccesses (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize the GOT and Stub relocations if the edge target address is in range.</p>


<ol class="doxyList" type="1">
<li>PCRel32GOTLoadRelaxable. For this edge kind, if the target is in range, then replace GOT load with lea</li>
<li>BranchPCRel32ToPtrJumpStubRelaxable. For this edge kind, if the target is in range, replace a indirect jump by plt stub with a direct jump to the target</li>
</ol>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a34ef37c952f50f08ba132f992af9bba4">BranchPCRel32</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1abbcdf6b67a662a9bd7b37181b24a3c6f">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c">Delta32</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a2b9b4bde645a27a83435303ac1e06e69">getEdgeKindName</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a2669dc43fc00ceeba47db937ae286b4b">PCRel32GOTLoadRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a81bb18739548bc2a716e15d451114be1">PCRel32GOTLoadREXRelaxable</a>, <a href="#aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3">Pointer32</a>, <a href="#acd96e0def723945c3f358d87e5d7a054">PointerJumpStubContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad21474fff99853c3d22abfe6634ee9ed">llvm::jitlink::printEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a8fe40b19af9c9f98b39e9c2f954e8d54">llvm::jitlink::link_MachO_x86_64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NullPointerContent {#aa49410e3ce0c5b98847f643624370778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::x86_64::NullPointerContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>x86-64 null pointer content.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {0x00, 0x00, 0x00, 0x00,
                                              0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a>.</p>


<p>Referenced by <a href="#a895327287e36f2118e7d50fdef340700">createAnonymousPointer</a>.</p>

</div>
</div>

### PointerJumpStubContent {#acd96e0def723945c3f358d87e5d7a054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::x86_64::PointerJumpStubContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>x86-64 pointer jump stub content.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    static_cast&lt;char&gt;(0xFFu), 0x25, 0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>


<p>Contains the instruction sequence for an indirect jump via an in-memory pointer: jmpq *ptr(rip)</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a>.</p>


<p>Referenced by <a href="#a8b140dca7fc910c208b9bc103461f24e">createPointerJumpStubBlock</a> and <a href="#ac61404d428edea90fb2c5b180daf5361">optimizeGOTAndStubAccesses</a>.</p>

</div>
</div>

### PointerSize {#a73a3b0ce55e5217546f5140e284e5ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::x86_64::PointerSize = 8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64">x86_64</a> pointer size.</p>

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/machojitlinker-x86-64/#a101116d137e537d1396ce74e4cb3ca6d">llvm::jitlink::MachOJITLinker_x86_64::JITLinker&lt; MachOJITLinker_x86_64 &gt;</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a>.</p>

</div>
</div>

### ReentryTrampolineContent {#acb329db9130636bd0da16c88649d3268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::x86_64::ReentryTrampolineContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>x86-64 reentry trampoline.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  static_cast&lt;char&gt;(0xe8), 0x00, 0x00, 0x00, 0x00
}
</div>
</dd>
</dl>


<p>Contains the instruction sequence for a trampoline that stores its return address on the stack and calls &lt;reentry-symbol&gt;: call &lt;reentry-symbol&gt;</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a>.</p>


<p>Referenced by <a href="#a53467f0fe1d815298a88cb6c0d7b8420">createAnonymousReentryTrampoline</a> and <a href="#a37ac1d2bccf8bda89eb237edc25a74c0">createReentryTrampolineBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/x86-64-h">x86_64.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/x86-64-cpp">x86_64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
