---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolrefexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbolRefExpr` Class Reference

<p>Represent a reference to a symbol from inside an expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolRefExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for the full range of assembler expressions which are needed for parsing. <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind : uint16_t { <a href="#a5c463f6352570ee778c35c40949c4985">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462e444ca93b29d9b514d2c2ac460fde">MCSymbolRefExpr</a> (const MCSymbol *Symbol, VariantKind Kind, const MCAsmInfo *MAI, SMLoc Loc=SMLoc())</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f7e856b7404708782e32f15b522722">Symbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The symbol being referenced. <a href="#af7f7e856b7404708782e32f15b522722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5074811402edd4c3119fef6d874843">classof</a> (const MCExpr *E)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2bda90e8454f453eb06cc0c565b3d5">encodeSubclassData</a> (VariantKind Kind, bool HasSubsectionsViaSymbols)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed29ced2100e786e89f972d9b1ada3f">VariantKindBits</a> = 16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660b62989286f230198a41f06a4145dd">VariantKindMask</a> = (1 &lt;&lt; VariantKindBits) - 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b8dc4f782b704b6da68d31b9a493e6">HasSubsectionsViaSymbolsBit</a> = 1 &lt;&lt; VariantKindBits</td>
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

## Construction Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9914b597552aa4b4bcbb8acaa04d632a">create</a> (const MCSymbol *Symbol, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e4958e0559d700c71dbcf92f493e9a">create</a> (const MCSymbol *Symbol, VariantKind Kind, MCContext &amp;Ctx, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4731a5e185b996f5f9095f1fff88f67b">create</a> (StringRef Name, VariantKind Kind, MCContext &amp;Ctx)</td>
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

## Static Utility Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1431e9c9bff3315f5a9681a1cfc6d44b">getVariantKindName</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433c1cd00305214e7d1d81d682c2346a">getVariantKindForName</a> (StringRef Name)</td>
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

## Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048f077746d95f142d02e56586862bf2">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad860e326e495f296cdee70606908a6b1">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff40cdca21460452b93bdf50f1f1b74d">hasSubsectionsViaSymbols</a> () const</td>
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

<p>Represent a reference to a symbol from inside an expression.</p>


<p>A symbol reference in an expression may be a use of a label, a use of an assembler variable (defined constant), or constitute an implicit definition of the symbol as external.</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#a5c463f6352570ee778c35c40949c4985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSymbolRefExpr::VariantKind : uint16_t</td>
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
<td class="doxyEnumItemName">VK_None<a id="a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Invalid<a id="a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT<a id="a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTENT<a id="a5c463f6352570ee778c35c40949c4985a53c94a5a94c907ea9d14b4d4317487dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTOFF<a id="a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTREL<a id="a5c463f6352570ee778c35c40949c4985a52a066155dc6bd5c75e077d7fd2d619c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PCREL<a id="a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTPCREL<a id="a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTPCREL_NORELAX<a id="a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPOFF<a id="a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_INDNTPOFF<a id="a5c463f6352570ee778c35c40949c4985a542605f9315d7c837ffdf0db3d36ab00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_NTPOFF<a id="a5c463f6352570ee778c35c40949c4985ad51962e40d9ba19993f108197dd65f57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTNTPOFF<a id="a5c463f6352570ee778c35c40949c4985a39bde642c4c205e820490b44c7c99eaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PLT<a id="a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSGD<a id="a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSLD<a id="a5c463f6352570ee778c35c40949c4985a2bd18a4543b4686a238d7c84cf299257"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSLDM<a id="a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPOFF<a id="a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPOFF<a id="a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSCALL<a id="a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC<a id="a5c463f6352570ee778c35c40949c4985a0dfb6ffd20ec6e759a99ca36206fc27b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLVP<a id="a5c463f6352570ee778c35c40949c4985a5d7dc0ab54306dc5d9af486598f7d26d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLVPPAGE<a id="a5c463f6352570ee778c35c40949c4985a1b4b41a073cebf886ecd3828f0aaba89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLVPPAGEOFF<a id="a5c463f6352570ee778c35c40949c4985af0a99c543167803572c2fb1642f17010"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PAGE<a id="a5c463f6352570ee778c35c40949c4985a31cf99534bfdc7784bbaf684f89d3579"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PAGEOFF<a id="a5c463f6352570ee778c35c40949c4985aa68dd5cbd2bf672acbe601e89ccf676a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTPAGE<a id="a5c463f6352570ee778c35c40949c4985a463ee5a9ee2106acf1e4533e5d6a6eb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTPAGEOFF<a id="a5c463f6352570ee778c35c40949c4985afc40a65d8cb0da3855201ee24f549aa6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SECREL<a id="a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SIZE<a id="a5c463f6352570ee778c35c40949c4985ae82d65eb3584ba7c4f28110e5f033763"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WEAKREF<a id="a5c463f6352570ee778c35c40949c4985a4acec19f33bc45f90643617e00ce9a81"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_FUNCDESC<a id="a5c463f6352570ee778c35c40949c4985addb2ba73b9549a6c4c8ae26080ce4913"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTFUNCDESC<a id="a5c463f6352570ee778c35c40949c4985aae0bda78ff92ed142825a6cbfe0e2e23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTOFFFUNCDESC<a id="a5c463f6352570ee778c35c40949c4985a456d8d0226c9bb8047e9211574f8d91c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSGD_FDPIC<a id="a5c463f6352570ee778c35c40949c4985a2a7aabe201191ea7c45e6ad02eef5bd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSLDM_FDPIC<a id="a5c463f6352570ee778c35c40949c4985a37de9fd63a2734733444afef60f66f05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPOFF_FDPIC<a id="a5c463f6352570ee778c35c40949c4985a9bc6ac28fa9f15e6c5e08f13806b2fc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_X86_ABS8<a id="a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_X86_PLTOFF<a id="a5c463f6352570ee778c35c40949c4985aec6e66cd0fb96e202f1a13f25bf29cbf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_NONE<a id="a5c463f6352570ee778c35c40949c4985aa1fcd2b3ccf581e9749322a069bc612c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_GOT_PREL<a id="a5c463f6352570ee778c35c40949c4985a24803a39bfaa6dcba36248f08aa7e09d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_TARGET1<a id="a5c463f6352570ee778c35c40949c4985a8c438d2384c73769b778b037610f05c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_TARGET2<a id="a5c463f6352570ee778c35c40949c4985aea58f487f661d29c32f2721260bb91a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_PREL31<a id="a5c463f6352570ee778c35c40949c4985ab582b682c3a5495c335cad9a9a7efc4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_SBREL<a id="a5c463f6352570ee778c35c40949c4985a70f14faefb91e967ebfe0095578719b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_TLSLDO<a id="a5c463f6352570ee778c35c40949c4985ab14f2e9bf0754182e2f760b91cb6e625"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ARM_TLSDESCSEQ<a id="a5c463f6352570ee778c35c40949c4985ac12a4fc11e8f1ac1194704d87be03f79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_NONE<a id="a5c463f6352570ee778c35c40949c4985a20fbdefa51326892a391cc8b92cfeed3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_LO8<a id="a5c463f6352570ee778c35c40949c4985a397380ba86f34c5d45316aedb17717be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HI8<a id="a5c463f6352570ee778c35c40949c4985af05034277372574cb19c4b1a4cd9512e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HLO8<a id="a5c463f6352570ee778c35c40949c4985ae94f4874e083b555503261633fddf252"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_DIFF8<a id="a5c463f6352570ee778c35c40949c4985a23b7b8655bd878090bcde3981874b67b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_DIFF16<a id="a5c463f6352570ee778c35c40949c4985a23ddbd81fa939ae7beb63b41adf49840"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_DIFF32<a id="a5c463f6352570ee778c35c40949c4985a7d4ea2582d7854b749f600956cab2270"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_PM<a id="a5c463f6352570ee778c35c40949c4985af427aa83e01ff2afe3a8640aaa86c0a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_LO<a id="a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HI<a id="a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HA<a id="a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGH<a id="a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGHA<a id="a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGHER<a id="a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGHERA<a id="a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGHEST<a id="a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_HIGHESTA<a id="a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_LO<a id="a5c463f6352570ee778c35c40949c4985ad179e874cf4e309b0e9b955967f12371"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_HI<a id="a5c463f6352570ee778c35c40949c4985a0adbb1cf9b46d88694e78fad77ebc014"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_HA<a id="a5c463f6352570ee778c35c40949c4985a23004891138ddce80497bebc9e47c3cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TOCBASE<a id="a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TOC<a id="a5c463f6352570ee778c35c40949c4985aa4b8b58379694eb9c24793904e2b2089"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TOC_LO<a id="a5c463f6352570ee778c35c40949c4985a9ea61bcfe12d2dbd766d06581e5abe79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TOC_HI<a id="a5c463f6352570ee778c35c40949c4985ac336aade6add02fc835b447c21d12074"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TOC_HA<a id="a5c463f6352570ee778c35c40949c4985a86b94af00057681fc558d5ade49f77f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_U<a id="a5c463f6352570ee778c35c40949c4985a357bed48651388b3b7882ed32f085ec1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_L<a id="a5c463f6352570ee778c35c40949c4985a2e024b4ca6a06e62e43f54816758e59e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPMOD<a id="a5c463f6352570ee778c35c40949c4985a0301409c32f14b13a93451a72bfd54a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_LO<a id="a5c463f6352570ee778c35c40949c4985a3ae3c5740fe01f98a256caeb5a1ae6f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HI<a id="a5c463f6352570ee778c35c40949c4985a61a15f02c13a7251c97f9387c3f99ecb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HA<a id="a5c463f6352570ee778c35c40949c4985aa022f5ada06b78d01fc4227b09a8722a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGH<a id="a5c463f6352570ee778c35c40949c4985ad1e8fbb210d1190a9c71fc0b5c2a74bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGHA<a id="a5c463f6352570ee778c35c40949c4985a688a086d89be625bf3c11bab1e3ee549"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGHER<a id="a5c463f6352570ee778c35c40949c4985a91432c86c48a7496dd9de6088182a12a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGHERA<a id="a5c463f6352570ee778c35c40949c4985a1f9254d454e21c1ea81001a7e15a0917"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGHEST<a id="a5c463f6352570ee778c35c40949c4985a00a33ecfac5457b544a31d2ce8f3695a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TPREL_HIGHESTA<a id="a5c463f6352570ee778c35c40949c4985aa810324618394114d0088f1c6ce3f7e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_LO<a id="a5c463f6352570ee778c35c40949c4985ab8a6b1fa79f3b913402f58157014df7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HI<a id="a5c463f6352570ee778c35c40949c4985a6f871b8b19a508be82e3cf5fbdd1b788"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HA<a id="a5c463f6352570ee778c35c40949c4985a557068c0a5af8551cfeeebacb4e7b50d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGH<a id="a5c463f6352570ee778c35c40949c4985aaf636548d803f10f5f0e3607b55100ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGHA<a id="a5c463f6352570ee778c35c40949c4985a84017b8a3e33572c050157bbb4e364c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGHER<a id="a5c463f6352570ee778c35c40949c4985a00e36b4242d01a8186f89616c1d94033"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGHERA<a id="a5c463f6352570ee778c35c40949c4985a1142b930700bea9eb3c3208832552b1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGHEST<a id="a5c463f6352570ee778c35c40949c4985a843397ce73b687621bbe91e65e703558"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_DTPREL_HIGHESTA<a id="a5c463f6352570ee778c35c40949c4985a3aab9adfef3700bea810d54e20919b3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TPREL<a id="a5c463f6352570ee778c35c40949c4985a4cd5875553111c54d66aa7254d99af01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TPREL_LO<a id="a5c463f6352570ee778c35c40949c4985aed3c47b613307c1c3bb2e123285a324c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TPREL_HI<a id="a5c463f6352570ee778c35c40949c4985a00476eb3086a83e9f8694d17e659e246"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TPREL_HA<a id="a5c463f6352570ee778c35c40949c4985a10816ac7561fb1d788b69d59c4153236"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_DTPREL<a id="a5c463f6352570ee778c35c40949c4985acf90c1ae6ce721405baf8d6575dbbcae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_DTPREL_LO<a id="a5c463f6352570ee778c35c40949c4985aa2adbff823003ac824d4158a6c3d5a9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_DTPREL_HI<a id="a5c463f6352570ee778c35c40949c4985a5eb3d787ca102ee3f6becd6ce18f7351"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_DTPREL_HA<a id="a5c463f6352570ee778c35c40949c4985a154ca3222e772e0ea2d21a43d589a37a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TLS<a id="a5c463f6352570ee778c35c40949c4985a1ebb65d3581b26c6d9be3d4ff95d8648"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSGD<a id="a5c463f6352570ee778c35c40949c4985ab73442f1c191fde93198b4568cda1dfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSGD_LO<a id="a5c463f6352570ee778c35c40949c4985a7fe6746f350536c8fe0392b0a6670769"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSGD_HI<a id="a5c463f6352570ee778c35c40949c4985a1328ba71b9f7ab63659fb21462a434e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSGD_HA<a id="a5c463f6352570ee778c35c40949c4985a8df42e2c96f1fc53644f6a6c8353f57c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TLSGD<a id="a5c463f6352570ee778c35c40949c4985a614a4f4a72a1a5fbf6b309990dbf9643"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSGD<a id="a5c463f6352570ee778c35c40949c4985a45ef9ce5642cace4f318f108b42e11e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSGDM<a id="a5c463f6352570ee778c35c40949c4985a5f3745b2d55b8cb0de42cb6c62fe0ca9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSIE<a id="a5c463f6352570ee778c35c40949c4985a6c66e7ad14399948694612a5891021c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSLE<a id="a5c463f6352570ee778c35c40949c4985afd7d09055e7b976b23804658655b5184"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSLD<a id="a5c463f6352570ee778c35c40949c4985af0042f0eb9fb8dba8f49e4bedf5e9e10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_AIX_TLSML<a id="a5c463f6352570ee778c35c40949c4985a02e865dbaa6698cd599a034b55630829"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSLD<a id="a5c463f6352570ee778c35c40949c4985ad2369968761f661db6468af845d997f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSLD_LO<a id="a5c463f6352570ee778c35c40949c4985a9e1d9b07e91fad292c9fd673ca12e142"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSLD_HI<a id="a5c463f6352570ee778c35c40949c4985a89ef4dfce0cdcaae2d7a1c2e786d0775"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSLD_HA<a id="a5c463f6352570ee778c35c40949c4985a11579e28bc40de8894dd92e9dabb677e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_PCREL<a id="a5c463f6352570ee778c35c40949c4985a11109fa28d94481aac762781d22c216e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSGD_PCREL<a id="a5c463f6352570ee778c35c40949c4985a29655f0864a4c6d617e844c2b37d6abd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TLSLD_PCREL<a id="a5c463f6352570ee778c35c40949c4985a511a0cde1ea148087a9bc31b4bd730c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_GOT_TPREL_PCREL<a id="a5c463f6352570ee778c35c40949c4985a47f886b8180bd36339b34b696e4aceed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TLS_PCREL<a id="a5c463f6352570ee778c35c40949c4985a3af1b5ef4b41faa6d2e73935860fa3c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_TLSLD<a id="a5c463f6352570ee778c35c40949c4985a55f8ba42b33462144024cc7a07194631"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_LOCAL<a id="a5c463f6352570ee778c35c40949c4985a14ae083881358216647922cedc7ae4ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_NOTOC<a id="a5c463f6352570ee778c35c40949c4985afaacbcfe095c753443e87af4aad33014"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PPC_PCREL_OPT<a id="a5c463f6352570ee778c35c40949c4985a0e7a0e61e9e2418f5a362d17b4c1c6c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_COFF_IMGREL32<a id="a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_LO16<a id="a5c463f6352570ee778c35c40949c4985a4e7973f3204bb0bc6c0d6d37341af6e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_HI16<a id="a5c463f6352570ee778c35c40949c4985a0b9581b7a8c98210fca1a88eb050c7e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_GPREL<a id="a5c463f6352570ee778c35c40949c4985a5bb196f8bf15a224cdb60b96cbec0d2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_GD_GOT<a id="a5c463f6352570ee778c35c40949c4985a7de84847ab4ad2a218fefb78e952e6ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_LD_GOT<a id="a5c463f6352570ee778c35c40949c4985ae2423d201933ce84129fd857e083d3d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_GD_PLT<a id="a5c463f6352570ee778c35c40949c4985a935589a2c56d70c003eaec114c908fae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_LD_PLT<a id="a5c463f6352570ee778c35c40949c4985a746b73972bc3af36acc05a2ce90d9baa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_IE<a id="a5c463f6352570ee778c35c40949c4985a76148043f2fa1509f2b55b6472eeac7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Hexagon_IE_GOT<a id="a5c463f6352570ee778c35c40949c4985ab09b72e3f9139ae88ba205eabfb79c4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_TYPEINDEX<a id="a5c463f6352570ee778c35c40949c4985a2fa9fd79289091758e4bdfbfb8c6ff9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_TLSREL<a id="a5c463f6352570ee778c35c40949c4985ac07f166f23e0a79d7a862db2c4ba34ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_MBREL<a id="a5c463f6352570ee778c35c40949c4985ae58d84420e2227703a6f439f63517690"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_TBREL<a id="a5c463f6352570ee778c35c40949c4985a014ec8c7c1ea8fa9780614984167ff73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_GOT_TLS<a id="a5c463f6352570ee778c35c40949c4985a5b59c0c7585f11717cc920f4823e19b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_WASM_FUNCINDEX<a id="a5c463f6352570ee778c35c40949c4985a62dd0aeb9839db4490d0e271b00123f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_GOTPCREL32_LO<a id="a5c463f6352570ee778c35c40949c4985a8b3d7769ea4864cafc0c4b473c51e8e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_GOTPCREL32_HI<a id="a5c463f6352570ee778c35c40949c4985aa2865b7a92bfdde40bd5232a89f95d07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_REL32_LO<a id="a5c463f6352570ee778c35c40949c4985a0fa9b2f75ff263e67c141233b7e6ac23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_REL32_HI<a id="a5c463f6352570ee778c35c40949c4985a5b4e0a90b28c09da92dfc8b971253a0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_REL64<a id="a5c463f6352570ee778c35c40949c4985aa26b41b8badd0d0826298773147fef4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_ABS32_LO<a id="a5c463f6352570ee778c35c40949c4985a50b2f7c7d226c8cee497e63de5f88024"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AMDGPU_ABS32_HI<a id="a5c463f6352570ee778c35c40949c4985a7aeae3effe59f76e31c990f8e19ddb59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_HI32<a id="a5c463f6352570ee778c35c40949c4985acef6f78a2cda59d8b56b70c1e4ce760e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_LO32<a id="a5c463f6352570ee778c35c40949c4985a06b57ad804a80f34c35391b7ceaf6429"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PC_HI32<a id="a5c463f6352570ee778c35c40949c4985a43e08cb3b6baebc1c7f30b7de6e912c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PC_LO32<a id="a5c463f6352570ee778c35c40949c4985a36af1e0a05061d8f9f512c694a3f0064"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOT_HI32<a id="a5c463f6352570ee778c35c40949c4985afb3d29f6eb2d6914618498cfe61ca2bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOT_LO32<a id="a5c463f6352570ee778c35c40949c4985a8884a571dcc413be5dce1128380932e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOTOFF_HI32<a id="a5c463f6352570ee778c35c40949c4985ac80540810aee853573a4ad9f6ce02c0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOTOFF_LO32<a id="a5c463f6352570ee778c35c40949c4985a68abe5c43d47c405dd5bb850a528be9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PLT_HI32<a id="a5c463f6352570ee778c35c40949c4985af258c4a492ad17e13a4b4203902e8120"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PLT_LO32<a id="a5c463f6352570ee778c35c40949c4985aa9088a6103dd17b7ebc45bca3aded045"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TLS_GD_HI32<a id="a5c463f6352570ee778c35c40949c4985a96c63d9e27f06d831286afaf0892fece"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TLS_GD_LO32<a id="a5c463f6352570ee778c35c40949c4985ab7d5356ca03b04fff69afbe6a9a4bf02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TPOFF_HI32<a id="a5c463f6352570ee778c35c40949c4985ac903f694110764a3f1130550bd500f37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TPOFF_LO32<a id="a5c463f6352570ee778c35c40949c4985ac1b8a8b6f7974cdcec793a0f13b41b14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL<a id="a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL<a id="a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MCSymbolRefExpr() {#a462e444ca93b29d9b514d2c2ac460fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolRefExpr::MCSymbolRefExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Symbol {#af7f7e856b7404708782e32f15b522722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::MCSymbolRefExpr::Symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The symbol being referenced.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0c5074811402edd4c3119fef6d874843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolRefExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### encodeSubclassData() {#a4d2bda90e8454f453eb06cc0c565b3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolRefExpr::encodeSubclassData (<a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a> Kind, bool HasSubsectionsViaSymbols)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### HasSubsectionsViaSymbolsBit {#ae9b8dc4f782b704b6da68d31b9a493e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSymbolRefExpr::HasSubsectionsViaSymbolsBit = 1 &lt;&lt; VariantKindBits</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### VariantKindBits {#a9ed29ced2100e786e89f972d9b1ada3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSymbolRefExpr::VariantKindBits = 16</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### VariantKindMask {#a660b62989286f230198a41f06a4145dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSymbolRefExpr::VariantKindMask = (1 &lt;&lt; VariantKindBits) - 1</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#a9914b597552aa4b4bcbb8acaa04d632a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * llvm::MCSymbolRefExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#a9914b597552aa4b4bcbb8acaa04d632a">create</a> and <a href="#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantpool/#a9d1e0d3d33bca317531734dc3f1ba547">llvm::ConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#a4303712ca7aca04be8e4a7d4499c65c9">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#ae8c82ca37d5404ad87bfb83a207ea712">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a2ea528bf7b0254b3ae2e1c0864022767">computeLabelDiff</a>, <a href="#a9914b597552aa4b4bcbb8acaa04d632a">create</a>, <a href="#a4731a5e185b996f5f9095f1fff88f67b">create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a1149e610692549287d358a9926ca0d44">createGOTRelExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#ad7df82b40c89fe57a01cfd473dcfcd63">createPCXRelExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a0d0d7f47cce3c25a82585c9e4f27abac">createSparcMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a587150a33a51744021fd1bc8026194d3">createVEMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a64b42038a61a3c4b1880eea5331cdb44">llvm::AMDGPUDisassembler::decodeVersionImm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/addresspool/#aca37ed4296007b66416361e122caf678">llvm::AddressPool::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8061d1e593a8f095f0efe3ba0d793531">llvm::MCStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4f385d04b05418cfd8b1337ac541256c">llvm::MCStreamer::emitAbsoluteSymbolDiffAsULEB128</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#acec704ab147b53f347bf1020f050665d">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitAIXTlsCallHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a0483bd140eacb91339ca4e622b98ae04">llvm::TargetLoweringObjectFile::emitCGProfileMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0cce678ce28a97e39af6a60a52daac7f">llvm::MCWinCOFFStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#abc85cf8fcb99aada0bb615989928b516">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineStartLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a73ba925c2a5e09782525ede9dc691059">llvm::CodeViewContext::emitFileChecksumOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aedbc3a6b1ed39b77650edac4239774cf">llvm::WebAssemblyAsmPrinter::EmitFunctionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a0e3f4587b93083fdc01e3ec8f66b3701">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af62d1039f3b3ed8fe3f8a6c05086374c">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitFunctionDescriptor</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aed12387a77f0d475d9cb9b247580257b">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac456206c08bdce2e1a11cf14b316bc9a">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a5f962a3da2e5e21ea73c8a2ba3d60cf1">llvm::AMDGPUTargetELFStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a046ce1a28d601dbc32167434da7ce4cd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::EmitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aac53de41a4af1d12db6ce7d5a0cf6678">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#afb080cf7b9699890fae560c167c09291">llvm::AMDGPUTargetELFStreamer::EmitISAVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a7b744276265a7587d11961d5cbf82dd0">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#adde89997aabb6eb4532d8882f311a631">llvm::LoongArchAsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa925bb5b36e9ac03cfbe86ebcd70dd57">llvm::ARMAsmPrinter::emitJumpTableInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a09f6957ce3faffb065b97517e5a5ff76">llvm::X86AsmPrinter::emitKCFITypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2380b3abc7ab19ec1af9883a5f7bbd67">llvm::AsmPrinter::emitLabelPlusOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a4f06b0b91350004b887ff72fe7a1ab05">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a1580a63379a12004a4da0dfd70744768">llvm::SystemZAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#ada3b3b8c611fe7959f11bf477afd0b6e">EmitNop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#a50239bad1326b962fc58f1b311e7e255">llvm::AArch64_ELFTargetObjectFile::emitPersonalityValueImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ae2871329035b9e43047202b4ee2198fd">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthCheckAuthenticatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a4562e6672b8b09e99e8bc49651b20e0c">llvm::HexagonAsmPrinter::EmitSled</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a0cd5546d88db61fc8532323c85145f6e">llvm::LoongArchAsmPrinter::emitSled</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac7b652d5871240542b523c9d9fd950b5">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7865bd61cd2c65b2d94c58dd1523bb75">llvm::MCStreamer::emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetxcoffstreamer/#afe8572c864e0d6e8ef1104a9df84673b">anonymous{PPCMCTargetDesc.cpp}::PPCTargetXCOFFStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0c5eda02c50a11f3dde025afe0675b6e">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitTlsCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa72747d7d3b33e66672520f5a3e93462">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitTTypeReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcelfstreamer/#aa77f604b9e33cc0e95652bc4da85adae">llvm::AVRMCELFStreamer::emitValueForModiferKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac11138742df2a7103190a1955e6b7331">llvm::MCELFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#ac85beb9165822c1f0510c92a3f340b35">llvm::MCWasmStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a24389fc33ea52e268a13e698afe9f718">llvm::MCWinCOFFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6fb486939378ca836b98249408abcedf">llvm::ARMAsmPrinter::emitXXStructor</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ae3f7a2c3431323c5e22c2c175ebef9cb">llvm::WasmException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#af576492babedf4292598955c5adcf76b">llvm::AVRMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a481e97810e8743a7c0f25a51dbcad8c1">llvm::ELFObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a46eb8d3c0aed8e455691e71a12c142fd">forceExpAbs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a298d9fbfabe7c231654dab9f79d09a54">llvm::ARMElfTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a4824f185b09fa4322916df3508816b22">llvm::MipsTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelftargetobjectfile/#a7aa41b5373e9b1834047d254cf00e9f0">llvm::SystemZELFTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a98b1035db70203b5f4896096926d07be">llvm::TargetLoweringObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile/#a98e6b09f214872dfea075356cab62e87">llvm::X86ELFTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e11e3c1ca2c5f957aa7a7a16ff40e24">llvm::MCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcasminfo/#aca03cf4d1b04c7a87ec24725971e2605">llvm::RISCVMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#abc43ac9f2d903054af8e134b6eb37a9f">llvm::SparcELFMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin/#a1a05057cd3005401418d6bb6f4c53659">llvm::AArch64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#af21e68297b7ed966f286d8701beed510">llvm::SparcELFMCAsmInfo::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/x86-64mcasminfodarwin/#a2718196f3a76adab2b39bcdff3f3cb44">llvm::X86_64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a504a64ccf949c7078ba92cda156a24c3">getGlobalOffsetTable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8476d36f91161750b845b56f25cb7c47">llvm::AArch64MCInstLower::GetGlobalValueSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#ab479db6c0dce9d07c70ea70016ed99ff">llvm::AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a62d13f21f5dde00137a248d95cf8acd6">llvm::ARMElfTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#affc824acbbe220a54656c5519b408c4b">llvm::RISCVELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64elftargetobjectfile/#a7fade16e9dc1ebc9b6974b12857f5abe">llvm::X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#abe4296cf38fa7bebb355865172c0acac">llvm::X86_64MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#aaf998515054f452d13147bdfa76f33f7">llvm::ARMElfTargetObjectFile::getIndirectSymViaRWPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a6908e7c05abf63c09370bbaa00de64b0">llvm::M68kTargetLowering::getPICJumpTableRelocBaseExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a9e8d81b42a228a0a2e89454cf7a3d017">llvm::PPCTargetLowering::getPICJumpTableRelocBaseExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a424abc19654b712885d63747e7f5b4db">llvm::X86TargetLowering::getPICJumpTableRelocBaseExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a4df37ccc4bac970ed9da45c24bf04a42">llvm::MCResourceInfo::getSymRefExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#ac79e8bd77d3ba389e4b449527c72046a">getTLSGetOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#abda04e72e43a3aaef8a55e4ecf91d127">llvm::AArch64_MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad44640388d6a28f1c14510e7686042fc">llvm::ARMElfTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#aa9a2f88f6a81e5a8fa1bef4833eef6ba">llvm::TargetLoweringObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#a17558be02e5c14c099a7f347669a3132">llvm::X86_64MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac1cd29692079a1f57202b9947c5f5521">llvm::TargetLoweringObjectFile::getTTypeReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#afac72182f48f1b144922b37546a66778">llvm::BPFMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#ada3cf8f523e66ab2658f5c59e0727ed8">llvm::LanaiMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a0da8c32a960fd10c2f6cb034954b3924">llvm::MSP430MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afde96322ddbdb044b3ab0525ce73e775">llvm::AsmPrinter::lowerBlockAddressConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a98344bf2ff39658d712a0715b593e294">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a4622612a8ef9449430515a6c8614a7b9">llvm::AVRAsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a63986f1038cba27a4c2ceb0fb40ea14a">llvm::M68kTargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a3857be1416dafbc76e2e00df1cb1fc74">llvm::RISCVTargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ad81befa82353e9ee9e205edffbe77d4e">llvm::VETargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af3e16079a117749c3a3ab03753982e0e">llvm::X86TargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a9c941e2d8cbdc56abb6867dade371206">llvm::TargetLoweringObjectFileELF::lowerDSOLocalEquivalent</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab55c74c151c09190ab2204e33e77b299">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHardenedBRJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a03f07768097bdb66d5e2b5bd82e629c3">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHWASAN_CHECK_MEMACCESS</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ace19a1de0790088cc712996141fac07f">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerHWASAN_CHECK_MEMACCESS</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#a984878b12749e1f06574b379915f8524">llvm::AVRMCInstLower::lowerInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a164e68b3a2bec7c004e7fe6632611400">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerJumpTableDest</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a6a5214da5fedd168431b377870b2eaea">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerKCFI_CHECK</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a4b5ab0b13d0a554ac6b9db1ef8a988bd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerKCFI_CHECK</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab1c4cab46120a38ac573508e15189f9e">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerPATCHABLE_EVENT_CALL</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a09a7c632e2befc0851032e0d8983029c">llvm::TargetLoweringObjectFileCOFF::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a745752b67a45e5dc6b1f2a6985f68937">llvm::TargetLoweringObjectFileELF::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a0d892b52d1df1d1cb59054c2dab539be">llvm::TargetLoweringObjectFileWasm::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#ad8be4aad3f7a33a52b5c40cff98b5206">llvm::BPFMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#aab3177d726a52bd1f3a26e580f6c4eda">llvm::CSKYMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ad484999912240f5615d60831473902cd">makeStartPlusIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ab7dfefac8dca2f4b81a848e540e14031">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseFunctionTableOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a2e27ea385fabb6471aea3a5e37d3dd09">llvm::FaultMaps::recordFaultingOp</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a6c8e8592c8a9a236312224fb457fc834">llvm::AMDGPUSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### create {#ac5e4958e0559d700c71dbcf92f493e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * MCSymbolRefExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

### create {#a4731a5e185b996f5f9095f1fff88f67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * MCSymbolRefExpr::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Reference <a href="#a9914b597552aa4b4bcbb8acaa04d632a">create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Static Utility Functions

### getVariantKindForName {#a433c1cd00305214e7d1d81d682c2346a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolRefExpr::VariantKind MCSymbolRefExpr::getVariantKindForName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7aeae3effe59f76e31c990f8e19ddb59">VK_AMDGPU_ABS32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a50b2f7c7d226c8cee497e63de5f88024">VK_AMDGPU_ABS32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa2865b7a92bfdde40bd5232a89f95d07">VK_AMDGPU_GOTPCREL32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8b3d7769ea4864cafc0c4b473c51e8e4">VK_AMDGPU_GOTPCREL32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5b4e0a90b28c09da92dfc8b971253a0c">VK_AMDGPU_REL32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0fa9b2f75ff263e67c141233b7e6ac23">VK_AMDGPU_REL32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa26b41b8badd0d0826298773147fef4c">VK_AMDGPU_REL64</a>, <a href="#a5c463f6352570ee778c35c40949c4985af05034277372574cb19c4b1a4cd9512e">VK_AVR_HI8</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae94f4874e083b555503261633fddf252">VK_AVR_HLO8</a>, <a href="#a5c463f6352570ee778c35c40949c4985a397380ba86f34c5d45316aedb17717be">VK_AVR_LO8</a>, <a href="#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">VK_COFF_IMGREL32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">VK_DTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74">VK_DTPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">VK_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a53c94a5a94c907ea9d14b4d4317487dd">VK_GOTENT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a39bde642c4c205e820490b44c7c99eaf">VK_GOTNTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">VK_GOTOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a463ee5a9ee2106acf1e4533e5d6a6eb0">VK_GOTPAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985afc40a65d8cb0da3855201ee24f549aa6">VK_GOTPAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">VK_GOTPCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5">VK_GOTPCREL_NORELAX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a52a066155dc6bd5c75e077d7fd2d619c">VK_GOTREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680">VK_GOTTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7de84847ab4ad2a218fefb78e952e6ab">VK_Hexagon_GD_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a935589a2c56d70c003eaec114c908fae">VK_Hexagon_GD_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a76148043f2fa1509f2b55b6472eeac7f">VK_Hexagon_IE</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab09b72e3f9139ae88ba205eabfb79c4a">VK_Hexagon_IE_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae2423d201933ce84129fd857e083d3d3">VK_Hexagon_LD_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a746b73972bc3af36acc05a2ce90d9baa">VK_Hexagon_LD_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a542605f9315d7c837ffdf0db3d36ab00">VK_INDNTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2">VK_Invalid</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad51962e40d9ba19993f108197dd65f57">VK_NTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a31cf99534bfdc7784bbaf684f89d3579">VK_PAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa68dd5cbd2bf672acbe601e89ccf676a">VK_PAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7">VK_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">VK_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0301409c32f14b13a93451a72bfd54a8">VK_PPC_DTPMOD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a557068c0a5af8551cfeeebacb4e7b50d">VK_PPC_DTPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a6f871b8b19a508be82e3cf5fbdd1b788">VK_PPC_DTPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aaf636548d803f10f5f0e3607b55100ef">VK_PPC_DTPREL_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a84017b8a3e33572c050157bbb4e364c0">VK_PPC_DTPREL_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00e36b4242d01a8186f89616c1d94033">VK_PPC_DTPREL_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1142b930700bea9eb3c3208832552b1c">VK_PPC_DTPREL_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a843397ce73b687621bbe91e65e703558">VK_PPC_DTPREL_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3aab9adfef3700bea810d54e20919b3f">VK_PPC_DTPREL_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab8a6b1fa79f3b913402f58157014df7c">VK_PPC_DTPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985acf90c1ae6ce721405baf8d6575dbbcae">VK_PPC_GOT_DTPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a154ca3222e772e0ea2d21a43d589a37a">VK_PPC_GOT_DTPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5eb3d787ca102ee3f6becd6ce18f7351">VK_PPC_GOT_DTPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa2adbff823003ac824d4158a6c3d5a9a">VK_PPC_GOT_DTPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a23004891138ddce80497bebc9e47c3cd">VK_PPC_GOT_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0adbb1cf9b46d88694e78fad77ebc014">VK_PPC_GOT_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad179e874cf4e309b0e9b955967f12371">VK_PPC_GOT_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a11109fa28d94481aac762781d22c216e">VK_PPC_GOT_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab73442f1c191fde93198b4568cda1dfc">VK_PPC_GOT_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8df42e2c96f1fc53644f6a6c8353f57c">VK_PPC_GOT_TLSGD_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1328ba71b9f7ab63659fb21462a434e7">VK_PPC_GOT_TLSGD_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7fe6746f350536c8fe0392b0a6670769">VK_PPC_GOT_TLSGD_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a29655f0864a4c6d617e844c2b37d6abd">VK_PPC_GOT_TLSGD_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad2369968761f661db6468af845d997f9">VK_PPC_GOT_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a11579e28bc40de8894dd92e9dabb677e">VK_PPC_GOT_TLSLD_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a89ef4dfce0cdcaae2d7a1c2e786d0775">VK_PPC_GOT_TLSLD_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a9e1d9b07e91fad292c9fd673ca12e142">VK_PPC_GOT_TLSLD_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a511a0cde1ea148087a9bc31b4bd730c7">VK_PPC_GOT_TLSLD_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4cd5875553111c54d66aa7254d99af01">VK_PPC_GOT_TPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a10816ac7561fb1d788b69d59c4153236">VK_PPC_GOT_TPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00476eb3086a83e9f8694d17e659e246">VK_PPC_GOT_TPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aed3c47b613307c1c3bb2e123285a324c">VK_PPC_GOT_TPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a47f886b8180bd36339b34b696e4aceed">VK_PPC_GOT_TPREL_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">VK_PPC_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd">VK_PPC_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17">VK_PPC_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61">VK_PPC_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b">VK_PPC_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472">VK_PPC_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c">VK_PPC_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1">VK_PPC_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2e024b4ca6a06e62e43f54816758e59e">VK_PPC_L</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">VK_PPC_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a14ae083881358216647922cedc7ae4ea">VK_PPC_LOCAL</a>, <a href="#a5c463f6352570ee778c35c40949c4985afaacbcfe095c753443e87af4aad33014">VK_PPC_NOTOC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1ebb65d3581b26c6d9be3d4ff95d8648">VK_PPC_TLS</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3af1b5ef4b41faa6d2e73935860fa3c0">VK_PPC_TLS_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa4b8b58379694eb9c24793904e2b2089">VK_PPC_TOC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a86b94af00057681fc558d5ade49f77f9">VK_PPC_TOC_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac336aade6add02fc835b447c21d12074">VK_PPC_TOC_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a9ea61bcfe12d2dbd766d06581e5abe79">VK_PPC_TOC_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66">VK_PPC_TOCBASE</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa022f5ada06b78d01fc4227b09a8722a">VK_PPC_TPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a61a15f02c13a7251c97f9387c3f99ecb">VK_PPC_TPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad1e8fbb210d1190a9c71fc0b5c2a74bc">VK_PPC_TPREL_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a688a086d89be625bf3c11bab1e3ee549">VK_PPC_TPREL_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a91432c86c48a7496dd9de6088182a12a">VK_PPC_TPREL_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1f9254d454e21c1ea81001a7e15a0917">VK_PPC_TPREL_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00a33ecfac5457b544a31d2ce8f3695a">VK_PPC_TPREL_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa810324618394114d0088f1c6ce3f7e9">VK_PPC_TPREL_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3ae3c5740fe01f98a256caeb5a1ae6f2">VK_PPC_TPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a357bed48651388b3b7882ed32f085ec1">VK_PPC_U</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">VK_SECREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae82d65eb3584ba7c4f28110e5f033763">VK_SIZE</a>, <a href="#a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d">VK_TLSCALL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0dfb6ffd20ec6e759a99ca36206fc27b">VK_TLSDESC</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">VK_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2bd18a4543b4686a238d7c84cf299257">VK_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048">VK_TLSLDM</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5d7dc0ab54306dc5d9af486598f7d26d">VK_TLVP</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1b4b41a073cebf886ecd3828f0aaba89">VK_TLVPPAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985af0a99c543167803572c2fb1642f17010">VK_TLVPPAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">VK_TPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a">VK_TPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985afb3d29f6eb2d6914618498cfe61ca2bb">VK_VE_GOT_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8884a571dcc413be5dce1128380932e7">VK_VE_GOT_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac80540810aee853573a4ad9f6ce02c0a">VK_VE_GOTOFF_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a68abe5c43d47c405dd5bb850a528be9c">VK_VE_GOTOFF_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985acef6f78a2cda59d8b56b70c1e4ce760e">VK_VE_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a06b57ad804a80f34c35391b7ceaf6429">VK_VE_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a43e08cb3b6baebc1c7f30b7de6e912c3">VK_VE_PC_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a36af1e0a05061d8f9f512c694a3f0064">VK_VE_PC_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985af258c4a492ad17e13a4b4203902e8120">VK_VE_PLT_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa9088a6103dd17b7ebc45bca3aded045">VK_VE_PLT_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a96c63d9e27f06d831286afaf0892fece">VK_VE_TLS_GD_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab7d5356ca03b04fff69afbe6a9a4bf02">VK_VE_TLS_GD_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac903f694110764a3f1130550bd500f37">VK_VE_TPOFF_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac1b8a8b6f7974cdcec793a0f13b41b14">VK_VE_TPOFF_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a62dd0aeb9839db4490d0e271b00123f5">VK_WASM_FUNCINDEX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5b59c0c7585f11717cc920f4823e19b0">VK_WASM_GOT_TLS</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae58d84420e2227703a6f439f63517690">VK_WASM_MBREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a014ec8c7c1ea8fa9780614984167ff73">VK_WASM_TBREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac07f166f23e0a79d7a862db2c4ba34ec">VK_WASM_TLSREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2fa9fd79289091758e4bdfbfb8c6ff9f">VK_WASM_TYPEINDEX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">VK_X86_ABS8</a> and <a href="#a5c463f6352570ee778c35c40949c4985aec6e66cd0fb96e202f1a13f25bf29cbf">VK_X86_PLTOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9c71bbbb6e41ab4d9b6a95620f4266a9">llvm::MCTargetAsmParser::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>.</p>

</div>
</div>

### getVariantKindName {#a1431e9c9bff3315f5a9681a1cfc6d44b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MCSymbolRefExpr::getVariantKindName (<a href="#a5c463f6352570ee778c35c40949c4985">VariantKind</a> Kind)</td>
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



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7aeae3effe59f76e31c990f8e19ddb59">VK_AMDGPU_ABS32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a50b2f7c7d226c8cee497e63de5f88024">VK_AMDGPU_ABS32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa2865b7a92bfdde40bd5232a89f95d07">VK_AMDGPU_GOTPCREL32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8b3d7769ea4864cafc0c4b473c51e8e4">VK_AMDGPU_GOTPCREL32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5b4e0a90b28c09da92dfc8b971253a0c">VK_AMDGPU_REL32_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0fa9b2f75ff263e67c141233b7e6ac23">VK_AMDGPU_REL32_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa26b41b8badd0d0826298773147fef4c">VK_AMDGPU_REL64</a>, <a href="#a5c463f6352570ee778c35c40949c4985a24803a39bfaa6dcba36248f08aa7e09d">VK_ARM_GOT_PREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa1fcd2b3ccf581e9749322a069bc612c">VK_ARM_NONE</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab582b682c3a5495c335cad9a9a7efc4e">VK_ARM_PREL31</a>, <a href="#a5c463f6352570ee778c35c40949c4985a70f14faefb91e967ebfe0095578719b6">VK_ARM_SBREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8c438d2384c73769b778b037610f05c2">VK_ARM_TARGET1</a>, <a href="#a5c463f6352570ee778c35c40949c4985aea58f487f661d29c32f2721260bb91a8">VK_ARM_TARGET2</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac12a4fc11e8f1ac1194704d87be03f79">VK_ARM_TLSDESCSEQ</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab14f2e9bf0754182e2f760b91cb6e625">VK_ARM_TLSLDO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a23ddbd81fa939ae7beb63b41adf49840">VK_AVR_DIFF16</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7d4ea2582d7854b749f600956cab2270">VK_AVR_DIFF32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a23b7b8655bd878090bcde3981874b67b">VK_AVR_DIFF8</a>, <a href="#a5c463f6352570ee778c35c40949c4985af05034277372574cb19c4b1a4cd9512e">VK_AVR_HI8</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae94f4874e083b555503261633fddf252">VK_AVR_HLO8</a>, <a href="#a5c463f6352570ee778c35c40949c4985a397380ba86f34c5d45316aedb17717be">VK_AVR_LO8</a>, <a href="#a5c463f6352570ee778c35c40949c4985a20fbdefa51326892a391cc8b92cfeed3">VK_AVR_NONE</a>, <a href="#a5c463f6352570ee778c35c40949c4985af427aa83e01ff2afe3a8640aaa86c0a9">VK_AVR_PM</a>, <a href="#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">VK_COFF_IMGREL32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">VK_DTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74">VK_DTPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985addb2ba73b9549a6c4c8ae26080ce4913">VK_FUNCDESC</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">VK_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a53c94a5a94c907ea9d14b4d4317487dd">VK_GOTENT</a>, <a href="#a5c463f6352570ee778c35c40949c4985aae0bda78ff92ed142825a6cbfe0e2e23">VK_GOTFUNCDESC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a39bde642c4c205e820490b44c7c99eaf">VK_GOTNTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">VK_GOTOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a456d8d0226c9bb8047e9211574f8d91c">VK_GOTOFFFUNCDESC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a463ee5a9ee2106acf1e4533e5d6a6eb0">VK_GOTPAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985afc40a65d8cb0da3855201ee24f549aa6">VK_GOTPAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">VK_GOTPCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5">VK_GOTPCREL_NORELAX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a52a066155dc6bd5c75e077d7fd2d619c">VK_GOTREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680">VK_GOTTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a9bc6ac28fa9f15e6c5e08f13806b2fc9">VK_GOTTPOFF_FDPIC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7de84847ab4ad2a218fefb78e952e6ab">VK_Hexagon_GD_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a935589a2c56d70c003eaec114c908fae">VK_Hexagon_GD_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5bb196f8bf15a224cdb60b96cbec0d2e">VK_Hexagon_GPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0b9581b7a8c98210fca1a88eb050c7e7">VK_Hexagon_HI16</a>, <a href="#a5c463f6352570ee778c35c40949c4985a76148043f2fa1509f2b55b6472eeac7f">VK_Hexagon_IE</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab09b72e3f9139ae88ba205eabfb79c4a">VK_Hexagon_IE_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae2423d201933ce84129fd857e083d3d3">VK_Hexagon_LD_GOT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a746b73972bc3af36acc05a2ce90d9baa">VK_Hexagon_LD_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4e7973f3204bb0bc6c0d6d37341af6e5">VK_Hexagon_LO16</a>, <a href="#a5c463f6352570ee778c35c40949c4985a542605f9315d7c837ffdf0db3d36ab00">VK_INDNTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2">VK_Invalid</a>, <a href="#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">VK_None</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad51962e40d9ba19993f108197dd65f57">VK_NTPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a31cf99534bfdc7784bbaf684f89d3579">VK_PAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa68dd5cbd2bf672acbe601e89ccf676a">VK_PAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7">VK_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">VK_PLT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a45ef9ce5642cace4f318f108b42e11e6">VK_PPC_AIX_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5f3745b2d55b8cb0de42cb6c62fe0ca9">VK_PPC_AIX_TLSGDM</a>, <a href="#a5c463f6352570ee778c35c40949c4985a6c66e7ad14399948694612a5891021c3">VK_PPC_AIX_TLSIE</a>, <a href="#a5c463f6352570ee778c35c40949c4985af0042f0eb9fb8dba8f49e4bedf5e9e10">VK_PPC_AIX_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985afd7d09055e7b976b23804658655b5184">VK_PPC_AIX_TLSLE</a>, <a href="#a5c463f6352570ee778c35c40949c4985a02e865dbaa6698cd599a034b55630829">VK_PPC_AIX_TLSML</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0301409c32f14b13a93451a72bfd54a8">VK_PPC_DTPMOD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a557068c0a5af8551cfeeebacb4e7b50d">VK_PPC_DTPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a6f871b8b19a508be82e3cf5fbdd1b788">VK_PPC_DTPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aaf636548d803f10f5f0e3607b55100ef">VK_PPC_DTPREL_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a84017b8a3e33572c050157bbb4e364c0">VK_PPC_DTPREL_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00e36b4242d01a8186f89616c1d94033">VK_PPC_DTPREL_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1142b930700bea9eb3c3208832552b1c">VK_PPC_DTPREL_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a843397ce73b687621bbe91e65e703558">VK_PPC_DTPREL_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3aab9adfef3700bea810d54e20919b3f">VK_PPC_DTPREL_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab8a6b1fa79f3b913402f58157014df7c">VK_PPC_DTPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985acf90c1ae6ce721405baf8d6575dbbcae">VK_PPC_GOT_DTPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a154ca3222e772e0ea2d21a43d589a37a">VK_PPC_GOT_DTPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5eb3d787ca102ee3f6becd6ce18f7351">VK_PPC_GOT_DTPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa2adbff823003ac824d4158a6c3d5a9a">VK_PPC_GOT_DTPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a23004891138ddce80497bebc9e47c3cd">VK_PPC_GOT_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0adbb1cf9b46d88694e78fad77ebc014">VK_PPC_GOT_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad179e874cf4e309b0e9b955967f12371">VK_PPC_GOT_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a11109fa28d94481aac762781d22c216e">VK_PPC_GOT_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab73442f1c191fde93198b4568cda1dfc">VK_PPC_GOT_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8df42e2c96f1fc53644f6a6c8353f57c">VK_PPC_GOT_TLSGD_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1328ba71b9f7ab63659fb21462a434e7">VK_PPC_GOT_TLSGD_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7fe6746f350536c8fe0392b0a6670769">VK_PPC_GOT_TLSGD_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a29655f0864a4c6d617e844c2b37d6abd">VK_PPC_GOT_TLSGD_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad2369968761f661db6468af845d997f9">VK_PPC_GOT_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a11579e28bc40de8894dd92e9dabb677e">VK_PPC_GOT_TLSLD_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a89ef4dfce0cdcaae2d7a1c2e786d0775">VK_PPC_GOT_TLSLD_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a9e1d9b07e91fad292c9fd673ca12e142">VK_PPC_GOT_TLSLD_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a511a0cde1ea148087a9bc31b4bd730c7">VK_PPC_GOT_TLSLD_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4cd5875553111c54d66aa7254d99af01">VK_PPC_GOT_TPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a10816ac7561fb1d788b69d59c4153236">VK_PPC_GOT_TPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00476eb3086a83e9f8694d17e659e246">VK_PPC_GOT_TPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985aed3c47b613307c1c3bb2e123285a324c">VK_PPC_GOT_TPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a47f886b8180bd36339b34b696e4aceed">VK_PPC_GOT_TPREL_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">VK_PPC_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd">VK_PPC_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17">VK_PPC_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61">VK_PPC_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b">VK_PPC_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472">VK_PPC_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c">VK_PPC_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1">VK_PPC_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2e024b4ca6a06e62e43f54816758e59e">VK_PPC_L</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">VK_PPC_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a14ae083881358216647922cedc7ae4ea">VK_PPC_LOCAL</a>, <a href="#a5c463f6352570ee778c35c40949c4985afaacbcfe095c753443e87af4aad33014">VK_PPC_NOTOC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0e7a0e61e9e2418f5a362d17b4c1c6c9">VK_PPC_PCREL_OPT</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1ebb65d3581b26c6d9be3d4ff95d8648">VK_PPC_TLS</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3af1b5ef4b41faa6d2e73935860fa3c0">VK_PPC_TLS_PCREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a614a4f4a72a1a5fbf6b309990dbf9643">VK_PPC_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a55f8ba42b33462144024cc7a07194631">VK_PPC_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa4b8b58379694eb9c24793904e2b2089">VK_PPC_TOC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a86b94af00057681fc558d5ade49f77f9">VK_PPC_TOC_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac336aade6add02fc835b447c21d12074">VK_PPC_TOC_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985a9ea61bcfe12d2dbd766d06581e5abe79">VK_PPC_TOC_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66">VK_PPC_TOCBASE</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa022f5ada06b78d01fc4227b09a8722a">VK_PPC_TPREL_HA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a61a15f02c13a7251c97f9387c3f99ecb">VK_PPC_TPREL_HI</a>, <a href="#a5c463f6352570ee778c35c40949c4985ad1e8fbb210d1190a9c71fc0b5c2a74bc">VK_PPC_TPREL_HIGH</a>, <a href="#a5c463f6352570ee778c35c40949c4985a688a086d89be625bf3c11bab1e3ee549">VK_PPC_TPREL_HIGHA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a91432c86c48a7496dd9de6088182a12a">VK_PPC_TPREL_HIGHER</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1f9254d454e21c1ea81001a7e15a0917">VK_PPC_TPREL_HIGHERA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a00a33ecfac5457b544a31d2ce8f3695a">VK_PPC_TPREL_HIGHEST</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa810324618394114d0088f1c6ce3f7e9">VK_PPC_TPREL_HIGHESTA</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3ae3c5740fe01f98a256caeb5a1ae6f2">VK_PPC_TPREL_LO</a>, <a href="#a5c463f6352570ee778c35c40949c4985a357bed48651388b3b7882ed32f085ec1">VK_PPC_U</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">VK_SECREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae82d65eb3584ba7c4f28110e5f033763">VK_SIZE</a>, <a href="#a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d">VK_TLSCALL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a0dfb6ffd20ec6e759a99ca36206fc27b">VK_TLSDESC</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">VK_TLSGD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2a7aabe201191ea7c45e6ad02eef5bd2">VK_TLSGD_FDPIC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2bd18a4543b4686a238d7c84cf299257">VK_TLSLD</a>, <a href="#a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048">VK_TLSLDM</a>, <a href="#a5c463f6352570ee778c35c40949c4985a37de9fd63a2734733444afef60f66f05">VK_TLSLDM_FDPIC</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5d7dc0ab54306dc5d9af486598f7d26d">VK_TLVP</a>, <a href="#a5c463f6352570ee778c35c40949c4985a1b4b41a073cebf886ecd3828f0aaba89">VK_TLVPPAGE</a>, <a href="#a5c463f6352570ee778c35c40949c4985af0a99c543167803572c2fb1642f17010">VK_TLVPPAGEOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">VK_TPOFF</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a">VK_TPREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985afb3d29f6eb2d6914618498cfe61ca2bb">VK_VE_GOT_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a8884a571dcc413be5dce1128380932e7">VK_VE_GOT_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac80540810aee853573a4ad9f6ce02c0a">VK_VE_GOTOFF_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a68abe5c43d47c405dd5bb850a528be9c">VK_VE_GOTOFF_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985acef6f78a2cda59d8b56b70c1e4ce760e">VK_VE_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a06b57ad804a80f34c35391b7ceaf6429">VK_VE_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a43e08cb3b6baebc1c7f30b7de6e912c3">VK_VE_PC_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a36af1e0a05061d8f9f512c694a3f0064">VK_VE_PC_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985af258c4a492ad17e13a4b4203902e8120">VK_VE_PLT_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985aa9088a6103dd17b7ebc45bca3aded045">VK_VE_PLT_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a96c63d9e27f06d831286afaf0892fece">VK_VE_TLS_GD_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ab7d5356ca03b04fff69afbe6a9a4bf02">VK_VE_TLS_GD_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac903f694110764a3f1130550bd500f37">VK_VE_TPOFF_HI32</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac1b8a8b6f7974cdcec793a0f13b41b14">VK_VE_TPOFF_LO32</a>, <a href="#a5c463f6352570ee778c35c40949c4985a62dd0aeb9839db4490d0e271b00123f5">VK_WASM_FUNCINDEX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a5b59c0c7585f11717cc920f4823e19b0">VK_WASM_GOT_TLS</a>, <a href="#a5c463f6352570ee778c35c40949c4985ae58d84420e2227703a6f439f63517690">VK_WASM_MBREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a014ec8c7c1ea8fa9780614984167ff73">VK_WASM_TBREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985ac07f166f23e0a79d7a862db2c4ba34ec">VK_WASM_TLSREL</a>, <a href="#a5c463f6352570ee778c35c40949c4985a2fa9fd79289091758e4bdfbfb8c6ff9f">VK_WASM_TYPEINDEX</a>, <a href="#a5c463f6352570ee778c35c40949c4985a4acec19f33bc45f90643617e00ce9a81">VK_WEAKREF</a>, <a href="#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">VK_X86_ABS8</a> and <a href="#a5c463f6352570ee778c35c40949c4985aec6e66cd0fb96e202f1a13f25bf29cbf">VK_X86_PLTOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a0c4536e911b01c1a6f0ab8ed2a62bf16">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getKind {#ad860e326e495f296cdee70606908a6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::MCSymbolRefExpr::getKind ()</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ad7a73c5ca50f673d05234b59a93bfa29">llvm::MCExpr::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a5b3ab698b20fe1832388bb62f71c213e">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm21Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#af576492babedf4292598955c5adcf76b">llvm::AVRMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a7759c46e30fcf1d9af690f2788cac998">llvm::PPCMCCodeEmitter::getTLSRegEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc6a276f0a40e983e11fe851e818ad01">llvm::isPartOfGOTToPCRelPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a7ec597eb70645748d7299e7a05faa4a5">needsExpandMemInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a35779cde38be2f4c81791032dcf33b10">optimizeToShortImmediateForm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoreinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfinstprinter-cpp/#a5c6ef4b0a6eaef2b6b8e73fc3ff5701a">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvinstprinter-cpp/#a5c6ef4b0a6eaef2b6b8e73fc3ff5701a">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensainstprinter-cpp/#a948e4ad81c6d59fecdb91478eedbd9ef">printExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a6cd305cb01305d4c101633f77bf6e4bc">llvm::PPCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a71696cd21e4b5e6a498bfa1c891f147a">llvm::SystemZInstPrinterCommon::printPCRelTLSOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a> and <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>.</p>

</div>
</div>

### getSymbol {#a048f077746d95f142d02e56586862bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol &amp; llvm::MCSymbolRefExpr::getSymbol ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantpool/#a9d1e0d3d33bca317531734dc3f1ba547">llvm::ConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ac25530725b6ee241fdd59a2b41cc8222">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a58e3c2a4ec9c34e4a8c8388fb66946ae">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a912942cd73fd3f0a2dfb952fed5c49dc">llvm::MCWinCOFFStreamer::emitCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ad3e4f5bb59058be7d568e2505d04b830">llvm::NVPTXTargetStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#af576492babedf4292598955c5adcf76b">llvm::AVRMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a03ebbddf5185beab8e633649235fe873">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::finalizeCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a12d7f7b28045ca28e88138c63c174184">llvm::MCWinCOFFStreamer::finalizeCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a719cb125836c429953e4eb35be1e93b4">hasGOTReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#acc39fa43ddee9c26c911927bb0afee99">llvm::WebAssemblyInstPrinter::printCatchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoreinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensainstprinter-cpp/#a948e4ad81c6d59fecdb91478eedbd9ef">printExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a6cd305cb01305d4c101633f77bf6e4bc">llvm::PPCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a71696cd21e4b5e6a498bfa1c891f147a">llvm::SystemZInstPrinterCommon::printPCRelTLSOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#ae083e4782d3a3ca6e98fbaacbb8d3f8f">llvm::WinCOFFWriter::recordRelocation</a>.</p>

</div>
</div>

### hasSubsectionsViaSymbols {#aff40cdca21460452b93bdf50f1f1b74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolRefExpr::hasSubsectionsViaSymbols ()</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ad7a73c5ca50f673d05234b59a93bfa29">llvm::MCExpr::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
