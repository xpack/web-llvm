---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64mcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64MCExpr` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64MCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">Target/AArch64/MCTargetDesc/AArch64MCExpr.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr">AArch64AuthMCExpr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#abec9c1dd43489b968c9780860bad71bf">...</a> }</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a585c3355b561e0bd7a9e8d3cbed44">AArch64MCExpr</a> (const MCExpr *Expr, VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7b303dd646822f22c9b1f6169162b4">getVariantKindName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the variant kind into an ELF-appropriate modifier (e.g. <a href="#a4c7b303dd646822f22c9b1f6169162b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d76f738ef1a55d72a3a429c8eab475">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5979780bec8026d8fd6cb8bf024b3086">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d1f8b239360ee96cd7a33f384fa21b">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee670ab9e4208096e0aff88d1a28034">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef0aa1408d6fd0ecb399eb97c5aadc5">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad34eaeebe09350fbc7d251a89ecad4">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415b7d11d0dc2d887b95b66ea6ece596">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8865f9c5ef2c6882f77df724f2bbce77">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr">AArch64MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d44e8b0d35d0b19946a50e8229ab86">create</a> (const MCExpr *Expr, VariantKind Kind, MCContext &amp;Ctx)</td>
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

## VariantKind information extractors. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e3d0ae8a67b027d48dbb2a51ed6e9a">getSymbolLoc</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dfd432f33b5e5ff4114b9be04a2b25f">getAddressFrag</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2b5e4ba4c1ccd001580fc8181e52eb">isNotChecked</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17d0c21f5ebab570d850a8e8a4ffa9f">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of this expression. <a href="#ab17d0c21f5ebab570d850a8e8a4ffa9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc269d1f3523366720c8c5d8d382722">getSubExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the expression this modifier applies to. <a href="#aadc269d1f3523366720c8c5d8d382722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#abec9c1dd43489b968c9780860bad71bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64MCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_ABS<a id="abec9c1dd43489b968c9780860bad71bfa873476895e81395d69f2a8a5e9f298cf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SABS<a id="abec9c1dd43489b968c9780860bad71bfae88eb6cdf1eae5ef51e211504b00e706"></a></td>
<td class="doxyEnumItemDescription"> (= 0x002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL<a id="abec9c1dd43489b968c9780860bad71bfab98c64bd3be65858d30034f3ca5fcfbf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x003)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT<a id="abec9c1dd43489b968c9780860bad71bfa96518ec6ca1da559ff4a909126b88060"></a></td>
<td class="doxyEnumItemDescription"> (= 0x004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL<a id="abec9c1dd43489b968c9780860bad71bfa261e5fdfac362b9c39961c5226dbfccf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x005)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPREL<a id="abec9c1dd43489b968c9780860bad71bfa6b76c48acac537ea0f3accd4f946b223"></a></td>
<td class="doxyEnumItemDescription"> (= 0x006)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL<a id="abec9c1dd43489b968c9780860bad71bfaa3020e9ba5dfa0324318faad507a0a58"></a></td>
<td class="doxyEnumItemDescription"> (= 0x007)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC<a id="abec9c1dd43489b968c9780860bad71bfaa1193d791c0127a6f7a86565a3f460bd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SECREL<a id="abec9c1dd43489b968c9780860bad71bfaec64aa7810f0b31023d490a86d01d415"></a></td>
<td class="doxyEnumItemDescription"> (= 0x009)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AUTH<a id="abec9c1dd43489b968c9780860bad71bfa0121933247ec3c2a0477b4e9142fcdc9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AUTHADDR<a id="abec9c1dd43489b968c9780860bad71bfaa8bd8587ab7bb2c4e6db67d515b0d83e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00b)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_AUTH<a id="abec9c1dd43489b968c9780860bad71bfa9ec4c589014eb66893073ac3083a2670"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00c)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC_AUTH<a id="abec9c1dd43489b968c9780860bad71bfa32da9cfae143cc7c95c2e0f54ca40bcc"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00d)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SymLocBits<a id="abec9c1dd43489b968c9780860bad71bfa69094d51626dc25699fb27be5e23d119"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00f)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PAGE<a id="abec9c1dd43489b968c9780860bad71bfa0809191a4698f385b9a261d81ff588eb"></a></td>
<td class="doxyEnumItemDescription"> (= 0x010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PAGEOFF<a id="abec9c1dd43489b968c9780860bad71bfa3560c4b55ab38ca90cfe2434429bb878"></a></td>
<td class="doxyEnumItemDescription"> (= 0x020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_HI12<a id="abec9c1dd43489b968c9780860bad71bfaa4531e7925a13cb837c64da9db9a971d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x030)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_G0<a id="abec9c1dd43489b968c9780860bad71bfa0e5e06b19986568f2c1e60713e2ad16a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x040)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_G1<a id="abec9c1dd43489b968c9780860bad71bfa1f089fe988759598e6be192bc25fda14"></a></td>
<td class="doxyEnumItemDescription"> (= 0x050)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_G2<a id="abec9c1dd43489b968c9780860bad71bfa7f9d6eabce1bf6172cc4d52eb1a572da"></a></td>
<td class="doxyEnumItemDescription"> (= 0x060)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_G3<a id="abec9c1dd43489b968c9780860bad71bfa615c30307b7a2762031b185b1f0b0333"></a></td>
<td class="doxyEnumItemDescription"> (= 0x070)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LO15<a id="abec9c1dd43489b968c9780860bad71bfa8456ae950bf4e253ace9693cd8635c80"></a></td>
<td class="doxyEnumItemDescription"> (= 0x080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AddressFragBits<a id="abec9c1dd43489b968c9780860bad71bfac023b84e4a49df08de7abf40646e9024"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0f0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_NC<a id="abec9c1dd43489b968c9780860bad71bfacfebe394a2b06edc4ddc5e96f6295776"></a></td>
<td class="doxyEnumItemDescription"> (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CALL<a id="abec9c1dd43489b968c9780860bad71bfa7df30bfd9a5a56ae922f3597d31363b0"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_PAGE<a id="abec9c1dd43489b968c9780860bad71bfaaf6f9676ef24562e98c151543f52efc8"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_PAGE_NC<a id="abec9c1dd43489b968c9780860bad71bfa660036640793b7c6285441ebaaec4c6a"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_PAGE    | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G3<a id="abec9c1dd43489b968c9780860bad71bfa963191759d19cf8d90bc0c40435c8cb8"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G2<a id="abec9c1dd43489b968c9780860bad71bfa284689a52a5f79b95b051a057c54fb1e"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G2_S<a id="abec9c1dd43489b968c9780860bad71bfa536c18c873600b1e2aba9d9f894e9213"></a></td>
<td class="doxyEnumItemDescription"> (= VK_SABS         | VK_G2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G2_NC<a id="abec9c1dd43489b968c9780860bad71bfa1089df68239d0e46c2fba2190c4c0eb8"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G2      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G1<a id="abec9c1dd43489b968c9780860bad71bfae40f238af3f6fe589641a720ab4f97a8"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G1_S<a id="abec9c1dd43489b968c9780860bad71bfa53f60806897246321227204c69d467c3"></a></td>
<td class="doxyEnumItemDescription"> (= VK_SABS         | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G1_NC<a id="abec9c1dd43489b968c9780860bad71bfa1f931e50ae5f4c5f77e050447b2e3320"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G1      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G0<a id="abec9c1dd43489b968c9780860bad71bfa35474485d868b25489fc57669a9c27f9"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G0_S<a id="abec9c1dd43489b968c9780860bad71bfa7eb9497609b61ca20e383022f9ab3290"></a></td>
<td class="doxyEnumItemDescription"> (= VK_SABS         | VK_G0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_ABS_G0_NC<a id="abec9c1dd43489b968c9780860bad71bfa65e6d1b5482060081af43ab78352964d"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_G0      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LO12<a id="abec9c1dd43489b968c9780860bad71bfac273d7a8ebcef5784a4904ffe145aefe"></a></td>
<td class="doxyEnumItemDescription"> (= VK_ABS          | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G3<a id="abec9c1dd43489b968c9780860bad71bfa9a4ed17656f61247e51858d2f8d9203d"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G2<a id="abec9c1dd43489b968c9780860bad71bfae308678726c12af491f9647e76f3f1b9"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G2_NC<a id="abec9c1dd43489b968c9780860bad71bfa432b91e82080f70cff564bc1f0db2b17"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G2      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G1<a id="abec9c1dd43489b968c9780860bad71bfab0d49b0ffa4753b61465eb29942f838c"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G1_NC<a id="abec9c1dd43489b968c9780860bad71bfadf42ca6f959ddac98d35254c0914af09"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G1      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G0<a id="abec9c1dd43489b968c9780860bad71bfa8f3aaf6805e534003f15c7e878acdf32"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_PREL_G0_NC<a id="abec9c1dd43489b968c9780860bad71bfab793dd2a7b912aeaae778108094a5689"></a></td>
<td class="doxyEnumItemDescription"> (= VK_PREL         | VK_G0      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_LO12<a id="abec9c1dd43489b968c9780860bad71bfaa3e719e2fda5e6446235fedc1024897e"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOT          | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_PAGE<a id="abec9c1dd43489b968c9780860bad71bfa9df90d2efd141370b894bd4749ed184c"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOT          | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_PAGE_LO15<a id="abec9c1dd43489b968c9780860bad71bfa5fbf97669aa58e6ffa919564aabc2f5f"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOT          | VK_LO15    | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_AUTH_LO12<a id="abec9c1dd43489b968c9780860bad71bfa2f76c31f5c93ff69cd59e817abd85223"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOT_AUTH     | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOT_AUTH_PAGE<a id="abec9c1dd43489b968c9780860bad71bfae1c2096bfd2bbfd76a75327f7a830e6b"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOT_AUTH     | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_G2<a id="abec9c1dd43489b968c9780860bad71bfa8f5d53560d98ded247f3bc911c00260d"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_G2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_G1<a id="abec9c1dd43489b968c9780860bad71bfa1ea6131fa4bc346a2285f73b1e3b2b88"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_G1_NC<a id="abec9c1dd43489b968c9780860bad71bfa1ea81fd8999cf2538b39f1e012f4a9cc"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_G1      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_G0<a id="abec9c1dd43489b968c9780860bad71bfa752f95c69e8b43369d83833adb099345"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_G0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_G0_NC<a id="abec9c1dd43489b968c9780860bad71bfab73ae607357b58d9d3de5256d5558284"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_G0      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_HI12<a id="abec9c1dd43489b968c9780860bad71bfad1e341aea3471c4a8356b69bfad7a772"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_HI12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_LO12<a id="abec9c1dd43489b968c9780860bad71bfae976f5dddffeb8a77e5ecc471343842d"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_PAGEOFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_DTPREL_LO12_NC<a id="abec9c1dd43489b968c9780860bad71bfa690cf2259632dd195b29cb7ad0cd16b7"></a></td>
<td class="doxyEnumItemDescription"> (= VK_DTPREL       | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPREL_PAGE<a id="abec9c1dd43489b968c9780860bad71bfa64f45ff3541539f980e5edcdbfbd1a73"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOTTPREL     | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPREL_LO12_NC<a id="abec9c1dd43489b968c9780860bad71bfad5dd2834fe1711d63b1b6c7ab4fdf5e1"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOTTPREL     | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPREL_G1<a id="abec9c1dd43489b968c9780860bad71bfa818d75cf614986328128098bb46084ed"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOTTPREL     | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_GOTTPREL_G0_NC<a id="abec9c1dd43489b968c9780860bad71bfa9c3e5cca2bdd09fc0ecb532f2c5d7e45"></a></td>
<td class="doxyEnumItemDescription"> (= VK_GOTTPREL     | VK_G0      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_G2<a id="abec9c1dd43489b968c9780860bad71bfa4b1b25eea13543bbbe0d904a4776d430"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_G2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_G1<a id="abec9c1dd43489b968c9780860bad71bfa5027a58d31c5e57b7483970eaf6cd602"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_G1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_G1_NC<a id="abec9c1dd43489b968c9780860bad71bfa11bfd951d2f6ec25329b879f8d428fa9"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_G1      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_G0<a id="abec9c1dd43489b968c9780860bad71bfaeb8c93fb135d2775c869861178d11807"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_G0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_G0_NC<a id="abec9c1dd43489b968c9780860bad71bfa6e1d58609fc75b55166830312b91d2df"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_G0      | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_HI12<a id="abec9c1dd43489b968c9780860bad71bfa65b0bb155666aed0ad6a4a61dc4f76b6"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_HI12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_LO12<a id="abec9c1dd43489b968c9780860bad71bfa69a04395c63763644a14a6a929075fb0"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_PAGEOFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TPREL_LO12_NC<a id="abec9c1dd43489b968c9780860bad71bfaa2d3ca49c7f86aedb741b49d223fce16"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TPREL        | VK_PAGEOFF | VK_NC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC_LO12<a id="abec9c1dd43489b968c9780860bad71bfae86e7fb84bad4ed1be1f5772229a8d58"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TLSDESC      | VK_PAGEOFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC_PAGE<a id="abec9c1dd43489b968c9780860bad71bfaa2fd0f1618e78066a208b3ae06037391"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TLSDESC      | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC_AUTH_LO12<a id="abec9c1dd43489b968c9780860bad71bfacf90d92f6c5b8b5972b2631c72eb5dde"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TLSDESC_AUTH | VK_PAGEOFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_TLSDESC_AUTH_PAGE<a id="abec9c1dd43489b968c9780860bad71bfaa433d52bc17bc21ce04f3cf8f409c358"></a></td>
<td class="doxyEnumItemDescription"> (= VK_TLSDESC_AUTH | VK_PAGE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SECREL_LO12<a id="abec9c1dd43489b968c9780860bad71bfaee5e353993b28f25d23e1b76e1b295a2"></a></td>
<td class="doxyEnumItemDescription"> (= VK_SECREL       | VK_PAGEOFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_SECREL_HI12<a id="abec9c1dd43489b968c9780860bad71bfad8bf44f54a45b38024a2cdc10226cb3a"></a></td>
<td class="doxyEnumItemDescription"> (= VK_SECREL       | VK_HI12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_INVALID<a id="abec9c1dd43489b968c9780860bad71bfaaa4c8d42e062c94e8869aed17b89b61a"></a></td>
<td class="doxyEnumItemDescription"> (= 0xfff)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### AArch64MCExpr() {#a26a585c3355b561e0bd7a9e8d3cbed44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64MCExpr::AArch64MCExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a68355545670bc68f6f32c8d00d636fc0">llvm::AArch64AuthMCExpr::classof</a> and <a href="#a84d44e8b0d35d0b19946a50e8229ab86">create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#a2ee670ab9e4208096e0aff88d1a28034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64MCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#ab17d0c21f5ebab570d850a8e8a4ffa9f">getKind</a>, <a href="#aadc269d1f3523366720c8c5d8d382722">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a> and <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>.</p>

</div>
</div>

### findAssociatedFragment() {#a44d1f8b239360ee96cd7a33f384fa21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * AArch64MCExpr::findAssociatedFragment ()</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a0ef0aa1408d6fd0ecb399eb97c5aadc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64MCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#aadc269d1f3523366720c8c5d8d382722">getSubExpr</a>, <a href="#a07e3d0ae8a67b027d48dbb2a51ed6e9a">getSymbolLoc</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa261e5fdfac362b9c39961c5226dbfccf">VK_DTPREL</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa6b76c48acac537ea0f3accd4f946b223">VK_GOTTPREL</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaa1193d791c0127a6f7a86565a3f460bd">VK_TLSDESC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa32da9cfae143cc7c95c2e0f54ca40bcc">VK_TLSDESC_AUTH</a> and <a href="#abec9c1dd43489b968c9780860bad71bfaa3020e9ba5dfa0324318faad507a0a58">VK_TPREL</a>.</p>

</div>
</div>

### getVariantKindName() {#a4c7b303dd646822f22c9b1f6169162b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AArch64MCExpr::getVariantKindName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the variant kind into an ELF-appropriate modifier (e.g.</p>


<p>":got:", ":lo12:").</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>References <a href="#ab17d0c21f5ebab570d850a8e8a4ffa9f">getKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa35474485d868b25489fc57669a9c27f9">VK_ABS_G0</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa65e6d1b5482060081af43ab78352964d">VK_ABS_G0_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa7eb9497609b61ca20e383022f9ab3290">VK_ABS_G0_S</a>, <a href="#abec9c1dd43489b968c9780860bad71bfae40f238af3f6fe589641a720ab4f97a8">VK_ABS_G1</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa1f931e50ae5f4c5f77e050447b2e3320">VK_ABS_G1_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa53f60806897246321227204c69d467c3">VK_ABS_G1_S</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa284689a52a5f79b95b051a057c54fb1e">VK_ABS_G2</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa1089df68239d0e46c2fba2190c4c0eb8">VK_ABS_G2_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa536c18c873600b1e2aba9d9f894e9213">VK_ABS_G2_S</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa963191759d19cf8d90bc0c40435c8cb8">VK_ABS_G3</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaaf6f9676ef24562e98c151543f52efc8">VK_ABS_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa660036640793b7c6285441ebaaec4c6a">VK_ABS_PAGE_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa7df30bfd9a5a56ae922f3597d31363b0">VK_CALL</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa752f95c69e8b43369d83833adb099345">VK_DTPREL_G0</a>, <a href="#abec9c1dd43489b968c9780860bad71bfab73ae607357b58d9d3de5256d5558284">VK_DTPREL_G0_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa1ea6131fa4bc346a2285f73b1e3b2b88">VK_DTPREL_G1</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa1ea81fd8999cf2538b39f1e012f4a9cc">VK_DTPREL_G1_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa8f5d53560d98ded247f3bc911c00260d">VK_DTPREL_G2</a>, <a href="#abec9c1dd43489b968c9780860bad71bfad1e341aea3471c4a8356b69bfad7a772">VK_DTPREL_HI12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfae976f5dddffeb8a77e5ecc471343842d">VK_DTPREL_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa690cf2259632dd195b29cb7ad0cd16b7">VK_DTPREL_LO12_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa96518ec6ca1da559ff4a909126b88060">VK_GOT</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa9ec4c589014eb66893073ac3083a2670">VK_GOT_AUTH</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa2f76c31f5c93ff69cd59e817abd85223">VK_GOT_AUTH_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfae1c2096bfd2bbfd76a75327f7a830e6b">VK_GOT_AUTH_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaa3e719e2fda5e6446235fedc1024897e">VK_GOT_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa9df90d2efd141370b894bd4749ed184c">VK_GOT_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa5fbf97669aa58e6ffa919564aabc2f5f">VK_GOT_PAGE_LO15</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa6b76c48acac537ea0f3accd4f946b223">VK_GOTTPREL</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa9c3e5cca2bdd09fc0ecb532f2c5d7e45">VK_GOTTPREL_G0_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa818d75cf614986328128098bb46084ed">VK_GOTTPREL_G1</a>, <a href="#abec9c1dd43489b968c9780860bad71bfad5dd2834fe1711d63b1b6c7ab4fdf5e1">VK_GOTTPREL_LO12_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa64f45ff3541539f980e5edcdbfbd1a73">VK_GOTTPREL_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfac273d7a8ebcef5784a4904ffe145aefe">VK_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa8f3aaf6805e534003f15c7e878acdf32">VK_PREL_G0</a>, <a href="#abec9c1dd43489b968c9780860bad71bfab793dd2a7b912aeaae778108094a5689">VK_PREL_G0_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfab0d49b0ffa4753b61465eb29942f838c">VK_PREL_G1</a>, <a href="#abec9c1dd43489b968c9780860bad71bfadf42ca6f959ddac98d35254c0914af09">VK_PREL_G1_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfae308678726c12af491f9647e76f3f1b9">VK_PREL_G2</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa432b91e82080f70cff564bc1f0db2b17">VK_PREL_G2_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa9a4ed17656f61247e51858d2f8d9203d">VK_PREL_G3</a>, <a href="#abec9c1dd43489b968c9780860bad71bfad8bf44f54a45b38024a2cdc10226cb3a">VK_SECREL_HI12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaee5e353993b28f25d23e1b76e1b295a2">VK_SECREL_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaa1193d791c0127a6f7a86565a3f460bd">VK_TLSDESC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa32da9cfae143cc7c95c2e0f54ca40bcc">VK_TLSDESC_AUTH</a>, <a href="#abec9c1dd43489b968c9780860bad71bfacf90d92f6c5b8b5972b2631c72eb5dde">VK_TLSDESC_AUTH_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaa433d52bc17bc21ce04f3cf8f409c358">VK_TLSDESC_AUTH_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfae86e7fb84bad4ed1be1f5772229a8d58">VK_TLSDESC_LO12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaa2fd0f1618e78066a208b3ae06037391">VK_TLSDESC_PAGE</a>, <a href="#abec9c1dd43489b968c9780860bad71bfaeb8c93fb135d2775c869861178d11807">VK_TPREL_G0</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa6e1d58609fc75b55166830312b91d2df">VK_TPREL_G0_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa5027a58d31c5e57b7483970eaf6cd602">VK_TPREL_G1</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa11bfd951d2f6ec25329b879f8d428fa9">VK_TPREL_G1_NC</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa4b1b25eea13543bbbe0d904a4776d430">VK_TPREL_G2</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa65b0bb155666aed0ad6a4a61dc4f76b6">VK_TPREL_HI12</a>, <a href="#abec9c1dd43489b968c9780860bad71bfa69a04395c63763644a14a6a929075fb0">VK_TPREL_LO12</a> and <a href="#abec9c1dd43489b968c9780860bad71bfaa2d3ca49c7f86aedb741b49d223fce16">VK_TPREL_LO12_NC</a>.</p>


<p>Referenced by <a href="#ab7d76f738ef1a55d72a3a429c8eab475">printImpl</a>.</p>

</div>
</div>

### printImpl() {#ab7d76f738ef1a55d72a3a429c8eab475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64MCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>Reference <a href="#a4c7b303dd646822f22c9b1f6169162b4">getVariantKindName</a>.</p>

</div>
</div>

### visitUsedExpr() {#a5979780bec8026d8fd6cb8bf024b3086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64MCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>References <a href="#aadc269d1f3523366720c8c5d8d382722">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a3ad34eaeebe09350fbc7d251a89ecad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AArch64MCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>

</div>
</div>

### Kind {#a415b7d11d0dc2d887b95b66ea6ece596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::AArch64MCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8865f9c5ef2c6882f77df724f2bbce77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64MCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#a84d44e8b0d35d0b19946a50e8229ab86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64MCExpr * AArch64MCExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a>.</p>


<p>Reference <a href="#a26a585c3355b561e0bd7a9e8d3cbed44">AArch64MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aac53de41a4af1d12db6ce7d5a0cf6678">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## VariantKind information extractors.

### getAddressFrag {#a7dfd432f33b5e5ff4114b9be04a2b25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AArch64MCExpr::getAddressFrag (<a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a> Kind)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Reference <a href="#abec9c1dd43489b968c9780860bad71bfac023b84e4a49df08de7abf40646e9024">VK_AddressFragBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a85d0607dba50e8b55a836f53bc8184ca">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getSymbolLoc {#a07e3d0ae8a67b027d48dbb2a51ed6e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AArch64MCExpr::getSymbolLoc (<a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a> Kind)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Reference <a href="#abec9c1dd43489b968c9780860bad71bfa69094d51626dc25699fb27be5e23d119">VK_SymLocBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#a2815f5697eeeba8167e7b5fe3a15646c">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::applyFixup</a>, <a href="#a0ef0aa1408d6fd0ecb399eb97c5aadc5">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a85d0607dba50e8b55a836f53bc8184ca">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::getRelocType</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffobjectwriter-cpp-/aarch64wincoffobjectwriter/#ac4bbe9cdad8b662d3467e8cb63d87b74">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### isNotChecked {#a5a2b5e4ba4c1ccd001580fc8181e52eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64MCExpr::isNotChecked (<a href="#abec9c1dd43489b968c9780860bad71bf">VariantKind</a> Kind)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Reference <a href="#abec9c1dd43489b968c9780860bad71bfacfebe394a2b06edc4ddc5e96f6295776">VK_NC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a85d0607dba50e8b55a836f53bc8184ca">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getKind {#ab17d0c21f5ebab570d850a8e8a4ffa9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AArch64MCExpr::getKind ()</td>
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

<p>Get the kind of this expression.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="#a2ee670ab9e4208096e0aff88d1a28034">evaluateAsRelocatableImpl</a>, <a href="#a4c7b303dd646822f22c9b1f6169162b4">getVariantKindName</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a519328137ea7edad0cf2db58d4e810fd">llvm::AArch64AuthMCExpr::hasAddressDiversity</a>.</p>

</div>
</div>

### getSubExpr {#aadc269d1f3523366720c8c5d8d382722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::AArch64MCExpr::getSubExpr ()</td>
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

<p>Get the expression this modifier applies to.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="#a2ee670ab9e4208096e0aff88d1a28034">evaluateAsRelocatableImpl</a>, <a href="#a0ef0aa1408d6fd0ecb399eb97c5aadc5">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#ac31114afe8ec5070ba99a22c6a1cd75d">llvm::AArch64AuthMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a93caf33eeff28bfb622085687c51231c">llvm::AArch64AuthMCExpr::visitUsedExpr</a> and <a href="#a5979780bec8026d8fd6cb8bf024b3086">visitUsedExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp">AArch64MCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-h">AArch64MCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
