---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loongarchmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoongArchMCExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LoongArchMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">Target/LoongArch/MCTargetDesc/LoongArchMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#a86a435759a1b631e4b292966be3bed3f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e177369b5c9319fd4ec6fe587fe850d">LoongArchMCExpr</a> (const MCExpr *Expr, VariantKind Kind, bool Hint)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf4b498b59667ac2ef8028f56fe51e1">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59900b7f7675f6072424c1cd1243240c">getSubExpr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4dfc23aafdbe1c23d8dfd2d883ea412">getRelaxHint</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bffc7de58b06151f639047c88074277">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cae3779c4cf6161a29b19196c789c5">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ce48054f6c130aef1bbe41be25c289">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13d0f778dbd80fe988df361238268f0">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c19ad7e6c598eb57a215a524a9d51bd">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f77d6a00e355f8c88af2624d1ca80f7">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce3237e178693cb4dd733967098ff76">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ce825a8838586324ad09e50aa421e4">RelaxHint</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr">LoongArchMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ef99fc9b815bad6647b7ee1c5b4161">create</a> (const MCExpr *Expr, VariantKind Kind, MCContext &amp;Ctx, bool Hint=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae350daa28f46ae17b589721b3e17758c">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb1e17682ce7a3dd2ed4eba0d7994fa">getVariantKindName</a> (VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66cc3e0b06526eb09333e4c407425c2a">getVariantKindForName</a> (StringRef name)</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#a86a435759a1b631e4b292966be3bed3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoongArchMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_LoongArch_None<a id="a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_CALL<a id="a86a435759a1b631e4b292966be3bed3fa1966ed6149cfdacca4a00fe4c47c84b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_CALL_PLT<a id="a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_B16<a id="a86a435759a1b631e4b292966be3bed3fa9d404502c90b9f06080fc97fe12110ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_B21<a id="a86a435759a1b631e4b292966be3bed3fa898fbeff95eaf12a8ea019722e6d0d3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_B26<a id="a86a435759a1b631e4b292966be3bed3fa013d74af246487fe165cb00b45c3a09d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_ABS_HI20<a id="a86a435759a1b631e4b292966be3bed3fa203b677b6d91643eee403c74f5370303"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_ABS_LO12<a id="a86a435759a1b631e4b292966be3bed3fa4b6341fa13f1dc1e47baacdcf69e8c41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_ABS64_LO20<a id="a86a435759a1b631e4b292966be3bed3fafa717809c42ea7a735c4ba7cd7cc9b0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_ABS64_HI12<a id="a86a435759a1b631e4b292966be3bed3fa5a1b61e6eda817ed9e2b3cd6056990b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_PCALA_HI20<a id="a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_PCALA_LO12<a id="a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_PCALA64_LO20<a id="a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_PCALA64_HI12<a id="a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT_PC_HI20<a id="a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT_PC_LO12<a id="a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT64_PC_LO20<a id="a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT64_PC_HI12<a id="a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT_HI20<a id="a86a435759a1b631e4b292966be3bed3fa2968ccf12fee2fe568d6673d83632eba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT_LO12<a id="a86a435759a1b631e4b292966be3bed3fa88122daedcca01675ef8906b58578b5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT64_LO20<a id="a86a435759a1b631e4b292966be3bed3fac47fcc37d78a9b3eec4e00531ab622a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_GOT64_HI12<a id="a86a435759a1b631e4b292966be3bed3fa311598ad7d07257815082808e9ac1fdf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE_HI20<a id="a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE_LO12<a id="a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE64_LO20<a id="a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE64_HI12<a id="a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE_PC_HI20<a id="a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE_PC_LO12<a id="a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE64_PC_LO20<a id="a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE64_PC_HI12<a id="a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE_HI20<a id="a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE_LO12<a id="a86a435759a1b631e4b292966be3bed3faa4ed58231825db10243f5d7200bf8d09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE64_LO20<a id="a86a435759a1b631e4b292966be3bed3fa6d762b588d0bfd42e24afb9b4943c710"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_IE64_HI12<a id="a86a435759a1b631e4b292966be3bed3fa5ed5ac4f2e54048bf799310defa548ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LD_PC_HI20<a id="a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LD_HI20<a id="a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_GD_PC_HI20<a id="a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_GD_HI20<a id="a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_CALL36<a id="a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_PC_HI20<a id="a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_PC_LO12<a id="a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC64_PC_LO20<a id="a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC64_PC_HI12<a id="a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_HI20<a id="a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_LO12<a id="a86a435759a1b631e4b292966be3bed3fa8f6f6db2e883c43aeade25c0437dbed0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC64_LO20<a id="a86a435759a1b631e4b292966be3bed3fac54f5d108b9b10b10dbde7fcc8360a27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC64_HI12<a id="a86a435759a1b631e4b292966be3bed3fa33f37781402f6b86afbef475c4161894"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_LD<a id="a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_CALL<a id="a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE_HI20_R<a id="a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE_ADD_R<a id="a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LE_LO12_R<a id="a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_PCREL20_S2<a id="a86a435759a1b631e4b292966be3bed3fa1c6d9ba2e4a6e6a8fff0f16a0e390cbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_LD_PCREL20_S2<a id="a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_GD_PCREL20_S2<a id="a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_TLS_DESC_PCREL20_S2<a id="a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_LoongArch_Invalid<a id="a86a435759a1b631e4b292966be3bed3fa00135481912986d64bbd2a939fd40f53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LoongArchMCExpr() {#a6e177369b5c9319fd4ec6fe587fe850d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoongArchMCExpr::LoongArchMCExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a> Kind, bool Hint)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#af2cae3779c4cf6161a29b19196c789c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#a4bf4b498b59667ac2ef8028f56fe51e1">getKind</a>, <a href="#a59900b7f7675f6072424c1cd1243240c">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a> and <a href="#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">VK_LoongArch_None</a>.</p>

