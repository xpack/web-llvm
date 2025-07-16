---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/loongarch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `loongarch` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::loongarch { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/gottablemanager">GOTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global Offset Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/gottablemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/plttablemanager">PLTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/plttablemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_loongarch : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#a7be3e7f350a78822211e1c660f34cc3e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents loongarch fixups. <a href="#a7be3e7f350a78822211e1c660f34cc3e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b78020f456adebdae460db52b04ba19">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given loongarch edge. <a href="#a6b78020f456adebdae460db52b04ba19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2377350044033afbfaab40043241f5">extractBits</a> (uint64_t Val, unsigned Hi, unsigned Lo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4c142fe5b9d4d263bef7ff0132a9a3">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a9b4c142fe5b9d4d263bef7ff0132a9a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa00f1cd81c9070c8e07704b9517f1a">getGOTEntryBlockContent</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619bf7835d7e30b4a042ba908ec54ac8">getStubBlockContent</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d15b3ca5a91487c95a159ec6c073596">createAnonymousPointer</a> (LinkGraph &amp;G, Section &amp;PointerSection, Symbol *InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new pointer block in the given section and returns an Anonymous symbol pointing to it. <a href="#a5d15b3ca5a91487c95a159ec6c073596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d9dddb99936e8e5519565b13682c65">createAnonymousPointerJumpStub</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it. <a href="#a49d9dddb99936e8e5519565b13682c65">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5994a8d8b8826bcbb59e99daad1263d">NullPointerContent</a>[8] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>loongarch null pointer content. <a href="#ae5994a8d8b8826bcbb59e99daad1263d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44761ad25d9f144156e678766b76d97">StubEntrySize</a> = 12</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>loongarch stub content. <a href="#af44761ad25d9f144156e678766b76d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86f8611c565291ecfc0d4491754b545">LA64StubContent</a>[StubEntrySize] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa260f5987545ddc03b6df8a513eb31e">LA32StubContent</a>[StubEntrySize] = ...</td>
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

### EdgeKind\_loongarch {#a7be3e7f350a78822211e1c660f34cc3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::loongarch::EdgeKind_loongarch : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents loongarch fixups.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer64<a id="a7be3e7f350a78822211e1c660f34cc3eac293043e113515d2a9cf442d7863c5b1"></a></td>
<td class="doxyEnumItemDescription">A plain 64-bit pointer value relocation (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32<a id="a7be3e7f350a78822211e1c660f34cc3eae171c2b21b0ca5f7dcf146b3a6b95ab2"></a></td>
<td class="doxyEnumItemDescription">A plain 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Branch16PCRel<a id="a7be3e7f350a78822211e1c660f34cc3ea2299f65ee790933b8c952760f8fa6591"></a></td>
<td class="doxyEnumItemDescription">A 16-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Branch21PCRel<a id="a7be3e7f350a78822211e1c660f34cc3ead6dfb4beb55c87d7196a2400a8a2a209"></a></td>
<td class="doxyEnumItemDescription">A 21-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Branch26PCRel<a id="a7be3e7f350a78822211e1c660f34cc3eadfe2c7676a29cbb6e03c41eaddce4ef8"></a></td>
<td class="doxyEnumItemDescription">A 26-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32<a id="a7be3e7f350a78822211e1c660f34cc3eab33232814f77bef7bbef1fd441b3db50"></a></td>
<td class="doxyEnumItemDescription">A 32-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta32<a id="a7be3e7f350a78822211e1c660f34cc3ea494e800bfd3f016b4fb632e00af33ec0"></a></td>
<td class="doxyEnumItemDescription">A 32-bit negative delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta64<a id="a7be3e7f350a78822211e1c660f34cc3eac3219b6735584f4bb2880143dc229931"></a></td>
<td class="doxyEnumItemDescription">A 64-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Page20<a id="a7be3e7f350a78822211e1c660f34cc3eabeb2e0639549b23d391c333717a0ccb3"></a></td>
<td class="doxyEnumItemDescription">The signed 20-bit delta from the fixup page to the page containing the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PageOffset12<a id="a7be3e7f350a78822211e1c660f34cc3ea7b7463996953e5a2d1f066ac44e1e5bb"></a></td>
<td class="doxyEnumItemDescription">The 12-bit offset of the target within its page</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPage20<a id="a7be3e7f350a78822211e1c660f34cc3ea3c04075ad9b9a3fa97569116c1565456"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Page20 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPageOffset12<a id="a7be3e7f350a78822211e1c660f34cc3eacce37383efd1e6cd6d7a79bdbf254794"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Pageoffset12 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Call36PCRel<a id="a7be3e7f350a78822211e1c660f34cc3eace3ec2bed20a153d8f27663ec07253ee"></a></td>
<td class="doxyEnumItemDescription">A 36-bit PC-relative call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add6<a id="a7be3e7f350a78822211e1c660f34cc3ead179dd08f88f8c9f5118b8fd79905f53"></a></td>
<td class="doxyEnumItemDescription">low 6 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add8<a id="a7be3e7f350a78822211e1c660f34cc3eaab85400cdf4d7d020fd54d8b6d9deb16"></a></td>
<td class="doxyEnumItemDescription">8 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add16<a id="a7be3e7f350a78822211e1c660f34cc3ea237f99072f68ce9300775a27900fb912"></a></td>
<td class="doxyEnumItemDescription">16 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add32<a id="a7be3e7f350a78822211e1c660f34cc3eae01e9f3e9e9a041a185ef3e3e452639f"></a></td>
<td class="doxyEnumItemDescription">32 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add64<a id="a7be3e7f350a78822211e1c660f34cc3ea8d7734865c6b9f5e5a14a49d0f432729"></a></td>
<td class="doxyEnumItemDescription">64 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddUleb128<a id="a7be3e7f350a78822211e1c660f34cc3ea257be2a795c61b47f1ef0b3ef9805d94"></a></td>
<td class="doxyEnumItemDescription">ULEB128 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub6<a id="a7be3e7f350a78822211e1c660f34cc3ea9345ce3ec9784222b19ed3c5607fed4a"></a></td>
<td class="doxyEnumItemDescription">low 6 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub8<a id="a7be3e7f350a78822211e1c660f34cc3ea6759ce0bf24347b8ef5e3c2725a801f0"></a></td>
<td class="doxyEnumItemDescription">8 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub16<a id="a7be3e7f350a78822211e1c660f34cc3ea4434c538f2b784d38bc16383bd9faaf1"></a></td>
<td class="doxyEnumItemDescription">16 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub32<a id="a7be3e7f350a78822211e1c660f34cc3ea8aca5b8e5b98b82c2f8850bfe1b946b6"></a></td>
<td class="doxyEnumItemDescription">32 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub64<a id="a7be3e7f350a78822211e1c660f34cc3eaf5a5ffc36cdccc5b0828589ca61d849d"></a></td>
<td class="doxyEnumItemDescription">64 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SubUleb128<a id="a7be3e7f350a78822211e1c660f34cc3ea5b3bdfc33b2af03fee8f55945d1b4a76"></a></td>
<td class="doxyEnumItemDescription">ULEB128 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignRelaxable<a id="a7be3e7f350a78822211e1c660f34cc3eae3c5424a90db0240562d511794330dca"></a></td>
<td class="doxyEnumItemDescription">Alignment requirement used by linker relaxation</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### applyFixup() {#a9b4c142fe5b9d4d263bef7ff0132a9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::loongarch::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="#a7be3e7f350a78822211e1c660f34cc3ea237f99072f68ce9300775a27900fb912">Add16</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae01e9f3e9e9a041a185ef3e3e452639f">Add32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ead179dd08f88f8c9f5118b8fd79905f53">Add6</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea8d7734865c6b9f5e5a14a49d0f432729">Add64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eaab85400cdf4d7d020fd54d8b6d9deb16">Add8</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea257be2a795c61b47f1ef0b3ef9805d94">AddUleb128</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae3c5424a90db0240562d511794330dca">AlignRelaxable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea2299f65ee790933b8c952760f8fa6591">Branch16PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ead6dfb4beb55c87d7196a2400a8a2a209">Branch21PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eadfe2c7676a29cbb6e03c41eaddce4ef8">Branch26PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eace3ec2bed20a153d8f27663ec07253ee">Call36PCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eab33232814f77bef7bbef1fd441b3db50">Delta32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eac3219b6735584f4bb2880143dc229931">Delta64</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="#aec2377350044033afbfaab40043241f5">extractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a6b78020f456adebdae460db52b04ba19">getEdgeKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a59286966d629be2e299edc33bb04fdb8">llvm::jitlink::makeAlignmentError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea494e800bfd3f016b4fb632e00af33ec0">NegDelta32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eabeb2e0639549b23d391c333717a0ccb3">Page20</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea7b7463996953e5a2d1f066ac44e1e5bb">PageOffset12</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae171c2b21b0ca5f7dcf146b3a6b95ab2">Pointer32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eac293043e113515d2a9cf442d7863c5b1">Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea4434c538f2b784d38bc16383bd9faaf1">Sub16</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea8aca5b8e5b98b82c2f8850bfe1b946b6">Sub32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea9345ce3ec9784222b19ed3c5607fed4a">Sub6</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eaf5a5ffc36cdccc5b0828589ca61d849d">Sub64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea6759ce0bf24347b8ef5e3c2725a801f0">Sub8</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea5b3bdfc33b2af03fee8f55945d1b4a76">SubUleb128</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createAnonymousPointer() {#a5d15b3ca5a91487c95a159ec6c073596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::loongarch::createAnonymousPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; PointerSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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

<p>Creates a new pointer block in the given section and returns an Anonymous symbol pointing to it.</p>


<p>If InitialTarget is given then an Pointer64 relocation will be added to the block pointing at InitialTarget.</p>


<p>The pointer block will have the following default values: alignment: PointerSize alignment-offset: 0</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a6fa00f1cd81c9070c8e07704b9517f1a">getGOTEntryBlockContent</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae171c2b21b0ca5f7dcf146b3a6b95ab2">Pointer32</a> and <a href="#a7be3e7f350a78822211e1c660f34cc3eac293043e113515d2a9cf442d7863c5b1">Pointer64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/gottablemanager/#ab502de7fffbf2d2b2a246a557409af13">llvm::jitlink::loongarch::GOTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af86dbecbbb47825e36f9af37bd6868ca">llvm::jitlink::getAnonymousPointerCreator</a>.</p>

</div>
</div>

### createAnonymousPointerJumpStub() {#a49d9dddb99936e8e5519565b13682c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::loongarch::createAnonymousPointerJumpStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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


<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a79b0a1f4950543ff5e1ecb66962a3697">llvm::jitlink::Block::addEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a619bf7835d7e30b4a042ba908ec54ac8">getStubBlockContent</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eabeb2e0639549b23d391c333717a0ccb3">Page20</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea7b7463996953e5a2d1f066ac44e1e5bb">PageOffset12</a> and <a href="#af44761ad25d9f144156e678766b76d97">StubEntrySize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/loongarch/plttablemanager/#a6d7ba3533ce040666b1c4bd7a2682e94">llvm::jitlink::loongarch::PLTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6e58d27e8cd9ba5dadc9194100b69be4">llvm::jitlink::getPointerJumpStubCreator</a>.</p>

</div>
</div>

### extractBits() {#aec2377350044033afbfaab40043241f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::jitlink::loongarch::extractBits (uint64_t Val, unsigned Hi, unsigned Lo)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="#a9b4c142fe5b9d4d263bef7ff0132a9a3">applyFixup</a>.</p>

</div>
</div>

### getEdgeKindName() {#a6b78020f456adebdae460db52b04ba19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::loongarch::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given loongarch edge.</p>


<p>For debugging purposes only.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/loongarch-cpp">loongarch.cpp</a>.</p>


<p>References <a href="#a7be3e7f350a78822211e1c660f34cc3ea237f99072f68ce9300775a27900fb912">Add16</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae01e9f3e9e9a041a185ef3e3e452639f">Add32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ead179dd08f88f8c9f5118b8fd79905f53">Add6</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea8d7734865c6b9f5e5a14a49d0f432729">Add64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eaab85400cdf4d7d020fd54d8b6d9deb16">Add8</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea257be2a795c61b47f1ef0b3ef9805d94">AddUleb128</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae3c5424a90db0240562d511794330dca">AlignRelaxable</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea2299f65ee790933b8c952760f8fa6591">Branch16PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ead6dfb4beb55c87d7196a2400a8a2a209">Branch21PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eadfe2c7676a29cbb6e03c41eaddce4ef8">Branch26PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eace3ec2bed20a153d8f27663ec07253ee">Call36PCRel</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eab33232814f77bef7bbef1fd441b3db50">Delta32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eac3219b6735584f4bb2880143dc229931">Delta64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp/#aef9ba900d85871db5625dfd07c8a0c66">KIND_NAME_CASE</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea494e800bfd3f016b4fb632e00af33ec0">NegDelta32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eabeb2e0639549b23d391c333717a0ccb3">Page20</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea7b7463996953e5a2d1f066ac44e1e5bb">PageOffset12</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eae171c2b21b0ca5f7dcf146b3a6b95ab2">Pointer32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eac293043e113515d2a9cf442d7863c5b1">Pointer64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea3c04075ad9b9a3fa97569116c1565456">RequestGOTAndTransformToPage20</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eacce37383efd1e6cd6d7a79bdbf254794">RequestGOTAndTransformToPageOffset12</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea4434c538f2b784d38bc16383bd9faaf1">Sub16</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea8aca5b8e5b98b82c2f8850bfe1b946b6">Sub32</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea9345ce3ec9784222b19ed3c5607fed4a">Sub6</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3eaf5a5ffc36cdccc5b0828589ca61d849d">Sub64</a>, <a href="#a7be3e7f350a78822211e1c660f34cc3ea6759ce0bf24347b8ef5e3c2725a801f0">Sub8</a> and <a href="#a7be3e7f350a78822211e1c660f34cc3ea5b3bdfc33b2af03fee8f55945d1b4a76">SubUleb128</a>.</p>


<p>Referenced by <a href="#a9b4c142fe5b9d4d263bef7ff0132a9a3">applyFixup</a> and <a href="/web-llvm/docs/api/classes/anonymous-elf-loongarch-cpp-/elflinkgraphbuilder-loongarch/#a18d961ea503b8f12b610174e273068ff">anonymous{ELF_loongarch.cpp}::ELFLinkGraphBuilder_loongarch&lt; ELFT &gt;::ELFLinkGraphBuilder_loongarch</a>.</p>

</div>
</div>

### getGOTEntryBlockContent() {#a6fa00f1cd81c9070c8e07704b9517f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; llvm::jitlink::loongarch::getGOTEntryBlockContent (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#ae5994a8d8b8826bcbb59e99daad1263d">NullPointerContent</a>.</p>


<p>Referenced by <a href="#a5d15b3ca5a91487c95a159ec6c073596">createAnonymousPointer</a>.</p>

</div>
</div>

### getStubBlockContent() {#a619bf7835d7e30b4a042ba908ec54ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; llvm::jitlink::loongarch::getStubBlockContent (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aaa260f5987545ddc03b6df8a513eb31e">LA32StubContent</a>, <a href="#ac86f8611c565291ecfc0d4491754b545">LA64StubContent</a> and <a href="#af44761ad25d9f144156e678766b76d97">StubEntrySize</a>.</p>


<p>Referenced by <a href="#a49d9dddb99936e8e5519565b13682c65">createAnonymousPointerJumpStub</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### LA32StubContent {#aaa260f5987545ddc03b6df8a513eb31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::loongarch::LA32StubContent</td>
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
    0x14, 0x00, 0x00, 0x1a, 
    0x94, 0x02, 0x80, 0x28, 
    0x80, 0x02, 0x00, 0x4c  
}
</div>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/loongarch-cpp">loongarch.cpp</a>.</p>


<p>Referenced by <a href="#a619bf7835d7e30b4a042ba908ec54ac8">getStubBlockContent</a>.</p>

</div>
</div>

### LA64StubContent {#ac86f8611c565291ecfc0d4491754b545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::loongarch::LA64StubContent</td>
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
    0x14, 0x00, 0x00, 0x1a, 
    0x94, 0x02, 0xc0, 0x28, 
    0x80, 0x02, 0x00, 0x4c  
}
</div>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/loongarch-cpp">loongarch.cpp</a>.</p>


