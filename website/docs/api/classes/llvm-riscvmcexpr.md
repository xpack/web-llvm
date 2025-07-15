---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVMCExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">Target/RISCV/MCTargetDesc/RISCVMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#a6be127bc7f810a3f4dc182aff79943e6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e636394a36f7536c467ed2b86e772b5">RISCVMCExpr</a> (const MCExpr *Expr, VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00877c778cc9f75bf1682233e36930d9">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b6a90d8388aab90babe76b13765ddf6">getPCRelHiFixup</a> (const MCFragment **DFOut) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the corresponding PC-relative HI fixup that a VK_RISCV_PCREL_LO points to, and optionally the fragment containing it. <a href="#a4b6a90d8388aab90babe76b13765ddf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335d3c9eae0ade1e0ac3aff43ba90583">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dde8d50bac6a7bb455e6558fa95efa">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667256edf5e6bcb93ea674af7d41a8ce">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddeb9dfb6e1b81fe4d5ee0dd88eb6e4">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03310207de2d33d4b21d6e94bdabb76d">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742a0e5b5a151c9955edcdd8e04068ad">evaluateAsConstant</a> (int64_t &amp;Res) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d74dcf333fc42a3c81b8b8445728e3">evaluateAsInt64</a> (int64_t Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0345929cea97a0728a95333cb6d762">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592de5aeeff180d6251d019aecac7357">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr">RISCVMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113007d7338e79e7c4ebfec41a5b733a">create</a> (const MCExpr *Expr, VariantKind Kind, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7d9517844a32b1319e0b63ae7bd9eb">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71a001d22873f5487311a525ee014d7">getVariantKindForName</a> (StringRef name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a38e1ae757369266dd64277c7278ea">getVariantKindName</a> (VariantKind Kind)</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#a6be127bc7f810a3f4dc182aff79943e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">VK_RISCV_None<a id="a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_LO<a id="a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_HI<a id="a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_PCREL_LO<a id="a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_PCREL_HI<a id="a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_GOT_HI<a id="a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TPREL_LO<a id="a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TPREL_HI<a id="a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TPREL_ADD<a id="a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLS_GOT_HI<a id="a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLS_GD_HI<a id="a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_CALL<a id="a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_CALL_PLT<a id="a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_32_PCREL<a id="a6be127bc7f810a3f4dc182aff79943e6a604e28a9a3d857c263b22b49ba9b19f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLSDESC_HI<a id="a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLSDESC_LOAD_LO<a id="a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLSDESC_ADD_LO<a id="a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_TLSDESC_CALL<a id="a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_RISCV_Invalid<a id="a6be127bc7f810a3f4dc182aff79943e6ac04a0920cd401e8c1ed55264c9d1ae7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RISCVMCExpr() {#a9e636394a36f7536c467ed2b86e772b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVMCExpr::RISCVMCExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a> Kind)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsConstant() {#a742a0e5b5a151c9955edcdd8e04068ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVMCExpr::evaluateAsConstant (int64_t &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">VK_RISCV_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">VK_RISCV_CALL_PLT</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">VK_RISCV_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">VK_RISCV_PCREL_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">VK_RISCV_PCREL_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">VK_RISCV_TLS_GD_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">VK_RISCV_TLS_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">VK_RISCV_TLSDESC_ADD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">VK_RISCV_TLSDESC_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">VK_RISCV_TLSDESC_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">VK_RISCV_TLSDESC_LOAD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">VK_RISCV_TPREL_ADD</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">VK_RISCV_TPREL_HI</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">VK_RISCV_TPREL_LO</a>.</p>

</div>
</div>

### evaluateAsRelocatableImpl() {#a99dde8d50bac6a7bb455e6558fa95efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#a00877c778cc9f75bf1682233e36930d9">getKind</a>, <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">VK_RISCV_None</a>.</p>

</div>
</div>

### findAssociatedFragment() {#abddeb9dfb6e1b81fe4d5ee0dd88eb6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::RISCVMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a03310207de2d33d4b21d6e94bdabb76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="#a00877c778cc9f75bf1682233e36930d9">getKind</a>, <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">VK_RISCV_TLS_GD_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">VK_RISCV_TLS_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">VK_RISCV_TLSDESC_HI</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">VK_RISCV_TPREL_HI</a>.</p>

</div>
</div>

### getKind() {#a00877c778cc9f75bf1682233e36930d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::RISCVMCExpr::getKind ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>


<p>Referenced by <a href="#a99dde8d50bac6a7bb455e6558fa95efa">evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="#a03310207de2d33d4b21d6e94bdabb76d">fixELFSymbolsInTLSFixups</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a847e5bb4507e49e9af8582df2cb12f50">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getImmOpValue</a> and <a href="#a335d3c9eae0ade1e0ac3aff43ba90583">printImpl</a>.</p>

</div>
</div>

### getPCRelHiFixup() {#a4b6a90d8388aab90babe76b13765ddf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixup * RISCVMCExpr::getPCRelHiFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> ** DFOut)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the corresponding PC-relative HI fixup that a VK_RISCV_PCREL_LO points to, and optionally the fragment containing it.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>nullptr if this isn't a VK_RISCV_PCREL_LO pointing to a known PC-relative HI fixup.</p></dd>
</dl>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a4ff796b91dfd8a1d885eed8bf90d7cf7">llvm::RISCV::fixup_riscv_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad37e08bb2772b97fd5c82cc64b92b8c9">llvm::RISCV::fixup_riscv_pcrel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1dcfb88aadd66136c03e2620a6ff91dd">llvm::RISCV::fixup_riscv_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a13b9024d713be1b06a31431a40316038">llvm::RISCV::fixup_riscv_tls_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#af54312c2c4a267e78f5ee754c68dfbcc">llvm::MCSymbol::getOffset</a>, <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getSubExpr() {#a9b015218e16a353dd5bb4a60bb89d46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::RISCVMCExpr::getSubExpr ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>


<p>Referenced by <a href="#a742a0e5b5a151c9955edcdd8e04068ad">evaluateAsConstant</a>, <a href="#a99dde8d50bac6a7bb455e6558fa95efa">evaluateAsRelocatableImpl</a>, <a href="#abddeb9dfb6e1b81fe4d5ee0dd88eb6e4">findAssociatedFragment</a>, <a href="#a03310207de2d33d4b21d6e94bdabb76d">fixELFSymbolsInTLSFixups</a>, <a href="#a4b6a90d8388aab90babe76b13765ddf6">getPCRelHiFixup</a> and <a href="#a667256edf5e6bcb93ea674af7d41a8ce">visitUsedExpr</a>.</p>

</div>
</div>

### printImpl() {#a335d3c9eae0ade1e0ac3aff43ba90583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="#a00877c778cc9f75bf1682233e36930d9">getKind</a>, <a href="#a89a38e1ae757369266dd64277c7278ea">getVariantKindName</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">VK_RISCV_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">VK_RISCV_CALL_PLT</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">VK_RISCV_None</a>.</p>

</div>
</div>

### visitUsedExpr() {#a667256edf5e6bcb93ea674af7d41a8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="#a9b015218e16a353dd5bb4a60bb89d46c">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateAsInt64() {#ab4d74dcf333fc42a3c81b8b8445728e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t RISCVMCExpr::evaluateAsInt64 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#afc0345929cea97a0728a95333cb6d762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::RISCVMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a592de5aeeff180d6251d019aecac7357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::RISCVMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7c7d9517844a32b1319e0b63ae7bd9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#a113007d7338e79e7c4ebfec41a5b733a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVMCExpr * RISCVMCExpr::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a046ce1a28d601dbc32167434da7ce4cd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::EmitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcasminfo/#aca03cf4d1b04c7a87ec24725971e2605">llvm::RISCVMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ace19a1de0790088cc712996141fac07f">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerHWASAN_CHECK_MEMACCESS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>.</p>

</div>
</div>

### getVariantKindForName() {#af71a001d22873f5487311a525ee014d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVMCExpr::VariantKind RISCVMCExpr::getVariantKindForName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">VK_RISCV_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378">VK_RISCV_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ac04a0920cd401e8c1ed55264c9d1ae7d">VK_RISCV_Invalid</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">VK_RISCV_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">VK_RISCV_PCREL_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">VK_RISCV_PCREL_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">VK_RISCV_TLS_GD_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">VK_RISCV_TLS_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">VK_RISCV_TLSDESC_ADD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">VK_RISCV_TLSDESC_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">VK_RISCV_TLSDESC_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">VK_RISCV_TLSDESC_LOAD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">VK_RISCV_TPREL_ADD</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">VK_RISCV_TPREL_HI</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">VK_RISCV_TPREL_LO</a>.</p>

</div>
</div>

### getVariantKindName() {#a89a38e1ae757369266dd64277c7278ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RISCVMCExpr::getVariantKindName (<a href="#a6be127bc7f810a3f4dc182aff79943e6">VariantKind</a> Kind)</td>
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



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a604e28a9a3d857c263b22b49ba9b19f6">VK_RISCV_32_PCREL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">VK_RISCV_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">VK_RISCV_CALL_PLT</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">VK_RISCV_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378">VK_RISCV_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ac04a0920cd401e8c1ed55264c9d1ae7d">VK_RISCV_Invalid</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">VK_RISCV_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">VK_RISCV_None</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">VK_RISCV_PCREL_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">VK_RISCV_PCREL_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">VK_RISCV_TLS_GD_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">VK_RISCV_TLS_GOT_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">VK_RISCV_TLSDESC_ADD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">VK_RISCV_TLSDESC_CALL</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">VK_RISCV_TLSDESC_HI</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">VK_RISCV_TLSDESC_LOAD_LO</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">VK_RISCV_TPREL_ADD</a>, <a href="#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">VK_RISCV_TPREL_HI</a> and <a href="#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">VK_RISCV_TPREL_LO</a>.</p>


<p>Referenced by <a href="#a335d3c9eae0ade1e0ac3aff43ba90583">printImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp">RISCVMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