</div>
</div>

### findAssociatedFragment() {#af13d0f778dbd80fe988df361238268f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::LoongArchMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a59900b7f7675f6072424c1cd1243240c">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a9c19ad7e6c598eb57a215a524a9d51bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#a4bf4b498b59667ac2ef8028f56fe51e1">getKind</a>, <a href="#a59900b7f7675f6072424c1cd1243240c">getSubExpr</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62">VK_LoongArch_TLS_DESC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef">VK_LoongArch_TLS_DESC_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1">VK_LoongArch_TLS_GD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb">VK_LoongArch_TLS_GD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c">VK_LoongArch_TLS_IE_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">VK_LoongArch_TLS_IE_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3">VK_LoongArch_TLS_LD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">VK_LoongArch_TLS_LD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547">VK_LoongArch_TLS_LD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">VK_LoongArch_TLS_LE_HI20</a> and <a href="#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">VK_LoongArch_TLS_LE_HI20_R</a>.</p>

</div>
</div>

### getKind() {#a4bf4b498b59667ac2ef8028f56fe51e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::LoongArchMCExpr::getKind ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<p>Referenced by <a href="#af2cae3779c4cf6161a29b19196c789c5">evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="#a9c19ad7e6c598eb57a215a524a9d51bd">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a> and <a href="#a9bffc7de58b06151f639047c88074277">printImpl</a>.</p>

</div>
</div>

### getRelaxHint() {#ae4dfc23aafdbe1c23d8dfd2d883ea412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchMCExpr::getRelaxHint ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a>.</p>

</div>
</div>

### getSubExpr() {#a59900b7f7675f6072424c1cd1243240c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::LoongArchMCExpr::getSubExpr ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<p>Referenced by <a href="#af2cae3779c4cf6161a29b19196c789c5">evaluateAsRelocatableImpl</a>, <a href="#af13d0f778dbd80fe988df361238268f0">findAssociatedFragment</a>, <a href="#a9c19ad7e6c598eb57a215a524a9d51bd">fixELFSymbolsInTLSFixups</a> and <a href="#a88ce48054f6c130aef1bbe41be25c289">visitUsedExpr</a>.</p>

</div>
</div>

### printImpl() {#a9bffc7de58b06151f639047c88074277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="#a4bf4b498b59667ac2ef8028f56fe51e1">getKind</a>, <a href="#aaeb1e17682ce7a3dd2ed4eba0d7994fa">getVariantKindName</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa1966ed6149cfdacca4a00fe4c47c84b2">VK_LoongArch_CALL</a> and <a href="#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">VK_LoongArch_None</a>.</p>

