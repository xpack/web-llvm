---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsMCExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">Target/Mips/MCTargetDesc/MipsMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MipsExprKind { <a href="#ab8bb54401d51992af131ce600f468f70">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2284e41a9af44f8bb5a8a6bb0efd9c6b">MipsMCExpr</a> (MipsExprKind Kind, const MCExpr *Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8321e3415e010ba4cb28d4317332603e">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of this expression. <a href="#a8321e3415e010ba4cb28d4317332603e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the child of this expression. <a href="#a40f77c0873c95fd1652e5769b991bd55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa879516d2836ed2f4f6bf40d11489f94">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6611e2e9cb3a7eea00a5150360c2e98">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbef3f35fd05b8f0929d5e9d00abd8f8">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0126936c6207ecb570fedf6fbeb92419">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e3a96e4ef966b2497116da4c6911be">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68220d5cd03f3e38fd0949937c7e6ac">isGpOff</a> (MipsExprKind &amp;Kind) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5e849bf9c474c4c4baf1f35fefc667">isGpOff</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cea550e158bd5d2a5bfdc140fc2fa0">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae160c2132b6e7b7bddf1f1a0532a3267">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr">MipsMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0087423de073ff81b2249bdea54eab40">create</a> (MipsExprKind Kind, const MCExpr *Expr, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr">MipsMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29afc8458b5cc153a5cb5e1e8f0252f">createGpOff</a> (MipsExprKind Kind, const MCExpr *Expr, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6f8e5eca9341fc2b71da20283eda03">classof</a> (const MCExpr *E)</td>
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


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MipsExprKind {#ab8bb54401d51992af131ce600f468f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsMCExpr::MipsExprKind </td>
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
<td class="doxyEnumItemName">MEK_None<a id="ab8bb54401d51992af131ce600f468f70a127b4af2e6597a11a2271486307fdac1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_CALL_HI16<a id="ab8bb54401d51992af131ce600f468f70a257902481821ba5b40f837390279b03a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_CALL_LO16<a id="ab8bb54401d51992af131ce600f468f70a649881b3e57f4661dd4c80bee4a4b90a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_DTPREL<a id="ab8bb54401d51992af131ce600f468f70a84706a1c917c45b0668fbdbe8b4dd793"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_DTPREL_HI<a id="ab8bb54401d51992af131ce600f468f70a89d1a8e66789c4eae95877553dbc1565"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_DTPREL_LO<a id="ab8bb54401d51992af131ce600f468f70a9d0a302a9152729f52460e636c7fb44e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT<a id="ab8bb54401d51992af131ce600f468f70a386aafa447bee675e328e88e9470957e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOTTPREL<a id="ab8bb54401d51992af131ce600f468f70a79bd0912db4f9ad29c7e7e172a5c805d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_CALL<a id="ab8bb54401d51992af131ce600f468f70a0453b77229668594037b194c19c8e8ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_DISP<a id="ab8bb54401d51992af131ce600f468f70a0ae33921dce666ee7adef46268bf9f2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_HI16<a id="ab8bb54401d51992af131ce600f468f70a0a7f1b614b8ffd488e6089fbe10a316f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_LO16<a id="ab8bb54401d51992af131ce600f468f70af6e3d6f3b62ea7d5e97a5e8ff6ccf054"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_OFST<a id="ab8bb54401d51992af131ce600f468f70ab986b26f0ebeb0499f36b0d82fe639d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GOT_PAGE<a id="ab8bb54401d51992af131ce600f468f70adcc3e0803f2bff3ce95d8ff86fb0f550"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_GPREL<a id="ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_HI<a id="ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_HIGHER<a id="ab8bb54401d51992af131ce600f468f70ad184d95272d90612c94695f1d1f42fcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_HIGHEST<a id="ab8bb54401d51992af131ce600f468f70aeb7b57e94a471eb90a2905c65b60ce47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_LO<a id="ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_NEG<a id="ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_PCREL_HI16<a id="ab8bb54401d51992af131ce600f468f70adc7eb8cb308edcc2b568b4a737a6174c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_PCREL_LO16<a id="ab8bb54401d51992af131ce600f468f70ac16da9fec94c6aaee788e43d1788bfea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_TLSGD<a id="ab8bb54401d51992af131ce600f468f70abe74e919e6de05ae1af1093c96928e29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_TLSLDM<a id="ab8bb54401d51992af131ce600f468f70a89674453ca1f94bb72d4e9dca3e1e771"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_TPREL_HI<a id="ab8bb54401d51992af131ce600f468f70a855ac563dd866b584fe34b8d58eb4546"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_TPREL_LO<a id="ab8bb54401d51992af131ce600f468f70a8c4e3452b4ab8d6f1b9bdb42ecd075f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEK_Special<a id="ab8bb54401d51992af131ce600f468f70aa2356920f62894ef31881aff40beabcb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MipsMCExpr() {#a2284e41a9af44f8bb5a8a6bb0efd9c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsMCExpr::MipsMCExpr (<a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#ae6611e2e9cb3a7eea00a5150360c2e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#a8321e3415e010ba4cb28d4317332603e">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a48eebfa5f9f069075bc6412fd4371c7b">llvm::MCValue::getRefKind</a>, <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#af9a96a0245ea7da2779a023ab07829e4">llvm::MCValue::isAbsolute</a>, <a href="#abc5e849bf9c474c4c4baf1f35fefc667">isGpOff</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab8bb54401d51992af131ce600f468f70a257902481821ba5b40f837390279b03a">MEK_CALL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a649881b3e57f4661dd4c80bee4a4b90a">MEK_CALL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a84706a1c917c45b0668fbdbe8b4dd793">MEK_DTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89d1a8e66789c4eae95877553dbc1565">MEK_DTPREL_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70a9d0a302a9152729f52460e636c7fb44e">MEK_DTPREL_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a386aafa447bee675e328e88e9470957e">MEK_GOT</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0453b77229668594037b194c19c8e8ab">MEK_GOT_CALL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0ae33921dce666ee7adef46268bf9f2f">MEK_GOT_DISP</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0a7f1b614b8ffd488e6089fbe10a316f">MEK_GOT_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70af6e3d6f3b62ea7d5e97a5e8ff6ccf054">MEK_GOT_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ab986b26f0ebeb0499f36b0d82fe639d7">MEK_GOT_OFST</a>, <a href="#ab8bb54401d51992af131ce600f468f70adcc3e0803f2bff3ce95d8ff86fb0f550">MEK_GOT_PAGE</a>, <a href="#ab8bb54401d51992af131ce600f468f70a79bd0912db4f9ad29c7e7e172a5c805d">MEK_GOTTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">MEK_GPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">MEK_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70ad184d95272d90612c94695f1d1f42fcf">MEK_HIGHER</a>, <a href="#ab8bb54401d51992af131ce600f468f70aeb7b57e94a471eb90a2905c65b60ce47">MEK_HIGHEST</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">MEK_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">MEK_NEG</a>, <a href="#ab8bb54401d51992af131ce600f468f70a127b4af2e6597a11a2271486307fdac1">MEK_None</a>, <a href="#ab8bb54401d51992af131ce600f468f70adc7eb8cb308edcc2b568b4a737a6174c">MEK_PCREL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ac16da9fec94c6aaee788e43d1788bfea">MEK_PCREL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2356920f62894ef31881aff40beabcb">MEK_Special</a>, <a href="#ab8bb54401d51992af131ce600f468f70abe74e919e6de05ae1af1093c96928e29">MEK_TLSGD</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89674453ca1f94bb72d4e9dca3e1e771">MEK_TLSLDM</a>, <a href="#ab8bb54401d51992af131ce600f468f70a855ac563dd866b584fe34b8d58eb4546">MEK_TPREL_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8c4e3452b4ab8d6f1b9bdb42ecd075f6">MEK_TPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### findAssociatedFragment() {#a0126936c6207ecb570fedf6fbeb92419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::MipsMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a80e3a96e4ef966b2497116da4c6911be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#a8321e3415e010ba4cb28d4317332603e">getKind</a>, <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab8bb54401d51992af131ce600f468f70a257902481821ba5b40f837390279b03a">MEK_CALL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a649881b3e57f4661dd4c80bee4a4b90a">MEK_CALL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a84706a1c917c45b0668fbdbe8b4dd793">MEK_DTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89d1a8e66789c4eae95877553dbc1565">MEK_DTPREL_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70a9d0a302a9152729f52460e636c7fb44e">MEK_DTPREL_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a386aafa447bee675e328e88e9470957e">MEK_GOT</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0453b77229668594037b194c19c8e8ab">MEK_GOT_CALL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0ae33921dce666ee7adef46268bf9f2f">MEK_GOT_DISP</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0a7f1b614b8ffd488e6089fbe10a316f">MEK_GOT_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70af6e3d6f3b62ea7d5e97a5e8ff6ccf054">MEK_GOT_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ab986b26f0ebeb0499f36b0d82fe639d7">MEK_GOT_OFST</a>, <a href="#ab8bb54401d51992af131ce600f468f70adcc3e0803f2bff3ce95d8ff86fb0f550">MEK_GOT_PAGE</a>, <a href="#ab8bb54401d51992af131ce600f468f70a79bd0912db4f9ad29c7e7e172a5c805d">MEK_GOTTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">MEK_GPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">MEK_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70ad184d95272d90612c94695f1d1f42fcf">MEK_HIGHER</a>, <a href="#ab8bb54401d51992af131ce600f468f70aeb7b57e94a471eb90a2905c65b60ce47">MEK_HIGHEST</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">MEK_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">MEK_NEG</a>, <a href="#ab8bb54401d51992af131ce600f468f70a127b4af2e6597a11a2271486307fdac1">MEK_None</a>, <a href="#ab8bb54401d51992af131ce600f468f70adc7eb8cb308edcc2b568b4a737a6174c">MEK_PCREL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ac16da9fec94c6aaee788e43d1788bfea">MEK_PCREL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2356920f62894ef31881aff40beabcb">MEK_Special</a>, <a href="#ab8bb54401d51992af131ce600f468f70abe74e919e6de05ae1af1093c96928e29">MEK_TLSGD</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89674453ca1f94bb72d4e9dca3e1e771">MEK_TLSLDM</a>, <a href="#ab8bb54401d51992af131ce600f468f70a855ac563dd866b584fe34b8d58eb4546">MEK_TPREL_HI</a> and <a href="#ab8bb54401d51992af131ce600f468f70a8c4e3452b4ab8d6f1b9bdb42ecd075f6">MEK_TPREL_LO</a>.</p>

</div>
</div>

### getKind() {#a8321e3415e010ba4cb28d4317332603e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsExprKind llvm::MipsMCExpr::getKind ()</td>
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

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<p>Referenced by <a href="#ae6611e2e9cb3a7eea00a5150360c2e98">evaluateAsRelocatableImpl</a>, <a href="#a80e3a96e4ef966b2497116da4c6911be">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a> and <a href="#ad68220d5cd03f3e38fd0949937c7e6ac">isGpOff</a>.</p>

</div>
</div>

### getSubExpr() {#a40f77c0873c95fd1652e5769b991bd55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MipsMCExpr::getSubExpr ()</td>
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

<p>Get the child of this expression.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<p>Referenced by <a href="#ae6611e2e9cb3a7eea00a5150360c2e98">evaluateAsRelocatableImpl</a>, <a href="#a0126936c6207ecb570fedf6fbeb92419">findAssociatedFragment</a>, <a href="#a80e3a96e4ef966b2497116da4c6911be">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a>, <a href="#ad68220d5cd03f3e38fd0949937c7e6ac">isGpOff</a>, <a href="#aa879516d2836ed2f4f6bf40d11489f94">printImpl</a> and <a href="#abbef3f35fd05b8f0929d5e9d00abd8f8">visitUsedExpr</a>.</p>

</div>
</div>

### isGpOff() {#ad68220d5cd03f3e38fd0949937c7e6ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsMCExpr::isGpOff (<a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a> &amp; Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8321e3415e010ba4cb28d4317332603e">getKind</a>, <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a>, <a href="#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">MEK_GPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">MEK_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">MEK_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">MEK_NEG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a>.</p>

</div>
</div>

### isGpOff() {#abc5e849bf9c474c4c4baf1f35fefc667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsMCExpr::isGpOff ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<p>Reference <a href="#abc5e849bf9c474c4c4baf1f35fefc667">isGpOff</a>.</p>


<p>Referenced by <a href="#ae6611e2e9cb3a7eea00a5150360c2e98">evaluateAsRelocatableImpl</a> and <a href="#abc5e849bf9c474c4c4baf1f35fefc667">isGpOff</a>.</p>

</div>
</div>

### printImpl() {#aa879516d2836ed2f4f6bf40d11489f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab8bb54401d51992af131ce600f468f70a257902481821ba5b40f837390279b03a">MEK_CALL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a649881b3e57f4661dd4c80bee4a4b90a">MEK_CALL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70a84706a1c917c45b0668fbdbe8b4dd793">MEK_DTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89d1a8e66789c4eae95877553dbc1565">MEK_DTPREL_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70a9d0a302a9152729f52460e636c7fb44e">MEK_DTPREL_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a386aafa447bee675e328e88e9470957e">MEK_GOT</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0453b77229668594037b194c19c8e8ab">MEK_GOT_CALL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0ae33921dce666ee7adef46268bf9f2f">MEK_GOT_DISP</a>, <a href="#ab8bb54401d51992af131ce600f468f70a0a7f1b614b8ffd488e6089fbe10a316f">MEK_GOT_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70af6e3d6f3b62ea7d5e97a5e8ff6ccf054">MEK_GOT_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ab986b26f0ebeb0499f36b0d82fe639d7">MEK_GOT_OFST</a>, <a href="#ab8bb54401d51992af131ce600f468f70adcc3e0803f2bff3ce95d8ff86fb0f550">MEK_GOT_PAGE</a>, <a href="#ab8bb54401d51992af131ce600f468f70a79bd0912db4f9ad29c7e7e172a5c805d">MEK_GOTTPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">MEK_GPREL</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">MEK_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70ad184d95272d90612c94695f1d1f42fcf">MEK_HIGHER</a>, <a href="#ab8bb54401d51992af131ce600f468f70aeb7b57e94a471eb90a2905c65b60ce47">MEK_HIGHEST</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">MEK_LO</a>, <a href="#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">MEK_NEG</a>, <a href="#ab8bb54401d51992af131ce600f468f70a127b4af2e6597a11a2271486307fdac1">MEK_None</a>, <a href="#ab8bb54401d51992af131ce600f468f70adc7eb8cb308edcc2b568b4a737a6174c">MEK_PCREL_HI16</a>, <a href="#ab8bb54401d51992af131ce600f468f70ac16da9fec94c6aaee788e43d1788bfea">MEK_PCREL_LO16</a>, <a href="#ab8bb54401d51992af131ce600f468f70aa2356920f62894ef31881aff40beabcb">MEK_Special</a>, <a href="#ab8bb54401d51992af131ce600f468f70abe74e919e6de05ae1af1093c96928e29">MEK_TLSGD</a>, <a href="#ab8bb54401d51992af131ce600f468f70a89674453ca1f94bb72d4e9dca3e1e771">MEK_TLSLDM</a>, <a href="#ab8bb54401d51992af131ce600f468f70a855ac563dd866b584fe34b8d58eb4546">MEK_TPREL_HI</a>, <a href="#ab8bb54401d51992af131ce600f468f70a8c4e3452b4ab8d6f1b9bdb42ecd075f6">MEK_TPREL_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>.</p>

</div>
</div>

### visitUsedExpr() {#abbef3f35fd05b8f0929d5e9d00abd8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="#a40f77c0873c95fd1652e5769b991bd55">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#ae160c2132b6e7b7bddf1f1a0532a3267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MipsMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a88cea550e158bd5d2a5bfdc140fc2fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsExprKind llvm::MipsMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a2a6f8e5eca9341fc2b71da20283eda03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#a0087423de073ff81b2249bdea54eab40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsMCExpr * MipsMCExpr::create (<a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>Referenced by <a href="#af29afc8458b5cc153a5cb5e1e8f0252f">createGpOff</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a79d8b8865a2b71781082b9ea2da3b5a5">anonymous{MipsAsmParser.cpp}::MipsAsmParser::createTargetUnaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a4824f185b09fa4322916df3508816b22">llvm::MipsTargetObjectFile::getDebugThreadLocalSymbol</a>.</p>

</div>
</div>

### createGpOff() {#af29afc8458b5cc153a5cb5e1e8f0252f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsMCExpr * MipsMCExpr::createGpOff (<a href="#ab8bb54401d51992af131ce600f468f70">MipsExprKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a>.</p>


<p>References <a href="#a0087423de073ff81b2249bdea54eab40">create</a>, <a href="#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">MEK_GPREL</a> and <a href="#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">MEK_NEG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp">MipsMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-h">MipsMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
