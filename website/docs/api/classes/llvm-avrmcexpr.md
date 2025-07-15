---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AVRMCExpr` Class Reference

<p>A expression in <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">Target/AVR/MCTargetDesc/AVRMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#a963c676dc0bbdb455b7d84f71f35ca7e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifies the type of an expression. <a href="#a963c676dc0bbdb455b7d84f71f35ca7e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e113f6cb0c846329794c1eebfa181d7">AVRMCExpr</a> (VariantKind Kind, const MCExpr *Expr, bool Negated)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44301710c2af50e370afe9509989d04a">~AVRMCExpr</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a963c676dc0bbdb455b7d84f71f35ca7e">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b51f96d5fa6514746ac9bb7b725027">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the type of the expression. <a href="#a71b51f96d5fa6514746ac9bb7b725027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc52ae7e6ec071e9e7e586063104ba8b">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the name of the expression. <a href="#adc52ae7e6ec071e9e7e586063104ba8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815ae28b2e0a5700bd7b7dd3486504c2">getSubExpr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1">AVR::Fixups</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aec0a02f369f116f2372b20253005dc">getFixupKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the fixup which corresponds to the expression. <a href="#a3aec0a02f369f116f2372b20253005dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47441d62aeb6dd0b51c59a0bdcb11748">evaluateAsConstant</a> (int64_t &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluates the fixup as a constant value. <a href="#a47441d62aeb6dd0b51c59a0bdcb11748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8ff9b366e777f5e81d49e825a6d514">isNegated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7167be3d9f6421d08635a74d6afd11">setNegated</a> (bool negated=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a394a0cffa6632e417e87728dfd14a4">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af576492babedf4292598955c5adcf76b">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbdbf8c7001200fa2399608397e5746">visitUsedExpr</a> (MCStreamer &amp;streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138e6c66db9ffced264b6492b6355de9">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495694a4c9e60bcf42c7be83cc3f9aec">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e8419fbca4b140aecf13d0859bae18">evaluateAsInt64</a> (int64_t Value) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a963c676dc0bbdb455b7d84f71f35ca7e">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5de3aea2e36034c7c4d7d148ca1f9c">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e10b719c6c1a07e89903aab2da26576">SubExpr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8827063bdef27267c73f1f6f2b48cdeb">Negated</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr">AVRMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dda60009ec68b948826892b8cb5f75">create</a> (VariantKind Kind, const MCExpr *Expr, bool isNegated, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code expression. <a href="#a06dda60009ec68b948826892b8cb5f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625436f2d31e5c237035c4ec0658a4fc">classof</a> (const MCExpr *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a963c676dc0bbdb455b7d84f71f35ca7e">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303599407d59948c4938cffe6375de0a">getKindByName</a> (StringRef Name)</td>
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

<p>A expression in <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code.</p>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#a963c676dc0bbdb455b7d84f71f35ca7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AVRMCExpr::VariantKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specifies the type of an expression.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_None<a id="a963c676dc0bbdb455b7d84f71f35ca7ea3e188541dd26d06b2e94f270f2747dbd"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HI8<a id="a963c676dc0bbdb455b7d84f71f35ca7ead983bf089910d03f38c6ecfd9895f40b"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">hi8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_LO8<a id="a963c676dc0bbdb455b7d84f71f35ca7ea17d68c3365d37bba98c265778c257de8"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">lo8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HH8<a id="a963c676dc0bbdb455b7d84f71f35ca7eab5b06c1f5681eecbed057c4d595e74a1"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">hlo8() and hh8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HHI8<a id="a963c676dc0bbdb455b7d84f71f35ca7ea53c7ad4f7d81e5244496f4e27d984f82"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">hhi8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_PM<a id="a963c676dc0bbdb455b7d84f71f35ca7ea437c061b103c01b78c2d17eea54dc658"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">pm()</span>, reference to program memory</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_PM_LO8<a id="a963c676dc0bbdb455b7d84f71f35ca7ea09e73cf360d6f7dded6a699c9d29a66f"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">pm_lo8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_PM_HI8<a id="a963c676dc0bbdb455b7d84f71f35ca7ea20904697ab7c0bfa532f2a5285321a82"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">pm_hi8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_PM_HH8<a id="a963c676dc0bbdb455b7d84f71f35ca7eabf76baf9c9ef6feb676a09ff735c8918"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">pm_hh8()</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_LO8_GS<a id="a963c676dc0bbdb455b7d84f71f35ca7eabe72413cf67aa8fcadcf8f6944696211"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">lo8(gs())</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_HI8_GS<a id="a963c676dc0bbdb455b7d84f71f35ca7ea842018630575f76fa01b12213e92e8a7"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">hi8(gs())</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VK_AVR_GS<a id="a963c676dc0bbdb455b7d84f71f35ca7eabffd26c352f58776729a357e7e1bd290"></a></td>
<td class="doxyEnumItemDescription">Corresponds to <span class="doxyComputerOutput">gs()</span></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### AVRMCExpr() {#a1e113f6cb0c846329794c1eebfa181d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMCExpr::AVRMCExpr (<a href="#a963c676dc0bbdb455b7d84f71f35ca7e">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, bool Negated)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~AVRMCExpr() {#a44301710c2af50e370afe9509989d04a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMCExpr::~AVRMCExpr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsConstant() {#a47441d62aeb6dd0b51c59a0bdcb11748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMCExpr::evaluateAsConstant (int64_t &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evaluates the fixup as a constant value.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a> and <a href="#a815ae28b2e0a5700bd7b7dd3486504c2">getSubExpr</a>.</p>

</div>
</div>

### evaluateAsRelocatableImpl() {#af576492babedf4292598955c5adcf76b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea437c061b103c01b78c2d17eea54dc658">VK_AVR_PM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af427aa83e01ff2afe3a8640aaa86c0a9">llvm::MCSymbolRefExpr::VK_AVR_PM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### findAssociatedFragment() {#a138e6c66db9ffced264b6492b6355de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::AVRMCExpr::findAssociatedFragment ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a> and <a href="#a815ae28b2e0a5700bd7b7dd3486504c2">getSubExpr</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a495694a4c9e60bcf42c7be83cc3f9aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

### getFixupKind() {#a3aec0a02f369f116f2372b20253005dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVR::Fixups llvm::AVRMCExpr::getFixupKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the fixup which corresponds to the expression.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a0a7ad8e9592283440f485e0c10e944f2">llvm::AVR::fixup_16_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a382b86a3e3c868e6ddd9475944d8d1cd">llvm::AVR::fixup_hh8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a99d632ff5fa83e7b6ad4bf40eb108cbb">llvm::AVR::fixup_hh8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a9ee8f8e04076fa4bb138a15c7c28691f">llvm::AVR::fixup_hh8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ac8e2243f3ba6ba72cdea9d6e5d86a504">llvm::AVR::fixup_hh8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a78ac987d603e1af3517bd49dacc5ee34">llvm::AVR::fixup_hi8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a1edd771e4ceba008a0aa03ca9aee683f">llvm::AVR::fixup_hi8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aefc20853a2c98d2ef8a07255a98a6a22">llvm::AVR::fixup_hi8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ab13e48e1103a86880bd207573da528e9">llvm::AVR::fixup_hi8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a766028df6cd5759254edcfea42e8296d">llvm::AVR::fixup_hi8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a72001e129a73846ac51da1bc606f8c2d">llvm::AVR::fixup_lo8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa925266a218e48fd76747c51bd83615d">llvm::AVR::fixup_lo8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a58d3467e8ce0a23f1b6085534f4abf28">llvm::AVR::fixup_lo8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a86089f48a39009fba6b797d64a5c3e38">llvm::AVR::fixup_lo8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa45c22f2c30f421e4b2efbefde64a2b8">llvm::AVR::fixup_lo8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a57de6d17ac1d7fe855d0bdf7420b7e">llvm::AVR::fixup_ms8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a46b76675cc30a160bdc1efdfa54c26f2">llvm::AVR::fixup_ms8_ldi_neg</a>, <a href="#a71b51f96d5fa6514746ac9bb7b725027">getKind</a>, <a href="#aaf8ff9b366e777f5e81d49e825a6d514">isNegated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a3a1fa3eef584b35a695f93fb7e85a3a7">llvm::AVR::LastTargetFixupKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7eabffd26c352f58776729a357e7e1bd290">VK_AVR_GS</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7eab5b06c1f5681eecbed057c4d595e74a1">VK_AVR_HH8</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea53c7ad4f7d81e5244496f4e27d984f82">VK_AVR_HHI8</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ead983bf089910d03f38c6ecfd9895f40b">VK_AVR_HI8</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea842018630575f76fa01b12213e92e8a7">VK_AVR_HI8_GS</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea17d68c3365d37bba98c265778c257de8">VK_AVR_LO8</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7eabe72413cf67aa8fcadcf8f6944696211">VK_AVR_LO8_GS</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea3e188541dd26d06b2e94f270f2747dbd">VK_AVR_None</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea437c061b103c01b78c2d17eea54dc658">VK_AVR_PM</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7eabf76baf9c9ef6feb676a09ff735c8918">VK_AVR_PM_HH8</a>, <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea20904697ab7c0bfa532f2a5285321a82">VK_AVR_PM_HI8</a> and <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea09e73cf360d6f7dded6a699c9d29a66f">VK_AVR_PM_LO8</a>.</p>

</div>
</div>

### getKind() {#a71b51f96d5fa6514746ac9bb7b725027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AVRMCExpr::getKind ()</td>
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

<p>Gets the type of the expression.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<p>Referenced by <a href="#a3aec0a02f369f116f2372b20253005dc">getFixupKind</a>.</p>

</div>
</div>

### getName() {#adc52ae7e6ec071e9e7e586063104ba8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AVRMCExpr::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the name of the expression.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="#a5a394a0cffa6632e417e87728dfd14a4">printImpl</a>.</p>

</div>
</div>

### getSubExpr() {#a815ae28b2e0a5700bd7b7dd3486504c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::AVRMCExpr::getSubExpr ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<p>Referenced by <a href="#a47441d62aeb6dd0b51c59a0bdcb11748">evaluateAsConstant</a>, <a href="#a138e6c66db9ffced264b6492b6355de9">findAssociatedFragment</a>, <a href="#a5a394a0cffa6632e417e87728dfd14a4">printImpl</a> and <a href="#a1cbdbf8c7001200fa2399608397e5746">visitUsedExpr</a>.</p>

</div>
</div>

### isNegated() {#aaf8ff9b366e777f5e81d49e825a6d514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMCExpr::isNegated ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<p>Referenced by <a href="#a3aec0a02f369f116f2372b20253005dc">getFixupKind</a> and <a href="#a5a394a0cffa6632e417e87728dfd14a4">printImpl</a>.</p>

</div>
</div>

### printImpl() {#a5a394a0cffa6632e417e87728dfd14a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adc52ae7e6ec071e9e7e586063104ba8b">getName</a>, <a href="#a815ae28b2e0a5700bd7b7dd3486504c2">getSubExpr</a>, <a href="#aaf8ff9b366e777f5e81d49e825a6d514">isNegated</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a> and <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea3e188541dd26d06b2e94f270f2747dbd">VK_AVR_None</a>.</p>

</div>
</div>

### setNegated() {#a0e7167be3d9f6421d08635a74d6afd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCExpr::setNegated (bool negated=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

### visitUsedExpr() {#a1cbdbf8c7001200fa2399608397e5746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer)</td>
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



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="#a815ae28b2e0a5700bd7b7dd3486504c2">getSubExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateAsInt64() {#ab9e8419fbca4b140aecf13d0859bae18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AVRMCExpr::evaluateAsInt64 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#adc5de3aea2e36034c7c4d7d148ca1f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VariantKind llvm::AVRMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

### Negated {#a8827063bdef27267c73f1f6f2b48cdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMCExpr::Negated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

### SubExpr {#a7e10b719c6c1a07e89903aab2da26576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AVRMCExpr::SubExpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a625436f2d31e5c237035c4ec0658a4fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#a06dda60009ec68b948826892b8cb5f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRMCExpr * llvm::AVRMCExpr::create (<a href="#a963c676dc0bbdb455b7d84f71f35ca7e">VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, bool isNegated, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>Creates an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code expression.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a4622612a8ef9449430515a6c8614a7b9">llvm::AVRAsmPrinter::lowerConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>.</p>

</div>
</div>

### getKindByName() {#a303599407d59948c4938cffe6375de0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRMCExpr::VariantKind llvm::AVRMCExpr::getKindByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a> and <a href="#a963c676dc0bbdb455b7d84f71f35ca7ea3e188541dd26d06b2e94f270f2747dbd">VK_AVR_None</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-h">AVRMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