</div>
</div>

### visitUsedExpr() {#a88ce48054f6c130aef1bbe41be25c289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="#a59900b7f7675f6072424c1cd1243240c">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a8f77d6a00e355f8c88af2624d1ca80f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::LoongArchMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a8ce3237e178693cb4dd733967098ff76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::LoongArchMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>

</div>
</div>

### RelaxHint {#af2ce825a8838586324ad09e50aa421e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::LoongArchMCExpr::RelaxHint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ae350daa28f46ae17b589721b3e17758c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#aa9ef99fc9b815bad6647b7ee1c5b4161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoongArchMCExpr * LoongArchMCExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool Hint=false)</td>
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



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>.</p>

</div>
</div>

### getVariantKindForName() {#a66cc3e0b06526eb09333e4c407425c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchMCExpr::VariantKind LoongArchMCExpr::getVariantKindForName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5a1b61e6eda817ed9e2b3cd6056990b1">VK_LoongArch_ABS64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fafa717809c42ea7a735c4ba7cd7cc9b0d">VK_LoongArch_ABS64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa203b677b6d91643eee403c74f5370303">VK_LoongArch_ABS_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa4b6341fa13f1dc1e47baacdcf69e8c41">VK_LoongArch_ABS_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa9d404502c90b9f06080fc97fe12110ae">VK_LoongArch_B16</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa898fbeff95eaf12a8ea019722e6d0d3e">VK_LoongArch_B21</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa013d74af246487fe165cb00b45c3a09d">VK_LoongArch_B26</a>, <a href="#a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab">VK_LoongArch_CALL36</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5">VK_LoongArch_CALL_PLT</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa311598ad7d07257815082808e9ac1fdf">VK_LoongArch_GOT64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac47fcc37d78a9b3eec4e00531ab622a7">VK_LoongArch_GOT64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554">VK_LoongArch_GOT64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a">VK_LoongArch_GOT64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa2968ccf12fee2fe568d6673d83632eba">VK_LoongArch_GOT_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa88122daedcca01675ef8906b58578b5c">VK_LoongArch_GOT_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55">VK_LoongArch_GOT_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">VK_LoongArch_GOT_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa00135481912986d64bbd2a939fd40f53">VK_LoongArch_Invalid</a>, <a href="#a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6">VK_LoongArch_PCALA64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904">VK_LoongArch_PCALA64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664">VK_LoongArch_PCALA_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">VK_LoongArch_PCALA_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa1c6d9ba2e4a6e6a8fff0f16a0e390cbb">VK_LoongArch_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa33f37781402f6b86afbef475c4161894">VK_LoongArch_TLS_DESC64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac54f5d108b9b10b10dbde7fcc8360a27">VK_LoongArch_TLS_DESC64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380">VK_LoongArch_TLS_DESC64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968">VK_LoongArch_TLS_DESC64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7">VK_LoongArch_TLS_DESC_CALL</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62">VK_LoongArch_TLS_DESC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b">VK_LoongArch_TLS_DESC_LD</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa8f6f6db2e883c43aeade25c0437dbed0">VK_LoongArch_TLS_DESC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f">VK_LoongArch_TLS_DESC_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef">VK_LoongArch_TLS_DESC_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1">VK_LoongArch_TLS_GD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb">VK_LoongArch_TLS_GD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5ed5ac4f2e54048bf799310defa548ba">VK_LoongArch_TLS_IE64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa6d762b588d0bfd42e24afb9b4943c710">VK_LoongArch_TLS_IE64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1">VK_LoongArch_TLS_IE64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b">VK_LoongArch_TLS_IE64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c">VK_LoongArch_TLS_IE_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa4ed58231825db10243f5d7200bf8d09">VK_LoongArch_TLS_IE_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">VK_LoongArch_TLS_IE_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">VK_LoongArch_TLS_IE_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3">VK_LoongArch_TLS_LD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">VK_LoongArch_TLS_LD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547">VK_LoongArch_TLS_LD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768">VK_LoongArch_TLS_LE64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10">VK_LoongArch_TLS_LE64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">VK_LoongArch_TLS_LE_ADD_R</a>, <a href="#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">VK_LoongArch_TLS_LE_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">VK_LoongArch_TLS_LE_HI20_R</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252">VK_LoongArch_TLS_LE_LO12</a> and <a href="#a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290">VK_LoongArch_TLS_LE_LO12_R</a>.</p>

