---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskymcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CSKYMCExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::CSKYMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">Target/CSKY/MCTargetDesc/CSKYMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63da743bb8f09ed354f85a73c5ccebe">CSKYMCExpr</a> (VariantKind Kind, const MCExpr *Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2988ac0d4593937162372c8b40a7d54">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7002ae048cb2d37863aabccc80c3a8">getSubExpr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3994a2f853301c4b9d8e07fbe8882ec3">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cee463d58774d5fade0dce5de3b86e6">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a627b3cf30a4dc300e6a3c2b445f1d258">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee5ef0c182a3313754792e18ebcec90">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a34e306ad0455003f3be3efae9930f4">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b56be4b62b982fb58545a0230b86b34">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c630b56fab620771e6c94bbdf41f28">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr">CSKYMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518604e41db2d171b48aca08cf75f8c1">create</a> (const MCExpr *Expr, VariantKind Kind, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8f83e26f9e04d078a342b764e574ea">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe374453647c968a5b6e672904c644bb">getVariantKindName</a> (VariantKind Kind)</td>
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


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#a93a07cb47b5fa9cdb2cc05126cd3d56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::CSKYMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_CSKY_None<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da9651ea71fd4490018e90fc7093c586b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_ADDR<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da00b43daca1c50769fde2954c18a6a08d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_ADDR_HI16<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da4159132312b3202f8f961bd9c6c260c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_ADDR_LO16<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da2018b03ba284ae306c036109a686d78e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_PCREL<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da43a1824053e4748bbf5d03dc680b35a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_GOT<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da6f6264903a5cd681bef075a10d80830c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_GOT_IMM18_BY4<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da36ee0d98c24a4600f13f214ba4018c8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_GOTPC<a id="a93a07cb47b5fa9cdb2cc05126cd3d56dab1b698cbe7df1349a4dd7b50bc879c59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_GOTOFF<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da459851e1e27ad13079a564826c441637"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_PLT<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da69348b1cbd18fce5aff9db7f91d273b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_PLT_IMM18_BY4<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da346b51ddce5a12d83799e070e7f6ad4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_TLSIE<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_TLSLE<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_TLSGD<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_TLSLDO<a id="a93a07cb47b5fa9cdb2cc05126cd3d56dafea681928cdde2355e1b87f6ed63761b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_TLSLDM<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da6bb8f22442c3370bcba69b73a07fdc21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_CSKY_Invalid<a id="a93a07cb47b5fa9cdb2cc05126cd3d56da66fb2f24f44a694e25256f7d90a845c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### CSKYMCExpr() {#af63da743bb8f09ed354f85a73c5ccebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CSKYMCExpr::CSKYMCExpr (<a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#a3cee463d58774d5fade0dce5de3b86e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#ae2988ac0d4593937162372c8b40a7d54">getKind</a>, <a href="#a3e7002ae048cb2d37863aabccc80c3a8">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da6f6264903a5cd681bef075a10d80830c">VK_CSKY_GOT</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da36ee0d98c24a4600f13f214ba4018c8a">VK_CSKY_GOT_IMM18_BY4</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da459851e1e27ad13079a564826c441637">VK_CSKY_GOTOFF</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56dab1b698cbe7df1349a4dd7b50bc879c59">VK_CSKY_GOTPC</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da69348b1cbd18fce5aff9db7f91d273b9">VK_CSKY_PLT</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da346b51ddce5a12d83799e070e7f6ad4e">VK_CSKY_PLT_IMM18_BY4</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481">VK_CSKY_TLSGD</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95">VK_CSKY_TLSIE</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da6bb8f22442c3370bcba69b73a07fdc21">VK_CSKY_TLSLDM</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56dafea681928cdde2355e1b87f6ed63761b">VK_CSKY_TLSLDO</a> and <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30">VK_CSKY_TLSLE</a>.</p>

</div>
</div>

### findAssociatedFragment() {#aeee5ef0c182a3313754792e18ebcec90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::CSKYMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a3e7002ae048cb2d37863aabccc80c3a8">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a2a34e306ad0455003f3be3efae9930f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#ae2988ac0d4593937162372c8b40a7d54">getKind</a>, <a href="#a3e7002ae048cb2d37863aabccc80c3a8">getSubExpr</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481">VK_CSKY_TLSGD</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95">VK_CSKY_TLSIE</a> and <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30">VK_CSKY_TLSLE</a>.</p>

</div>
</div>

### getKind() {#ae2988ac0d4593937162372c8b40a7d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::CSKYMCExpr::getKind ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="#a3cee463d58774d5fade0dce5de3b86e6">evaluateAsRelocatableImpl</a>, <a href="#a2a34e306ad0455003f3be3efae9930f4">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a9c29d5d248e6c2e091dd022e206068f8">llvm::CSKYMCCodeEmitter::getTargetFixup</a> and <a href="#a3994a2f853301c4b9d8e07fbe8882ec3">printImpl</a>.</p>

</div>
</div>

### getSubExpr() {#a3e7002ae048cb2d37863aabccc80c3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::CSKYMCExpr::getSubExpr ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="#a3cee463d58774d5fade0dce5de3b86e6">evaluateAsRelocatableImpl</a>, <a href="#aeee5ef0c182a3313754792e18ebcec90">findAssociatedFragment</a>, <a href="#a2a34e306ad0455003f3be3efae9930f4">fixELFSymbolsInTLSFixups</a> and <a href="#a627b3cf30a4dc300e6a3c2b445f1d258">visitUsedExpr</a>.</p>

</div>
</div>

### printImpl() {#a3994a2f853301c4b9d8e07fbe8882ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>References <a href="#ae2988ac0d4593937162372c8b40a7d54">getKind</a> and <a href="#abe374453647c968a5b6e672904c644bb">getVariantKindName</a>.</p>

</div>
</div>

### visitUsedExpr() {#a627b3cf30a4dc300e6a3c2b445f1d258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>References <a href="#a3e7002ae048cb2d37863aabccc80c3a8">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a78c630b56fab620771e6c94bbdf41f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::CSKYMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a1b56be4b62b982fb58545a0230b86b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::CSKYMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8b8f83e26f9e04d078a342b764e574ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#a518604e41db2d171b48aca08cf75f8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CSKYMCExpr * CSKYMCExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a> and <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#aab3177d726a52bd1f3a26e580f6c4eda">llvm::CSKYMCInstLower::lowerSymbolOperand</a>.</p>

</div>
</div>

### getVariantKindName() {#abe374453647c968a5b6e672904c644bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef CSKYMCExpr::getVariantKindName (<a href="#a93a07cb47b5fa9cdb2cc05126cd3d56d">VariantKind</a> Kind)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da00b43daca1c50769fde2954c18a6a08d">VK_CSKY_ADDR</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da4159132312b3202f8f961bd9c6c260c1">VK_CSKY_ADDR_HI16</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da2018b03ba284ae306c036109a686d78e">VK_CSKY_ADDR_LO16</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da6f6264903a5cd681bef075a10d80830c">VK_CSKY_GOT</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da36ee0d98c24a4600f13f214ba4018c8a">VK_CSKY_GOT_IMM18_BY4</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da459851e1e27ad13079a564826c441637">VK_CSKY_GOTOFF</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56dab1b698cbe7df1349a4dd7b50bc879c59">VK_CSKY_GOTPC</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da9651ea71fd4490018e90fc7093c586b4">VK_CSKY_None</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da69348b1cbd18fce5aff9db7f91d273b9">VK_CSKY_PLT</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da346b51ddce5a12d83799e070e7f6ad4e">VK_CSKY_PLT_IMM18_BY4</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481">VK_CSKY_TLSGD</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95">VK_CSKY_TLSIE</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da6bb8f22442c3370bcba69b73a07fdc21">VK_CSKY_TLSLDM</a>, <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56dafea681928cdde2355e1b87f6ed63761b">VK_CSKY_TLSLDO</a> and <a href="#a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30">VK_CSKY_TLSLE</a>.</p>


<p>Referenced by <a href="#a3994a2f853301c4b9d8e07fbe8882ec3">printImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp">CSKYMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">CSKYMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
