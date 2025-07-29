---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonmcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonMCExpr` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">Target/Hexagon/MCTargetDesc/HexagonMCExpr.h</a>"
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b6e773cd93cecfb1752b9490ea0bfb">HexagonMCExpr</a> (MCExpr const *Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de7a5304f764fd6583ec75b5ce6a5e6">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d38c1312f839e6d789932230e6d420f">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec934e512bcd861faf50a32379b571ed">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa950b1f4ad67940b27f8c23658a6ec2b">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5961a76571b72f4bde70a029fd7e31c0">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;Asm) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab552670a785e186ac48027fe4ae32688">getExpr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f09c78f6fc2bf531212eabec2905904">setMustExtend</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6727baf4b2e8c33ab3c7063339c4e3">mustExtend</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d94ee4c8ac6b3ec3606c9766c82dcd9">setMustNotExtend</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318bb6449f347e87664f9dec35a831bc">mustNotExtend</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5586106990e946fd835539d8ac11902">setS27_2_reloc</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e372984bd10356d2313b67a899ced9">s27_2_reloc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbdc9f3a3b8d6aad75da13ed2f96bd9b">setSignMismatch</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de034f0258dedf038d0c47588468e7e">signMismatch</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a06cb912ed94ff1d483f8b1d05f77b5">Expr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8328599329004a14debacebaf3679805">MustNotExtend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683ae6607e447f73b015f9de469791ad">MustExtend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951f90c42f67133c8bc0bc7861eb0852">S27_2_reloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd121c3539615ab7dd004d2222408e4">SignMismatch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr">HexagonMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81566bd7394be9eb4df918513ea11b9b">create</a> (MCExpr const *Expr, MCContext &amp;Ctx)</td>
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


<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### HexagonMCExpr() {#a84b6e773cd93cecfb1752b9490ea0bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonMCExpr::HexagonMCExpr (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#a8d38c1312f839e6d789932230e6d420f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

### findAssociatedFragment() {#aa950b1f4ad67940b27f8c23658a6ec2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::HexagonMCExpr::findAssociatedFragment ()</td>
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



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a5961a76571b72f4bde70a029fd7e31c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a> and <a href="#ab552670a785e186ac48027fe4ae32688">getExpr</a>.</p>

</div>
</div>

### getExpr() {#ab552670a785e186ac48027fe4ae32688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCExpr const  * HexagonMCExpr::getExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="#a5961a76571b72f4bde70a029fd7e31c0">fixELFSymbolsInTLSFixups</a>.</p>

</div>
</div>

### mustExtend() {#a7b6727baf4b2e8c33ab3c7063339c4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCExpr::mustExtend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae19c50e8978b829dd70b876360c78894">llvm::HexagonMCInstrInfo::mustExtend</a>.</p>

</div>
</div>

### mustNotExtend() {#a318bb6449f347e87664f9dec35a831bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCExpr::mustNotExtend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5ad0644e32da21f9b472af7cdcd6a9d4">llvm::HexagonMCInstrInfo::mustNotExtend</a>.</p>

</div>
</div>

### printImpl() {#a4de7a5304f764fd6583ec75b5ce6a5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>.</p>

</div>
</div>

### s27\_2\_reloc() {#a85e372984bd10356d2313b67a899ced9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCExpr::s27_2_reloc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa194168067ea8a2c03b1973560ce0904">llvm::HexagonMCInstrInfo::s27_2_reloc</a>.</p>

</div>
</div>

### setMustExtend() {#a9f09c78f6fc2bf531212eabec2905904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::setMustExtend (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aedeada7604ef9521d3aec4ec5441811c">llvm::HexagonMCInstrInfo::setMustExtend</a>.</p>

</div>
</div>

### setMustNotExtend() {#a1d94ee4c8ac6b3ec3606c9766c82dcd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::setMustNotExtend (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac3e1f7a4739363ebefca0ac7930c2ccb">llvm::HexagonMCInstrInfo::setMustNotExtend</a>.</p>

</div>
</div>

### setS27\_2\_reloc() {#ab5586106990e946fd835539d8ac11902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::setS27_2_reloc (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a35d0d6d8b3d10dd3c01582071e1da5da">llvm::HexagonMCInstrInfo::setS27_2_reloc</a>.</p>

</div>
</div>

### setSignMismatch() {#acbdc9f3a3b8d6aad75da13ed2f96bd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::setSignMismatch (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>

</div>
</div>

### signMismatch() {#a6de034f0258dedf038d0c47588468e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCExpr::signMismatch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>

</div>
</div>

### visitUsedExpr() {#aec934e512bcd861faf50a32379b571ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expr {#a4a06cb912ed94ff1d483f8b1d05f77b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCExpr const* llvm::HexagonMCExpr::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>

</div>
</div>

### MustExtend {#a683ae6607e447f73b015f9de469791ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCExpr::MustExtend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>

</div>
</div>

### MustNotExtend {#a8328599329004a14debacebaf3679805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCExpr::MustNotExtend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>

</div>
</div>

### S27\_2\_reloc {#a951f90c42f67133c8bc0bc7861eb0852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCExpr::S27_2_reloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>

</div>
</div>

### SignMismatch {#a9cd121c3539615ab7dd004d2222408e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCExpr::SignMismatch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a81566bd7394be9eb4df918513ea11b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonMCExpr * HexagonMCExpr::create (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a4562e6672b8b09e99e8bc49651b20e0c">llvm::HexagonAsmPrinter::EmitSled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a1e6614f21ef1971dca42492c7318b5b7">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpressionOrOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a7e075cc11fc81de8e280e3cdf8560ef3">ScaleVectorOffset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp">HexagonMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">HexagonMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