</div>
</div>

### getVariantKindName() {#aaeb1e17682ce7a3dd2ed4eba0d7994fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LoongArchMCExpr::getVariantKindName (<a href="#a86a435759a1b631e4b292966be3bed3f">VariantKind</a> Kind)</td>
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



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5a1b61e6eda817ed9e2b3cd6056990b1">VK_LoongArch_ABS64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fafa717809c42ea7a735c4ba7cd7cc9b0d">VK_LoongArch_ABS64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa203b677b6d91643eee403c74f5370303">VK_LoongArch_ABS_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa4b6341fa13f1dc1e47baacdcf69e8c41">VK_LoongArch_ABS_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa9d404502c90b9f06080fc97fe12110ae">VK_LoongArch_B16</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa898fbeff95eaf12a8ea019722e6d0d3e">VK_LoongArch_B21</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa013d74af246487fe165cb00b45c3a09d">VK_LoongArch_B26</a>, <a href="#a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab">VK_LoongArch_CALL36</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5">VK_LoongArch_CALL_PLT</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa311598ad7d07257815082808e9ac1fdf">VK_LoongArch_GOT64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac47fcc37d78a9b3eec4e00531ab622a7">VK_LoongArch_GOT64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554">VK_LoongArch_GOT64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a">VK_LoongArch_GOT64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa2968ccf12fee2fe568d6673d83632eba">VK_LoongArch_GOT_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa88122daedcca01675ef8906b58578b5c">VK_LoongArch_GOT_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55">VK_LoongArch_GOT_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">VK_LoongArch_GOT_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6">VK_LoongArch_PCALA64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904">VK_LoongArch_PCALA64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664">VK_LoongArch_PCALA_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">VK_LoongArch_PCALA_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa1c6d9ba2e4a6e6a8fff0f16a0e390cbb">VK_LoongArch_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa33f37781402f6b86afbef475c4161894">VK_LoongArch_TLS_DESC64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac54f5d108b9b10b10dbde7fcc8360a27">VK_LoongArch_TLS_DESC64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380">VK_LoongArch_TLS_DESC64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968">VK_LoongArch_TLS_DESC64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7">VK_LoongArch_TLS_DESC_CALL</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62">VK_LoongArch_TLS_DESC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b">VK_LoongArch_TLS_DESC_LD</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa8f6f6db2e883c43aeade25c0437dbed0">VK_LoongArch_TLS_DESC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f">VK_LoongArch_TLS_DESC_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef">VK_LoongArch_TLS_DESC_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1">VK_LoongArch_TLS_GD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb">VK_LoongArch_TLS_GD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5ed5ac4f2e54048bf799310defa548ba">VK_LoongArch_TLS_IE64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa6d762b588d0bfd42e24afb9b4943c710">VK_LoongArch_TLS_IE64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1">VK_LoongArch_TLS_IE64_PC_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b">VK_LoongArch_TLS_IE64_PC_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c">VK_LoongArch_TLS_IE_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa4ed58231825db10243f5d7200bf8d09">VK_LoongArch_TLS_IE_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">VK_LoongArch_TLS_IE_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">VK_LoongArch_TLS_IE_PC_LO12</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3">VK_LoongArch_TLS_LD_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">VK_LoongArch_TLS_LD_PC_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547">VK_LoongArch_TLS_LD_PCREL20_S2</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768">VK_LoongArch_TLS_LE64_HI12</a>, <a href="#a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10">VK_LoongArch_TLS_LE64_LO20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">VK_LoongArch_TLS_LE_ADD_R</a>, <a href="#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">VK_LoongArch_TLS_LE_HI20</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">VK_LoongArch_TLS_LE_HI20_R</a>, <a href="#a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252">VK_LoongArch_TLS_LE_LO12</a> and <a href="#a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290">VK_LoongArch_TLS_LE_LO12_R</a>.</p>


<p>Referenced by <a href="#a9bffc7de58b06151f639047c88074277">printImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp">LoongArchMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-h">LoongArchMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
