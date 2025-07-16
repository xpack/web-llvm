---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpumcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUMCExpr` Class Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> target specific <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUMCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">Target/AMDGPU/MCTargetDesc/AMDGPUMCExpr.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VariantKind { <a href="#ac4e921b9d06cd1d20aa4994fc39ec64e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc3311a29203872aa32bb496ed38262">AMDGPUMCExpr</a> (VariantKind Kind, ArrayRef&lt; const MCExpr * &gt; Args, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453c499a74f936a9e882b3da2dac2223">~AMDGPUMCExpr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01629bf98f076a28c7b9b6f749cf1362">getArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac4e921b9d06cd1d20aa4994fc39ec64e">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13ba175af48ccb8caee3131ff1f4b7d">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03d9d83552b7841365415497274cb72">getSubExpr</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5a084f344a6ac2bba0451e0e9d6b45">printImpl</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ea2a3563181056354939fd2ed18e7e">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50a638d75c912e0d3b7b4624220e676">isSymbolUsedInExpression</a> (const MCSymbol *Sym) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3539e01cd4cfb4b9bf60489ae59a370b">visitUsedExpr</a> (MCStreamer &amp;Streamer) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5a31b7b4cdb70bc9991f1fde3391b0">findAssociatedFragment</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658c1563f15dc50adacb328ee1803bd6">fixELFSymbolsInTLSFixups</a> (MCAssembler &amp;) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eac2cbe2d51e739f814da4eeb497227">evaluateExtraSGPRs</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec1fd8cce9a13d660fe310d5b8ba17c">evaluateTotalNumVGPR</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8980e4b8385c2570f705f899ed3eb942">evaluateAlignTo</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9c0ee2ce7a595e18e9111c7984aec1">evaluateOccupancy</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac4e921b9d06cd1d20aa4994fc39ec64e">VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946c6e9411b4d95f78913a3810629c82">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad75af2e85e0565565c2dbd4fc4b3d60">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d45cc45d5da6e2383d9e01efe9298cd">RawArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801bb27e665b2a974c3ce9fd9d9c15f3">Args</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a> (VariantKind Kind, ArrayRef&lt; const MCExpr * &gt; Args, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6b0d859beed9d09768817687a6c972">createOr</a> (ArrayRef&lt; const MCExpr * &gt; Args, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245bacdf3c88f5963f1ea0b9cc20ffb0">createMax</a> (ArrayRef&lt; const MCExpr * &gt; Args, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e0974cd15aab665b6eba448cd94a5f">createExtraSGPRs</a> (const MCExpr *VCCUsed, const MCExpr *FlatScrUsed, bool XNACKUsed, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow delayed <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> resolve of ExtraSGPRs (in case VCCUsed or FlatScrUsed are unresolvable but needed for further MCExprs). <a href="#a99e0974cd15aab665b6eba448cd94a5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65eb9f650ce7f4dd73c2961f327f3128">createTotalNumVGPR</a> (const MCExpr *NumAGPR, const MCExpr *NumVGPR, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e40571141ae9feea150533572000199">createAlignTo</a> (const MCExpr *Value, const MCExpr *Align, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr">AMDGPUMCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528b669c7627f74c541a4800020df024">createOccupancy</a> (unsigned InitOcc, const MCExpr *NumSGPRs, const MCExpr *NumVGPRs, const GCNSubtarget &amp;STM, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mimics <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a78f78fef97b3e953f2f4992c369026d8">GCNSubtarget::computeOccupancy</a> for <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>. <a href="#a528b669c7627f74c541a4800020df024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded4cac13d059876caa1a12383c913ca">classof</a> (const MCExpr *E)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> target specific <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> operations.</p>


<p>Takes in a minimum of 1 argument to be used with an operation. The supported operations are:</p>


<ul class="doxyList ">
<li>(bitwise) or</li>
<li>max</li>
</ul>


:::info
<p>If the 'or'/'max' operations are provided only a single argument, the operation will act as a no-op and simply resolve as the provided argument.</p>
:::


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VariantKind {#ac4e921b9d06cd1d20aa4994fc39ec64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPUMCExpr::VariantKind </td>
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
<td class="doxyEnumItemName">AGVK_None<a id="ac4e921b9d06cd1d20aa4994fc39ec64eae7e93f75812fefd9f4b26aa8af091c9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_Or<a id="ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_Max<a id="ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_ExtraSGPRs<a id="ac4e921b9d06cd1d20aa4994fc39ec64ea8014f0c199aed5816661d1d3f14ac1fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_TotalNumVGPRs<a id="ac4e921b9d06cd1d20aa4994fc39ec64ea7d773e01afab66dff838bb1d5130fd5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_AlignTo<a id="ac4e921b9d06cd1d20aa4994fc39ec64ea4f4d41a1b5065704c6265c1d247e1f9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AGVK_Occupancy<a id="ac4e921b9d06cd1d20aa4994fc39ec64ea1390ea547d87d17899b5bf826b26ac96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### AMDGPUMCExpr() {#a9fc3311a29203872aa32bb496ed38262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUMCExpr::AMDGPUMCExpr (<a href="#ac4e921b9d06cd1d20aa4994fc39ec64e">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~AMDGPUMCExpr() {#a453c499a74f936a9e882b3da2dac2223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUMCExpr::~AMDGPUMCExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAsRelocatableImpl() {#ac7ea2a3563181056354939fd2ed18e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea4f4d41a1b5065704c6265c1d247e1f9e">AGVK_AlignTo</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea8014f0c199aed5816661d1d3f14ac1fc">AGVK_ExtraSGPRs</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea1390ea547d87d17899b5bf826b26ac96">AGVK_Occupancy</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea7d773e01afab66dff838bb1d5130fd5b">AGVK_TotalNumVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#af9a96a0245ea7da2779a023ab07829e4">llvm::MCValue::isAbsolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

### findAssociatedFragment() {#a0b5a31b7b4cdb70bc9991f1fde3391b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * AMDGPUMCExpr::findAssociatedFragment ()</td>
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



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>.</p>

</div>
</div>

### fixELFSymbolsInTLSFixups() {#a658c1563f15dc50adacb328ee1803bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUMCExpr::fixELFSymbolsInTLSFixups (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp;)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

### getArgs() {#a01629bf98f076a28c7b9b6f749cf1362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const MCExpr * &gt; llvm::AMDGPUMCExpr::getArgs ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>Referenced by <a href="#ab50a638d75c912e0d3b7b4624220e676">isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### getKind() {#af13ba175af48ccb8caee3131ff1f4b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AMDGPUMCExpr::getKind ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### getSubExpr() {#ac03d9d83552b7841365415497274cb72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AMDGPUMCExpr::getSubExpr (size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### isSymbolUsedInExpression() {#ab50a638d75c912e0d3b7b4624220e676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::isSymbolUsedInExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>Reference <a href="#a01629bf98f076a28c7b9b6f749cf1362">getArgs</a>.</p>

</div>
</div>

### printImpl() {#acc5a084f344a6ac2bba0451e0e9d6b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCExpr::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea4f4d41a1b5065704c6265c1d247e1f9e">AGVK_AlignTo</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea8014f0c199aed5816661d1d3f14ac1fc">AGVK_ExtraSGPRs</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0">AGVK_Max</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea1390ea547d87d17899b5bf826b26ac96">AGVK_Occupancy</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc">AGVK_Or</a>, <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea7d773e01afab66dff838bb1d5130fd5b">AGVK_TotalNumVGPRs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### visitUsedExpr() {#a3539e01cd4cfb4b9bf60489ae59a370b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCExpr::visitUsedExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateAlignTo() {#a8980e4b8385c2570f705f899ed3eb942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::evaluateAlignTo (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

### evaluateExtraSGPRs() {#a7eac2cbe2d51e739f814da4eeb497227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::evaluateExtraSGPRs (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

### evaluateOccupancy() {#aec9c0ee2ce7a595e18e9111c7984aec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::evaluateOccupancy (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

### evaluateTotalNumVGPR() {#a2ec1fd8cce9a13d660fe310d5b8ba17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCExpr::evaluateTotalNumVGPR (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Args {#a801bb27e665b2a974c3ce9fd9d9c15f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;const MCExpr *&gt; llvm::AMDGPUMCExpr::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

### Ctx {#aad75af2e85e0565565c2dbd4fc4b3d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::AMDGPUMCExpr::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

### Kind {#a946c6e9411b4d95f78913a3810629c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantKind llvm::AMDGPUMCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

### RawArgs {#a4d45cc45d5da6e2383d9e01efe9298cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr** llvm::AMDGPUMCExpr::RawArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aded4cac13d059876caa1a12383c913ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMCExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>.</p>

</div>
</div>

### create() {#a8b210af308c92a311c2a71c9a2ad051a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * AMDGPUMCExpr::create (<a href="#ac4e921b9d06cd1d20aa4994fc39ec64e">VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>Referenced by <a href="#a9e40571141ae9feea150533572000199">createAlignTo</a>, <a href="#a99e0974cd15aab665b6eba448cd94a5f">createExtraSGPRs</a>, <a href="#a245bacdf3c88f5963f1ea0b9cc20ffb0">createMax</a>, <a href="#a528b669c7627f74c541a4800020df024">createOccupancy</a>, <a href="#aad6b0d859beed9d09768817687a6c972">createOr</a>, <a href="#a65eb9f650ce7f4dd73c2961f327f3128">createTotalNumVGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### createAlignTo() {#a9e40571141ae9feea150533572000199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * llvm::AMDGPUMCExpr::createAlignTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Align, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea4f4d41a1b5065704c6265c1d247e1f9e">AGVK_AlignTo</a> and <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#ae18928643ad012c59561c9e50dc452fa">computeAccumOffset</a>.</p>

</div>
</div>

### createExtraSGPRs() {#a99e0974cd15aab665b6eba448cd94a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * AMDGPUMCExpr::createExtraSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * VCCUsed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * FlatScrUsed, bool XNACKUsed, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>Allow delayed <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> resolve of ExtraSGPRs (in case VCCUsed or FlatScrUsed are unresolvable but needed for further MCExprs).</p>


<p>Derived from implementation of <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f0de0c1180aa2d8965d9cdddfde84a5">IsaInfo::getNumExtraSGPRs</a> in <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea8014f0c199aed5816661d1d3f14ac1fc">AGVK_ExtraSGPRs</a>, <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#aeac390246bd74f8e7897e99b30ae2c6f">llvm::MCResourceInfo::createTotalNumSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### createMax() {#a245bacdf3c88f5963f1ea0b9cc20ffb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * llvm::AMDGPUMCExpr::createMax (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0">AGVK_Max</a> and <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#ae18928643ad012c59561c9e50dc452fa">computeAccumOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>.</p>

</div>
</div>

### createOccupancy() {#a528b669c7627f74c541a4800020df024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * AMDGPUMCExpr::createOccupancy (unsigned InitOcc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NumSGPRs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NumVGPRs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; STM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>Mimics <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a78f78fef97b3e953f2f4992c369026d8">GCNSubtarget::computeOccupancy</a> for <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>.</p>


<p>Remove dependency on <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> and depend only only the necessary values for said occupancy computation. Should match computeOccupancy implementation without passing <span class="doxyComputerOutput">STM</span> on.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea1390ea547d87d17899b5bf826b26ac96">AGVK_Occupancy</a>, <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#ace4de1de19cbe837c578fb3654b6c998">llvm::GCNSubtarget::getGeneration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a41a62eaa48728ca1d52dda5d0a9b08c1">llvm::AMDGPU::IsaInfo::getMaxWavesPerEU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a14accda22ecd133d48fa434165e690a0">llvm::AMDGPU::IsaInfo::getTotalNumVGPRs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae47a2723f63ec4e85b4228b56e5d759c">llvm::AMDGPU::IsaInfo::getVGPRAllocGranule</a>.</p>

</div>
</div>

### createOr() {#aad6b0d859beed9d09768817687a6c972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * llvm::AMDGPUMCExpr::createOr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc">AGVK_Or</a> and <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a>.</p>

</div>
</div>

### createTotalNumVGPR() {#a65eb9f650ce7f4dd73c2961f327f3128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMCExpr * AMDGPUMCExpr::createTotalNumVGPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NumAGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NumVGPR, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="#ac4e921b9d06cd1d20aa4994fc39ec64ea7d773e01afab66dff838bb1d5130fd5b">AGVK_TotalNumVGPRs</a> and <a href="#a8b210af308c92a311c2a71c9a2ad051a">create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a6fa44a1fa346266bc9d287dce014dcfb">llvm::MCResourceInfo::createTotalNumVGPRs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
