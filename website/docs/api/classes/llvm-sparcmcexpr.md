---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparcmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SparcMCExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SparcMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">Target/Sparc/MCTargetDesc/SparcMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#abeab46e996c332583b97b10b5feb70f0">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd949533d83f9424826a09a35d9fb6a5">SparcMCExpr</a> (VariantKind Kind, const MCExpr *Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0abfc0f163ee1620e82cdb7ce9ea13">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408cec492b050bec5d09a6780b2fa980">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84606656d540381277112a534617ab22">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbbe2390073ea564aa0b9f4086d8c43">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0abb9491e71c31e77aefd74adb826ee">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88819488dd0ab798f12ef453bd1cffce">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78efd189f95f64ad01e7717d2442827f">Expr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20680c3e5b06d06cb84f5760d6b81618">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8493d80b8e10f21a7d4ea16ac003ea">parseVariantKind</a> (StringRef name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2eb927068968a5e489d0a4fcbf57bb2">printVariantKind</a> (raw_ostream &amp;OS, VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502d">Sparc::Fixups</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e1d3d2c1aae3a8d544d65df80ec53d">getFixupKind</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr">SparcMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70deb9c48e0455e55db69bfd5eea03d2">create</a> (VariantKind Kind, const MCExpr *Expr, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae854f8a87be2a15a84a37bc15bc7a739">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOpcode - Get the kind of this expression. <a href="#ae854f8a87be2a15a84a37bc15bc7a739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSubExpr - Get the child of this expression. <a href="#a059c9ce986366074388c61ad5c8430f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502d">Sparc::Fixups</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8252a78114a84769c8b7eb0ddc2b2172">getFixupKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFixupKind - Get the fixup kind of this expression. <a href="#a8252a78114a84769c8b7eb0ddc2b2172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#abeab46e996c332583b97b10b5feb70f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SparcMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_Sparc_None<a id="abeab46e996c332583b97b10b5feb70f0a2ce20e1eb69dc725232b82d3c68a211e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_LO<a id="abeab46e996c332583b97b10b5feb70f0a7d943f8130bcbcbe1d07fc8093a0d828"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_HI<a id="abeab46e996c332583b97b10b5feb70f0a7cc3a40023555c0f1f8ec0fb52e14643"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_H44<a id="abeab46e996c332583b97b10b5feb70f0a149694e627b7a3afd016ae37cc1abf18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_M44<a id="abeab46e996c332583b97b10b5feb70f0acd9a32326cc297655ce42f1cb302b68b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_L44<a id="abeab46e996c332583b97b10b5feb70f0a33e42b130d33bc70b96779be96719c95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_HH<a id="abeab46e996c332583b97b10b5feb70f0aacdc766ee0cae5af952c551c6efc0ce6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_HM<a id="abeab46e996c332583b97b10b5feb70f0aa3ed710d0eceeff3a3657b87612459e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_LM<a id="abeab46e996c332583b97b10b5feb70f0a7734fcad9392739266fa9c0bea9f6491"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_PC22<a id="abeab46e996c332583b97b10b5feb70f0a12d596dc769c1c497312c35a9fbf7de9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_PC10<a id="abeab46e996c332583b97b10b5feb70f0aa1121fa0bf9b15fd6ada2c4bc3c3db13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOT22<a id="abeab46e996c332583b97b10b5feb70f0a567ee252480e04bf85b1fc21844ccc08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOT10<a id="abeab46e996c332583b97b10b5feb70f0a0a52e554a258a7d372633a1c06e3fcf8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOT13<a id="abeab46e996c332583b97b10b5feb70f0a44a67d006ec25ec5260bd980ba20fc6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_13<a id="abeab46e996c332583b97b10b5feb70f0a6dc05c49b76aa391f559d973952a2c0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_WPLT30<a id="abeab46e996c332583b97b10b5feb70f0a590c6e92dc4e4a6bce8e55207c07afc0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_WDISP30<a id="abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_R_DISP32<a id="abeab46e996c332583b97b10b5feb70f0af92cd2ce45d818cf6690e01518a39b12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_GD_HI22<a id="abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_GD_LO10<a id="abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_GD_ADD<a id="abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_GD_CALL<a id="abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDM_HI22<a id="abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDM_LO10<a id="abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDM_ADD<a id="abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDM_CALL<a id="abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDO_HIX22<a id="abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDO_LOX10<a id="abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LDO_ADD<a id="abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_IE_HI22<a id="abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_IE_LO10<a id="abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_IE_LD<a id="abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_IE_LDX<a id="abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_IE_ADD<a id="abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LE_HIX22<a id="abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_TLS_LE_LOX10<a id="abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_HIX22<a id="abeab46e996c332583b97b10b5feb70f0ab7d50948b8a31e29ebe9f06d29296022"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_LOX10<a id="abeab46e996c332583b97b10b5feb70f0aa8ad9426fad69e10af7552e35c0d6242"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOTDATA_HIX22<a id="abeab46e996c332583b97b10b5feb70f0a371160726b2b6d2fe29d33a3e37b5705"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOTDATA_LOX10<a id="abeab46e996c332583b97b10b5feb70f0af2ecea368b0008b44871c44742405783"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_Sparc_GOTDATA_OP<a id="abeab46e996c332583b97b10b5feb70f0af1142f8727b7ef375f7b66f3de9f307c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SparcMCExpr() {#acd949533d83f9424826a09a35d9fb6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparcMCExpr::SparcMCExpr (<a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#a408cec492b050bec5d09a6780b2fa980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a>.</p>

</div>
</div>

### findAssociatedFragment() {#adfbbe2390073ea564aa0b9f4086d8c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::SparcMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#ad0abb9491e71c31e77aefd74adb826ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#ae854f8a87be2a15a84a37bc15bc7a739">getKind</a>, <a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d">VK_Sparc_TLS_GD_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac">VK_Sparc_TLS_GD_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232">VK_Sparc_TLS_GD_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d">VK_Sparc_TLS_GD_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513">VK_Sparc_TLS_IE_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db">VK_Sparc_TLS_IE_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d">VK_Sparc_TLS_IE_LD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21">VK_Sparc_TLS_IE_LDX</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0">VK_Sparc_TLS_IE_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a">VK_Sparc_TLS_LDM_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31">VK_Sparc_TLS_LDM_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002">VK_Sparc_TLS_LDM_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73">VK_Sparc_TLS_LDM_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc">VK_Sparc_TLS_LDO_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c">VK_Sparc_TLS_LDO_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8">VK_Sparc_TLS_LDO_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec">VK_Sparc_TLS_LE_HIX22</a> and <a href="#abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06">VK_Sparc_TLS_LE_LOX10</a>.</p>

</div>
</div>

### printImpl() {#aec0abfc0f163ee1620e82cdb7ce9ea13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a> and <a href="#aa2eb927068968a5e489d0a4fcbf57bb2">printVariantKind</a>.</p>

</div>
</div>

### visitUsedExpr() {#a84606656d540381277112a534617ab22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="#a059c9ce986366074388c61ad5c8430f2">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a78efd189f95f64ad01e7717d2442827f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SparcMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a88819488dd0ab798f12ef453bd1cffce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::SparcMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a20680c3e5b06d06cb84f5760d6b81618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### getFixupKind() {#a66e1d3d2c1aae3a8d544d65df80ec53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sparc::Fixups SparcMCExpr::getFixupKind (<a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a> Kind)</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da602d9804c6b15c3eaa51cdeeeda754d2">llvm::Sparc::fixup_sparc_13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4adff73a6fdb09236d160a1058cd738c">llvm::Sparc::fixup_sparc_call30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da3e8e53769c95864f744db5c800d2452c">llvm::Sparc::fixup_sparc_got10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4bd19ebcb42069f48ac3d45dc1dc2c95">llvm::Sparc::fixup_sparc_got13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7904709be5733140c3834f84bf9721d3">llvm::Sparc::fixup_sparc_got22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2cfd03bdef2da2a2493359d4443ffc00">llvm::Sparc::fixup_sparc_gotdata_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabb1e74c3b7243667280210404a2d21d3">llvm::Sparc::fixup_sparc_gotdata_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4ffe3fe32ce294fa71d496bd72924532">llvm::Sparc::fixup_sparc_gotdata_op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7cb7e71faac52ef24527a11e314e7dae">llvm::Sparc::fixup_sparc_h44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2ed85fcf7a68bb72867d54508fdfa214">llvm::Sparc::fixup_sparc_hh</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da178d40a3cdc113de1bc4814dd67a11bc">llvm::Sparc::fixup_sparc_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6be1cb6bff4acb2026f1107593c5bcc1">llvm::Sparc::fixup_sparc_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daf9431782a67249942ea90c9d7882ea18">llvm::Sparc::fixup_sparc_hm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabad234abccd9064339207fe71a70c7be">llvm::Sparc::fixup_sparc_l44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da138cb8615551a89f2ced1e3a40669bdd">llvm::Sparc::fixup_sparc_lm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da02012bd04e669f47b0ca2c3ef4ec8df7">llvm::Sparc::fixup_sparc_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1665b86cbda5300143d0c72d38b18b55">llvm::Sparc::fixup_sparc_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da284cdb6a9399209232aa3c13ca8d2618">llvm::Sparc::fixup_sparc_m44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dac6502cb4a88284870e35d967c53ac47f">llvm::Sparc::fixup_sparc_pc10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa00d9587c28c43679ea78179d779dd85">llvm::Sparc::fixup_sparc_pc22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7de44a4f47d68e0bb21221b59fc64104">llvm::Sparc::fixup_sparc_tls_gd_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1cb655722f351a56ac2d2d20c6d3f21c">llvm::Sparc::fixup_sparc_tls_gd_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da55d287c9fa6b9f05e7d86d910d08ef90">llvm::Sparc::fixup_sparc_tls_gd_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6fd27a363f32a384e19d57732da83400">llvm::Sparc::fixup_sparc_tls_gd_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da81404b1c1698c400556d6db381d79b9b">llvm::Sparc::fixup_sparc_tls_ie_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da28c137eeff3f5dc170642e5313acd883">llvm::Sparc::fixup_sparc_tls_ie_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da0f86df663d98896b5c6d6d04f70b8f76">llvm::Sparc::fixup_sparc_tls_ie_ld</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafe9a137fc276c5872c10a68d18b6a1ee">llvm::Sparc::fixup_sparc_tls_ie_ldx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da98ce1ac1905989049a13fcc997c6800c">llvm::Sparc::fixup_sparc_tls_ie_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da20876dd25f69286a4dc4c4550f06e11f">llvm::Sparc::fixup_sparc_tls_ldm_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da944eebfbe22a2c847d37530c43b3c1f3">llvm::Sparc::fixup_sparc_tls_ldm_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa416e524e88172a66fad9215c0aa87d2">llvm::Sparc::fixup_sparc_tls_ldm_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da85b7e3dc16b048b452f479497746c819">llvm::Sparc::fixup_sparc_tls_ldm_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4fc6b4d7c79e1fb07e1c82aa851d2bb9">llvm::Sparc::fixup_sparc_tls_ldo_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4d435f58d4d1322c2d1db3f0ca19bdd6">llvm::Sparc::fixup_sparc_tls_ldo_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1fc5a8838faa83012242676700d3fbe9">llvm::Sparc::fixup_sparc_tls_ldo_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da26c24bbb56bdfabcd601f3763e07888c">llvm::Sparc::fixup_sparc_tls_le_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da401542a0ee1c7424a271c196e9b70de2">llvm::Sparc::fixup_sparc_tls_le_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafa321c88b1e9bb39ab5b2e09b05fe7a6">llvm::Sparc::fixup_sparc_wplt30</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a6dc05c49b76aa391f559d973952a2c0d">VK_Sparc_13</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0a52e554a258a7d372633a1c06e3fcf8">VK_Sparc_GOT10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a44a67d006ec25ec5260bd980ba20fc6c">VK_Sparc_GOT13</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a567ee252480e04bf85b1fc21844ccc08">VK_Sparc_GOT22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a371160726b2b6d2fe29d33a3e37b5705">VK_Sparc_GOTDATA_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af2ecea368b0008b44871c44742405783">VK_Sparc_GOTDATA_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af1142f8727b7ef375f7b66f3de9f307c">VK_Sparc_GOTDATA_OP</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a149694e627b7a3afd016ae37cc1abf18">VK_Sparc_H44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacdc766ee0cae5af952c551c6efc0ce6">VK_Sparc_HH</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7cc3a40023555c0f1f8ec0fb52e14643">VK_Sparc_HI</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ab7d50948b8a31e29ebe9f06d29296022">VK_Sparc_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa3ed710d0eceeff3a3657b87612459e7">VK_Sparc_HM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a33e42b130d33bc70b96779be96719c95">VK_Sparc_L44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7734fcad9392739266fa9c0bea9f6491">VK_Sparc_LM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7d943f8130bcbcbe1d07fc8093a0d828">VK_Sparc_LO</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa8ad9426fad69e10af7552e35c0d6242">VK_Sparc_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd9a32326cc297655ce42f1cb302b68b">VK_Sparc_M44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa1121fa0bf9b15fd6ada2c4bc3c3db13">VK_Sparc_PC10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a12d596dc769c1c497312c35a9fbf7de9">VK_Sparc_PC22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d">VK_Sparc_TLS_GD_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac">VK_Sparc_TLS_GD_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232">VK_Sparc_TLS_GD_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d">VK_Sparc_TLS_GD_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513">VK_Sparc_TLS_IE_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db">VK_Sparc_TLS_IE_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d">VK_Sparc_TLS_IE_LD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21">VK_Sparc_TLS_IE_LDX</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0">VK_Sparc_TLS_IE_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a">VK_Sparc_TLS_LDM_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31">VK_Sparc_TLS_LDM_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002">VK_Sparc_TLS_LDM_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73">VK_Sparc_TLS_LDM_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc">VK_Sparc_TLS_LDO_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c">VK_Sparc_TLS_LDO_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8">VK_Sparc_TLS_LDO_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec">VK_Sparc_TLS_LE_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06">VK_Sparc_TLS_LE_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403">VK_Sparc_WDISP30</a> and <a href="#abeab46e996c332583b97b10b5feb70f0a590c6e92dc4e4a6bce8e55207c07afc0">VK_Sparc_WPLT30</a>.</p>

</div>
</div>

### parseVariantKind() {#a8f8493d80b8e10f21a7d4ea16ac003ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcMCExpr::VariantKind SparcMCExpr::parseVariantKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
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



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0a52e554a258a7d372633a1c06e3fcf8">VK_Sparc_GOT10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a44a67d006ec25ec5260bd980ba20fc6c">VK_Sparc_GOT13</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a567ee252480e04bf85b1fc21844ccc08">VK_Sparc_GOT22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a371160726b2b6d2fe29d33a3e37b5705">VK_Sparc_GOTDATA_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af2ecea368b0008b44871c44742405783">VK_Sparc_GOTDATA_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af1142f8727b7ef375f7b66f3de9f307c">VK_Sparc_GOTDATA_OP</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a149694e627b7a3afd016ae37cc1abf18">VK_Sparc_H44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacdc766ee0cae5af952c551c6efc0ce6">VK_Sparc_HH</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7cc3a40023555c0f1f8ec0fb52e14643">VK_Sparc_HI</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ab7d50948b8a31e29ebe9f06d29296022">VK_Sparc_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa3ed710d0eceeff3a3657b87612459e7">VK_Sparc_HM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a33e42b130d33bc70b96779be96719c95">VK_Sparc_L44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7734fcad9392739266fa9c0bea9f6491">VK_Sparc_LM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7d943f8130bcbcbe1d07fc8093a0d828">VK_Sparc_LO</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa8ad9426fad69e10af7552e35c0d6242">VK_Sparc_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd9a32326cc297655ce42f1cb302b68b">VK_Sparc_M44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2ce20e1eb69dc725232b82d3c68a211e">VK_Sparc_None</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa1121fa0bf9b15fd6ada2c4bc3c3db13">VK_Sparc_PC10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a12d596dc769c1c497312c35a9fbf7de9">VK_Sparc_PC22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af92cd2ce45d818cf6690e01518a39b12">VK_Sparc_R_DISP32</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d">VK_Sparc_TLS_GD_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac">VK_Sparc_TLS_GD_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232">VK_Sparc_TLS_GD_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d">VK_Sparc_TLS_GD_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513">VK_Sparc_TLS_IE_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db">VK_Sparc_TLS_IE_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d">VK_Sparc_TLS_IE_LD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21">VK_Sparc_TLS_IE_LDX</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0">VK_Sparc_TLS_IE_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a">VK_Sparc_TLS_LDM_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31">VK_Sparc_TLS_LDM_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002">VK_Sparc_TLS_LDM_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73">VK_Sparc_TLS_LDM_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc">VK_Sparc_TLS_LDO_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c">VK_Sparc_TLS_LDO_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8">VK_Sparc_TLS_LDO_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec">VK_Sparc_TLS_LE_HIX22</a> and <a href="#abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06">VK_Sparc_TLS_LE_LOX10</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>.</p>

</div>
</div>

### printVariantKind() {#aa2eb927068968a5e489d0a4fcbf57bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcMCExpr::printVariantKind (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a> Kind)</td>
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



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a6dc05c49b76aa391f559d973952a2c0d">VK_Sparc_13</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0a52e554a258a7d372633a1c06e3fcf8">VK_Sparc_GOT10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a44a67d006ec25ec5260bd980ba20fc6c">VK_Sparc_GOT13</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a567ee252480e04bf85b1fc21844ccc08">VK_Sparc_GOT22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a371160726b2b6d2fe29d33a3e37b5705">VK_Sparc_GOTDATA_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af2ecea368b0008b44871c44742405783">VK_Sparc_GOTDATA_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af1142f8727b7ef375f7b66f3de9f307c">VK_Sparc_GOTDATA_OP</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a149694e627b7a3afd016ae37cc1abf18">VK_Sparc_H44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacdc766ee0cae5af952c551c6efc0ce6">VK_Sparc_HH</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7cc3a40023555c0f1f8ec0fb52e14643">VK_Sparc_HI</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ab7d50948b8a31e29ebe9f06d29296022">VK_Sparc_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa3ed710d0eceeff3a3657b87612459e7">VK_Sparc_HM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a33e42b130d33bc70b96779be96719c95">VK_Sparc_L44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7734fcad9392739266fa9c0bea9f6491">VK_Sparc_LM</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7d943f8130bcbcbe1d07fc8093a0d828">VK_Sparc_LO</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa8ad9426fad69e10af7552e35c0d6242">VK_Sparc_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd9a32326cc297655ce42f1cb302b68b">VK_Sparc_M44</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2ce20e1eb69dc725232b82d3c68a211e">VK_Sparc_None</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aa1121fa0bf9b15fd6ada2c4bc3c3db13">VK_Sparc_PC10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a12d596dc769c1c497312c35a9fbf7de9">VK_Sparc_PC22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0af92cd2ce45d818cf6690e01518a39b12">VK_Sparc_R_DISP32</a>, <a href="#abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d">VK_Sparc_TLS_GD_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac">VK_Sparc_TLS_GD_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232">VK_Sparc_TLS_GD_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d">VK_Sparc_TLS_GD_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513">VK_Sparc_TLS_IE_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db">VK_Sparc_TLS_IE_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d">VK_Sparc_TLS_IE_LD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21">VK_Sparc_TLS_IE_LDX</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0">VK_Sparc_TLS_IE_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a">VK_Sparc_TLS_LDM_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31">VK_Sparc_TLS_LDM_CALL</a>, <a href="#abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002">VK_Sparc_TLS_LDM_HI22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73">VK_Sparc_TLS_LDM_LO10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc">VK_Sparc_TLS_LDO_ADD</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c">VK_Sparc_TLS_LDO_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8">VK_Sparc_TLS_LDO_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec">VK_Sparc_TLS_LE_HIX22</a>, <a href="#abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06">VK_Sparc_TLS_LE_LOX10</a>, <a href="#abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403">VK_Sparc_WDISP30</a> and <a href="#abeab46e996c332583b97b10b5feb70f0a590c6e92dc4e4a6bce8e55207c07afc0">VK_Sparc_WPLT30</a>.</p>


<p>Referenced by <a href="#aec0abfc0f163ee1620e82cdb7ce9ea13">printImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#a70deb9c48e0455e55db69bfd5eea03d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SparcMCExpr * SparcMCExpr::create (<a href="#abeab46e996c332583b97b10b5feb70f0">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#ad7df82b40c89fe57a01cfd473dcfcd63">createPCXRelExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a0d0d7f47cce3c25a82585c9e4f27abac">createSparcMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#abc43ac9f2d903054af8e134b6eb37a9f">llvm::SparcELFMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#af21e68297b7ed966f286d8701beed510">llvm::SparcELFMCAsmInfo::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getFixupKind {#a8252a78114a84769c8b7eb0ddc2b2172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sparc::Fixups llvm::SparcMCExpr::getFixupKind ()</td>
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

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<p>Reference <a href="#a8252a78114a84769c8b7eb0ddc2b2172">getFixupKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a> and <a href="#a8252a78114a84769c8b7eb0ddc2b2172">getFixupKind</a>.</p>

</div>
</div>

### getKind {#ae854f8a87be2a15a84a37bc15bc7a739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::SparcMCExpr::getKind ()</td>
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

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<p>Referenced by <a href="#ad0abb9491e71c31e77aefd74adb826ee">fixELFSymbolsInTLSFixups</a>.</p>

</div>
</div>

### getSubExpr {#a059c9ce986366074388c61ad5c8430f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::SparcMCExpr::getSubExpr ()</td>
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

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a>.</p>


<p>Referenced by <a href="#a408cec492b050bec5d09a6780b2fa980">evaluateAsRelocatableImpl</a>, <a href="#adfbbe2390073ea564aa0b9f4086d8c43">findAssociatedFragment</a>, <a href="#ad0abb9491e71c31e77aefd74adb826ee">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a>, <a href="#aec0abfc0f163ee1620e82cdb7ce9ea13">printImpl</a> and <a href="#a84606656d540381277112a534617ab22">visitUsedExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp">SparcMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">SparcMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
