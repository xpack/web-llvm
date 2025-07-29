---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vemcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VEMCExpr` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VEMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">Target/VE/MCTargetDesc/VEMCExpr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetexpr">MCTargetExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an extension point for target-specific <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> subclasses to implement. <a href="/web-llvm/docs/api/classes/llvm/mctargetexpr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#af04d361a436f54db54865f22611d8844">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e73241d1f974f15d9ea59b03c23918">VEMCExpr</a> (VariantKind Kind, const MCExpr *Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56b48d047f6f858510a0359fc41ceb1">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7ef1f889fba81bf6d37bbaec0c1c8a">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b434b7b50ec9cc59b53879dafc4af83">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c01ea8a9f7f30631202409dc4c6097">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae555917520a703b5f76a5e01fd695566">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af04d361a436f54db54865f22611d8844">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02aec7e4a1da2f9907cf396fac5d96ce">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7d914d293abdaf133b9678bc414976">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae342aa09551117798d50cea865b964">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#af04d361a436f54db54865f22611d8844">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34980fe75ddfddc6b82e729a114d63ee">parseVariantKind</a> (StringRef name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b6af0581db08db179d106bd9359662">printVariantKind</a> (raw_ostream &amp;OS, VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7821b626d1794902e8c557e77fd4eeff">printVariantKindSuffix</a> (raw_ostream &amp;OS, VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178a">VE::Fixups</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054211421ff240aac77f21e13e2b6203">getFixupKind</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vemcexpr">VEMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874e7a37a3a7e51ef151eb95e146638f">create</a> (VariantKind Kind, const MCExpr *Expr, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af04d361a436f54db54865f22611d8844">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf80b2a40229dbe9c1c1e343dfabbc8f">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOpcode - Get the kind of this expression. <a href="#acf80b2a40229dbe9c1c1e343dfabbc8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSubExpr - Get the child of this expression. <a href="#acf94c893e26b74ba84b365b0da9ab0a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178a">VE::Fixups</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8829b314d024dd55b5b996db45b85a">getFixupKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFixupKind - Get the fixup kind of this expression. <a href="#a8e8829b314d024dd55b5b996db45b85a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#af04d361a436f54db54865f22611d8844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::VEMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_VE_None<a id="af04d361a436f54db54865f22611d8844a221dc68f6ee115899fdd31260fda51a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_REFLONG<a id="af04d361a436f54db54865f22611d8844a518d06109a2bfdfa92b8471d4a62bc5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_HI32<a id="af04d361a436f54db54865f22611d8844ac94ed29f4289901bc1de4347e9d80729"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_LO32<a id="af04d361a436f54db54865f22611d8844a6a83319d3cc9131896854c2e350fe3c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PC_HI32<a id="af04d361a436f54db54865f22611d8844afa8cbe2b3aec1ab1c45fcc47016c6a13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PC_LO32<a id="af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOT_HI32<a id="af04d361a436f54db54865f22611d8844afd3e143e988f0199bebc087e3808150d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOT_LO32<a id="af04d361a436f54db54865f22611d8844afa2697fe92ab835a60c8c60be2031968"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOTOFF_HI32<a id="af04d361a436f54db54865f22611d8844adef45f38bec1d2389f16ce3a745e9f8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_GOTOFF_LO32<a id="af04d361a436f54db54865f22611d8844afb5ca8be38b3fe175de653cba9565e6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PLT_HI32<a id="af04d361a436f54db54865f22611d8844a1b10645839cb20c6c30ce8fd24488cac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_PLT_LO32<a id="af04d361a436f54db54865f22611d8844a7718c139a271dfb69d284a5dcc020d1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TLS_GD_HI32<a id="af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TLS_GD_LO32<a id="af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TPOFF_HI32<a id="af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_VE_TPOFF_LO32<a id="af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### VEMCExpr() {#ab7e73241d1f974f15d9ea59b03c23918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VEMCExpr::VEMCExpr (<a href="#af04d361a436f54db54865f22611d8844">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#a8c7ef1f889fba81bf6d37bbaec0c1c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#acf80b2a40229dbe9c1c1e343dfabbc8f">getKind</a>, <a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a> and <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>.</p>

</div>
</div>

### findAssociatedFragment() {#a71c01ea8a9f7f30631202409dc4c6097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::VEMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#ae555917520a703b5f76a5e01fd695566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#acf80b2a40229dbe9c1c1e343dfabbc8f">getKind</a>, <a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a>, <a href="#af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc">VK_VE_TLS_GD_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b">VK_VE_TLS_GD_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f">VK_VE_TPOFF_HI32</a> and <a href="#af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340">VK_VE_TPOFF_LO32</a>.</p>

</div>
</div>

### printImpl() {#af56b48d047f6f858510a0359fc41ceb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a>, <a href="#ad5b6af0581db08db179d106bd9359662">printVariantKind</a> and <a href="#a7821b626d1794902e8c557e77fd4eeff">printVariantKindSuffix</a>.</p>

</div>
</div>

### visitUsedExpr() {#a9b434b7b50ec9cc59b53879dafc4af83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="#acf94c893e26b74ba84b365b0da9ab0a4">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a1d7d914d293abdaf133b9678bc414976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::VEMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a02aec7e4a1da2f9907cf396fac5d96ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::VEMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afae342aa09551117798d50cea865b964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VEMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### getFixupKind() {#a054211421ff240aac77f21e13e2b6203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VE::Fixups VEMCExpr::getFixupKind (<a href="#af04d361a436f54db54865f22611d8844">VariantKind</a> Kind)</td>
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



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa2ad67f23f486e531ca82d71890a68a01">llvm::VE::fixup_ve_got_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa5405339da89126a4026867f540e33441">llvm::VE::fixup_ve_got_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa401919b7d910ed497dbe04087ffb51c0">llvm::VE::fixup_ve_gotoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa8a34234c9b623e8c9c425c81be4cb62c">llvm::VE::fixup_ve_gotoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaa5364c6e73ddba627ce657e4356d0b49">llvm::VE::fixup_ve_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa78d516c790863298415e6177345d5ff8">llvm::VE::fixup_ve_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa667f7a97724598853fb6d3cebb1e27d3">llvm::VE::fixup_ve_pc_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaaf6751559269bc22d124be47cec2bdb2">llvm::VE::fixup_ve_pc_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aade9959851c0f191c677111084c14698f">llvm::VE::fixup_ve_plt_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa122241fcebbf6c6cef07b513c0191a7c">llvm::VE::fixup_ve_plt_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaf3cea4fe606bf2531f03ca6576c51961">llvm::VE::fixup_ve_reflong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafc47658a501eaa76ba863b76fadd9735">llvm::VE::fixup_ve_tls_gd_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafa85f01d7cc2698698e63aa36c528204">llvm::VE::fixup_ve_tls_gd_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa0312ddb55e9fd7d4e1288f15f6ac4246">llvm::VE::fixup_ve_tpoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aac8d006c70ba7b24159949d6159dcf08c">llvm::VE::fixup_ve_tpoff_lo32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af04d361a436f54db54865f22611d8844afd3e143e988f0199bebc087e3808150d">VK_VE_GOT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afa2697fe92ab835a60c8c60be2031968">VK_VE_GOT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844adef45f38bec1d2389f16ce3a745e9f8c">VK_VE_GOTOFF_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afb5ca8be38b3fe175de653cba9565e6f">VK_VE_GOTOFF_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844ac94ed29f4289901bc1de4347e9d80729">VK_VE_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a6a83319d3cc9131896854c2e350fe3c5">VK_VE_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844afa8cbe2b3aec1ab1c45fcc47016c6a13">VK_VE_PC_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064">VK_VE_PC_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a1b10645839cb20c6c30ce8fd24488cac">VK_VE_PLT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a7718c139a271dfb69d284a5dcc020d1b">VK_VE_PLT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a518d06109a2bfdfa92b8471d4a62bc5d">VK_VE_REFLONG</a>, <a href="#af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc">VK_VE_TLS_GD_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b">VK_VE_TLS_GD_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f">VK_VE_TPOFF_HI32</a> and <a href="#af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340">VK_VE_TPOFF_LO32</a>.</p>

</div>
</div>

### parseVariantKind() {#a34980fe75ddfddc6b82e729a114d63ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VEMCExpr::VariantKind VEMCExpr::parseVariantKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
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



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#af04d361a436f54db54865f22611d8844afd3e143e988f0199bebc087e3808150d">VK_VE_GOT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afa2697fe92ab835a60c8c60be2031968">VK_VE_GOT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844adef45f38bec1d2389f16ce3a745e9f8c">VK_VE_GOTOFF_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afb5ca8be38b3fe175de653cba9565e6f">VK_VE_GOTOFF_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844ac94ed29f4289901bc1de4347e9d80729">VK_VE_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a6a83319d3cc9131896854c2e350fe3c5">VK_VE_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a221dc68f6ee115899fdd31260fda51a3">VK_VE_None</a>, <a href="#af04d361a436f54db54865f22611d8844afa8cbe2b3aec1ab1c45fcc47016c6a13">VK_VE_PC_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064">VK_VE_PC_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a1b10645839cb20c6c30ce8fd24488cac">VK_VE_PLT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a7718c139a271dfb69d284a5dcc020d1b">VK_VE_PLT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc">VK_VE_TLS_GD_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b">VK_VE_TLS_GD_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f">VK_VE_TPOFF_HI32</a> and <a href="#af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340">VK_VE_TPOFF_LO32</a>.</p>

</div>
</div>

### printVariantKind() {#ad5b6af0581db08db179d106bd9359662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEMCExpr::printVariantKind (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#af04d361a436f54db54865f22611d8844">VariantKind</a> Kind)</td>
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



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="#af04d361a436f54db54865f22611d8844afd3e143e988f0199bebc087e3808150d">VK_VE_GOT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afa2697fe92ab835a60c8c60be2031968">VK_VE_GOT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844adef45f38bec1d2389f16ce3a745e9f8c">VK_VE_GOTOFF_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afb5ca8be38b3fe175de653cba9565e6f">VK_VE_GOTOFF_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844ac94ed29f4289901bc1de4347e9d80729">VK_VE_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a6a83319d3cc9131896854c2e350fe3c5">VK_VE_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a221dc68f6ee115899fdd31260fda51a3">VK_VE_None</a>, <a href="#af04d361a436f54db54865f22611d8844afa8cbe2b3aec1ab1c45fcc47016c6a13">VK_VE_PC_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064">VK_VE_PC_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a1b10645839cb20c6c30ce8fd24488cac">VK_VE_PLT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a7718c139a271dfb69d284a5dcc020d1b">VK_VE_PLT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a518d06109a2bfdfa92b8471d4a62bc5d">VK_VE_REFLONG</a>, <a href="#af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc">VK_VE_TLS_GD_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b">VK_VE_TLS_GD_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f">VK_VE_TPOFF_HI32</a> and <a href="#af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340">VK_VE_TPOFF_LO32</a>.</p>


<p>Referenced by <a href="#af56b48d047f6f858510a0359fc41ceb1">printImpl</a>.</p>

</div>
</div>

### printVariantKindSuffix() {#a7821b626d1794902e8c557e77fd4eeff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VEMCExpr::printVariantKindSuffix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#af04d361a436f54db54865f22611d8844">VariantKind</a> Kind)</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>References <a href="#af04d361a436f54db54865f22611d8844afd3e143e988f0199bebc087e3808150d">VK_VE_GOT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afa2697fe92ab835a60c8c60be2031968">VK_VE_GOT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844adef45f38bec1d2389f16ce3a745e9f8c">VK_VE_GOTOFF_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844afb5ca8be38b3fe175de653cba9565e6f">VK_VE_GOTOFF_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844ac94ed29f4289901bc1de4347e9d80729">VK_VE_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a6a83319d3cc9131896854c2e350fe3c5">VK_VE_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a221dc68f6ee115899fdd31260fda51a3">VK_VE_None</a>, <a href="#af04d361a436f54db54865f22611d8844afa8cbe2b3aec1ab1c45fcc47016c6a13">VK_VE_PC_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064">VK_VE_PC_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a1b10645839cb20c6c30ce8fd24488cac">VK_VE_PLT_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844a7718c139a271dfb69d284a5dcc020d1b">VK_VE_PLT_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a518d06109a2bfdfa92b8471d4a62bc5d">VK_VE_REFLONG</a>, <a href="#af04d361a436f54db54865f22611d8844a1d3ac7169ac9e57f4649b6511b33cdbc">VK_VE_TLS_GD_HI32</a>, <a href="#af04d361a436f54db54865f22611d8844ac76c6bd05314c1edf7fbd5f46da4128b">VK_VE_TLS_GD_LO32</a>, <a href="#af04d361a436f54db54865f22611d8844a4676c87c5e1b37d734a62bdc661de99f">VK_VE_TPOFF_HI32</a> and <a href="#af04d361a436f54db54865f22611d8844a817ce24e954272bd0202712a1c7ec340">VK_VE_TPOFF_LO32</a>.</p>


<p>Referenced by <a href="#af56b48d047f6f858510a0359fc41ceb1">printImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#a874e7a37a3a7e51ef151eb95e146638f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VEMCExpr * VEMCExpr::create (<a href="#af04d361a436f54db54865f22611d8844">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a1149e610692549287d358a9926ca0d44">createGOTRelExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a587150a33a51744021fd1bc8026194d3">createVEMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getFixupKind {#a8e8829b314d024dd55b5b996db45b85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VE::Fixups llvm::VEMCExpr::getFixupKind ()</td>
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

<p>getFixupKind - Get the fixup kind of this expression.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<p>Reference <a href="#a8e8829b314d024dd55b5b996db45b85a">getFixupKind</a>.</p>


<p>Referenced by <a href="#a8e8829b314d024dd55b5b996db45b85a">getFixupKind</a>.</p>

</div>
</div>

### getKind {#acf80b2a40229dbe9c1c1e343dfabbc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::VEMCExpr::getKind ()</td>
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

<p>getOpcode - Get the kind of this expression.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<p>Referenced by <a href="#a8c7ef1f889fba81bf6d37bbaec0c1c8a">evaluateAsRelocatableImpl</a> and <a href="#ae555917520a703b5f76a5e01fd695566">fixELFSymbolsInTLSFixups</a>.</p>

</div>
</div>

### getSubExpr {#acf94c893e26b74ba84b365b0da9ab0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::VEMCExpr::getSubExpr ()</td>
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

<p>getSubExpr - Get the child of this expression.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a>.</p>


<p>Referenced by <a href="#a8c7ef1f889fba81bf6d37bbaec0c1c8a">evaluateAsRelocatableImpl</a>, <a href="#a71c01ea8a9f7f30631202409dc4c6097">findAssociatedFragment</a>, <a href="#ae555917520a703b5f76a5e01fd695566">fixELFSymbolsInTLSFixups</a>, <a href="#af56b48d047f6f858510a0359fc41ceb1">printImpl</a> and <a href="#a9b434b7b50ec9cc59b53879dafc4af83">visitUsedExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp">VEMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">VEMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