<p>Referenced by <a href="#a619bf7835d7e30b4a042ba908ec54ac8">getStubBlockContent</a>.</p>

</div>
</div>

### NullPointerContent {#ae5994a8d8b8826bcbb59e99daad1263d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::loongarch::NullPointerContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>loongarch null pointer content.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {0x00, 0x00, 0x00, 0x00,
                                    0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/loongarch-cpp">loongarch.cpp</a>.</p>


<p>Referenced by <a href="#a6fa00f1cd81c9070c8e07704b9517f1a">getGOTEntryBlockContent</a>.</p>

</div>
</div>

### StubEntrySize {#af44761ad25d9f144156e678766b76d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::jitlink::loongarch::StubEntrySize = 12</td>
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

<p>loongarch stub content.</p>


<p>Contains the instruction sequence for an indirect jump via an in-memory pointer: pcalau12i $t8, page20(ptr) ld.[w/d] $t8, pageoff12(ptr) jr $t8</p>


<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a>.</p>


<p>Referenced by <a href="#a49d9dddb99936e8e5519565b13682c65">createAnonymousPointerJumpStub</a> and <a href="#a619bf7835d7e30b4a042ba908ec54ac8">getStubBlockContent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/loongarch-h">loongarch.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/loongarch-cpp">loongarch.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
