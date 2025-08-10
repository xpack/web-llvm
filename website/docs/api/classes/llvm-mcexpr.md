---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCExpr` Class

<p>Base class for the full range of assembler expressions which are needed for parsing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Binary assembler expressions. <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr">MCConstantExpr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent a reference to a symbol from inside an expression. <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr">MCUnaryExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unary assembler expressions. <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ExprKind : uint8_t { <a href="#a83112ba0cecd7a7add9f1f9c441d606f">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa87b2d95c8eda3a0735b017b5aa8b3">MCExpr</a> (const MCExpr &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c94b145b6ade90726e2bab678ddc708">MCExpr</a> (ExprKind Kind, SMLoc Loc, unsigned SubclassData=0)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e7611d72a547f75d1b5299b0227728f">operator=</a> (const MCExpr &amp;)=delete</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup, const SectionAddrMap *Addrs, bool InSet) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a73c5ca50f673d05234b59a93bfa29">getSubclassData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5eeb27ae67dba976fec843d2fda75a">evaluateAsAbsolute</a> (int64_t &amp;Res, const MCAssembler *Asm, const SectionAddrMap *Addrs, bool InSet) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a83112ba0cecd7a7add9f1f9c441d606f">ExprKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77447c21d46c1e8b02e260c7185740b">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c989f844ab8929d4dcd46243fba0ea0">SubclassData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> reserved for use by <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> subclasses. <a href="#a0c989f844ab8929d4dcd46243fba0ea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb5582befe14ebc440ed819ae1c7dbd7">Loc</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2ef31f10b1090cecb8b7508c07aae4">NumSubclassDataBits</a> = 24</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a83112ba0cecd7a7add9f1f9c441d606f">ExprKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d6e67c11188675c1309e098afac194">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4237f50d652cdefff412b2c780c369">getLoc</a> () const</td>
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

## Utility Methods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3067756d9df7843be2d25cedab37da4">print</a> (raw_ostream &amp;OS, const MCAsmInfo *MAI, bool InParens=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9178f3e2cad3ab5a9b9cb621deac70a">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae066b71f79346e6cf0e978da4656e1bc">isSymbolUsedInExpression</a> (const MCSymbol *Sym) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the given symbol is used anywhere in the expression or subexpressions. <a href="#ae066b71f79346e6cf0e978da4656e1bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Expression Evaluation Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3118fd234d0cd907ed2e253fb2d41c0d">evaluateAsAbsolute</a> (int64_t &amp;Res, const MCAssembler &amp;Asm, const SectionAddrMap &amp;Addrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to evaluate the expression to an absolute value. <a href="#a3118fd234d0cd907ed2e253fb2d41c0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad587d3ff60ad2437c383befa45bcf256">evaluateAsAbsolute</a> (int64_t &amp;Res) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2879fe2effc4cf9bf2b4c57988a8bc04">evaluateAsAbsolute</a> (int64_t &amp;Res, const MCAssembler &amp;Asm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663c9eb11c0a7c5ddf59a069f7cc341d">evaluateAsAbsolute</a> (int64_t &amp;Res, const MCAssembler *Asm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9756a579fc66a3fbcc6d3e82866a289f">evaluateKnownAbsolute</a> (int64_t &amp;Res, const MCAssembler &amp;Asm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Aggressive variant of evaluateAsRelocatable when relocations are unavailable (e.g. <a href="#a9756a579fc66a3fbcc6d3e82866a289f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa770f9e822312cc252ee01659e0bc7d4">evaluateAsRelocatable</a> (MCValue &amp;Res, const MCAssembler *Asm, const MCFixup *Fixup) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to evaluate the expression to a relocatable value, i.e. <a href="#aa770f9e822312cc252ee01659e0bc7d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07235c25b41769181e0d69078b61d9d4">evaluateAsValue</a> (MCValue &amp;Res, const MCAssembler &amp;Asm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to evaluate the expression to the form (a - b + constant) where neither a nor b are variables. <a href="#a07235c25b41769181e0d69078b61d9d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4694d7c3e8bb89a9c2fb6227b8aa1df">findAssociatedFragment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the "associated section" for this expression, which is currently defined as the absolute section for constants, or otherwise the section associated with the first defined symbol in the expression. <a href="#ae4694d7c3e8bb89a9c2fb6227b8aa1df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for the full range of assembler expressions which are needed for parsing.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ExprKind {#a83112ba0cecd7a7add9f1f9c441d606f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCExpr::ExprKind : uint8_t</td>
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
<td class="doxyEnumItemName">Binary<a id="a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51"></a></td>
<td class="doxyEnumItemDescription">Binary expressions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Constant<a id="a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> expressions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolRef<a id="a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91"></a></td>
<td class="doxyEnumItemDescription">References to labels and assigned expressions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unary<a id="a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e"></a></td>
<td class="doxyEnumItemDescription">Unary expressions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Target<a id="a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific expression</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCExpr() {#a8fa87b2d95c8eda3a0735b017b5aa8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCExpr::MCExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="#a7c94b145b6ade90726e2bab678ddc708">MCExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCExpr() {#a7c94b145b6ade90726e2bab678ddc708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCExpr::MCExpr (<a href="#a83112ba0cecd7a7add9f1f9c441d606f">ExprKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned SubclassData=0)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a48adca21667701ac41350cfe0d5b2cf6">llvm::MCBinaryExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a34ffc3c2b42f106ac63cc782667bfdbc">llvm::MCConstantExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a0c5074811402edd4c3119fef6d874843">llvm::MCSymbolRefExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetexpr/#a0685692d0d12cfcab7b9fd08db421fda">llvm::MCTargetExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a162be98639df47af335231b5868f429d">llvm::MCUnaryExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac393df34745cae1433909c2049978bd4">llvm::MCBinaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a40326528db66cf90324ba646912d634d">llvm::MCUnaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a37d8557c5bc9e9a92ce9b663e21f5e47">llvm::MCBinaryExpr::createAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#aaf1cb4447353da4a08ae3b5d55ca3eda">llvm::MCBinaryExpr::createAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#abf02d969009762015e1f45b7f9b17e90">llvm::MCBinaryExpr::createDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a12fc65c1c33d36926fade150b9205991">llvm::MCBinaryExpr::createEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ab1c84873133c2893284f143e3949b15b">llvm::MCBinaryExpr::createGT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a944476a319c4dddd25f49bf1da4d1e9e">llvm::MCBinaryExpr::createGTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a18d807a1b5c938811456307bfd3560b1">llvm::MCBinaryExpr::createLAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a58195f308d23f783e2b52e968ff1fe46">llvm::MCUnaryExpr::createLNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a786dd04a46593c07b33f81fdc919ee4f">llvm::MCBinaryExpr::createLOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a18a49f94de6b90d6fbc0c730b6a2ae5b">llvm::MCBinaryExpr::createLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a51d82c00c5a59ac45d7fe9fbf7fdb256">llvm::MCBinaryExpr::createLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#aa681023ab973e112d1aeaad5ad6b6806">llvm::MCBinaryExpr::createLTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#aff718d95a5738283e9049bc93fa9abe2">llvm::MCUnaryExpr::createMinus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a70c32a58780aa68e18e47e0bfac6ad15">llvm::MCBinaryExpr::createMod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a994d277dcd8d2765f20ddb1e81a1187e">llvm::MCBinaryExpr::createMul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a7b0a201b1e3eb4fe198d3eec3bc6ad61">llvm::MCBinaryExpr::createNE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#af8b9397b901280268465e71ed2fef286">llvm::MCUnaryExpr::createNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a8f9fe9e0790b764dc9ef925a83408f74">llvm::MCUnaryExpr::createPlus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac3fa97ac31d48ef7708ba959db34f38d">llvm::MCBinaryExpr::createShl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a26f6e7794e457483f87961dfb8ed3f06">llvm::MCBinaryExpr::createXor</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a7744bb0ad33a4245610b0bb3d7f330ed">llvm::MCUnaryExpr::getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetexpr/#ac9ed439cfe7e04d0be8d6b73ad38be4a">llvm::MCTargetExpr::isEqualTo</a>, <a href="#ae066b71f79346e6cf0e978da4656e1bc">isSymbolUsedInExpression</a>, <a href="#a8fa87b2d95c8eda3a0735b017b5aa8b3">MCExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetexpr/#a8ac1fdf776114a374cd8929fba6b8ccc">llvm::MCTargetExpr::MCTargetExpr</a> and <a href="#a1e7611d72a547f75d1b5299b0227728f">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1e7611d72a547f75d1b5299b0227728f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCExpr &amp; llvm::MCExpr::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="#a7c94b145b6ade90726e2bab678ddc708">MCExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### evaluateAsRelocatableImpl() {#a5f1cbd9499b37094c4e6c9660d1dbe19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsRelocatableImpl (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac66fe51a73cdf1ab9f07ca6ead1652e7">SectionAddrMap</a> * Addrs, bool InSet)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">Binary</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a050338ae4cc98b34569977f26196f415">canExpand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">llvm::MCBinaryExpr::Div</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">llvm::MCBinaryExpr::EQ</a>, <a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#afa1844c524c0ee91d2cca0f3eac95382">evaluateSymbolicAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="#af5d6e67c11188675c1309e098afac194">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a1032772abdf9ca7296d4b4f35fe199ac">llvm::MCUnaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a48eebfa5f9f069075bc6412fd4371c7b">llvm::MCValue::getRefKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a7744bb0ad33a4245610b0bb3d7f330ed">llvm::MCUnaryExpr::getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">llvm::MCBinaryExpr::GT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">llvm::MCBinaryExpr::GTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#aff40cdca21460452b93bdf50f1f1b74d">llvm::MCSymbolRefExpr::hasSubsectionsViaSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#af9a96a0245ea7da2779a023ab07829e4">llvm::MCValue::isAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">llvm::MCBinaryExpr::LAnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa720aa777e91acde959f629de0f475126">llvm::MCUnaryExpr::LNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">llvm::MCBinaryExpr::LOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">llvm::MCBinaryExpr::LT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">llvm::MCBinaryExpr::LTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa23670b83f3704a21f5f8fcaf2701211a">llvm::MCUnaryExpr::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">llvm::MCBinaryExpr::Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">llvm::MCBinaryExpr::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa473ccb44d0bb542a3fa877acde7813ae">llvm::MCUnaryExpr::Not</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a952b1824a84c532fdcfa4e55e5548b5b">llvm::MCBinaryExpr::OrNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa43f553663c81a0962438aae8d8c44526">llvm::MCUnaryExpr::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">SymbolRef</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">Target</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">Unary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">llvm::MCBinaryExpr::Xor</a>.</p>


<p>Referenced by <a href="#aa770f9e822312cc252ee01659e0bc7d4">evaluateAsRelocatable</a>, <a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a> and <a href="#a07235c25b41769181e0d69078b61d9d4">evaluateAsValue</a>.</p>

</div>
</div>

### getSubclassData() {#ad7a73c5ca50f673d05234b59a93bfa29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCExpr::getSubclassData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a1032772abdf9ca7296d4b4f35fe199ac">llvm::MCUnaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a723344f63b9a579c118f9fdf8f7d6cac">llvm::MCConstantExpr::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#aff40cdca21460452b93bdf50f1f1b74d">llvm::MCSymbolRefExpr::hasSubsectionsViaSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a515212db43234f10b2a1a10bb66a9db9">llvm::MCConstantExpr::useHexFormat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateAsAbsolute() {#aca5eeb27ae67dba976fec843d2fda75a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsAbsolute (int64_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac66fe51a73cdf1ab9f07ca6ead1652e7">SectionAddrMap</a> * Addrs, bool InSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#af77447c21d46c1e8b02e260c7185740b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExprKind llvm::MCExpr::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### Loc {#adb5582befe14ebc440ed819ae1c7dbd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCExpr::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### SubclassData {#a0c989f844ab8929d4dcd46243fba0ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCExpr::SubclassData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> reserved for use by <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> subclasses.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### NumSubclassDataBits {#a0e2ef31f10b1090cecb8b7508c07aae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCExpr::NumSubclassDataBits = 24</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getKind {#af5d6e67c11188675c1309e098afac194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExprKind llvm::MCExpr::getKind ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#ac2aee5b5bd6cf3275da3e9e35895fecc">anonymous{HexagonAsmParser.cpp}::HexagonOperand::CheckImmRange</a>, <a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a>, <a href="#ae4694d7c3e8bb89a9c2fb6227b8aa1df">findAssociatedFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp/#aa46e35fd185109152c2cece337dcb1e8">getAccessVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#ad639f513acb55b87a86bfc216cff9052">llvm::CSKYMCCodeEmitter::getBareSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#ae0d5413e8969be7638d03ff8c9e65353">llvm::CSKYMCCodeEmitter::getBranchSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a08ac76217df04bb70d79e961194d3d26">llvm::CSKYMCCodeEmitter::getCallSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a4b28c7cecddbd6c9aae7628ac71f365b">llvm::CSKYMCCodeEmitter::getConstpoolSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a5a26e3bd1555734e7aa5a82457ddc0e1">llvm::CSKYMCCodeEmitter::getDataSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a847e5bb4507e49e9af8582df2cb12f50">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter/#a955c8163dbb18d99c96c57d1c4b273f0">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a0e3a46287a3ec80268b6629a7298532b">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyelfobjectwriter-cpp-/cskyelfobjectwriter/#adcfdb6cf22cdaa14533e19d6c71d71a1">anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvelfobjectwriter-cpp-/riscvelfobjectwriter/#a292b37d2a3f3fb782daf79fed6123098">anonymous{RISCVELFObjectWriter.cpp}::RISCVELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a719cb125836c429953e4eb35be1e93b4">hasGOTReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#ab8a1f4390e38136b60ae5a6a3c1195f2">hasSecRelSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#ae1ce9b8b6ff65433d9ef32af6eae8e31">hasVariantSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a1dfc57d55bc5df5056dea7c627f24c37">llvm::MCOperand::isBareSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#ab29acfdfda391000c99d74b9922342c6">isEvaluated</a>, <a href="#ae066b71f79346e6cf0e978da4656e1bc">isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a7ec597eb70645748d7299e7a05faa4a5">needsExpandMemInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumccodeemitter-cpp/#ad58cd525cd161ac7d20f74864814e557">needsPCRel</a>, <a href="#ae3067756d9df7843be2d25cedab37da4">print</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a59aaa2e922d6173cbeaed43a2d58423a">llvm::X86Operand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14a78c5a53b12d5137e5e5e3af8d4390">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3e9dd2df270e8ff9b688dc40af18e54e">startsWithGlobalOffsetTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

### getLoc {#afc4237f50d652cdefff412b2c780c369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCExpr::getLoc ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a6ffd2d1f64a9104fc1a62c1387fca16e">llvm::LoongArchAsmBackend::relaxLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a0b10511c4a52fc282850610c648ba455">llvm::RISCVAsmBackend::relaxLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a179d49e133edc4f825fe798450d24458">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility Methods

### dump {#ae9178f3e2cad3ab5a9b9cb621deac70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCExpr::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### isSymbolUsedInExpression {#ae066b71f79346e6cf0e978da4656e1bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::isSymbolUsedInExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the given symbol is used anywhere in the expression or subexpressions.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">Binary</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">Constant</a>, <a href="#af5d6e67c11188675c1309e098afac194">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="#ae066b71f79346e6cf0e978da4656e1bc">isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a61020d1a9925e4f1ad5bb1a6b8e5e46e">llvm::MCSymbol::isWeakExternal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7c94b145b6ade90726e2bab678ddc708">MCExpr</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">SymbolRef</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">Target</a> and <a href="#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">Unary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a> and <a href="#ae066b71f79346e6cf0e978da4656e1bc">isSymbolUsedInExpression</a>.</p>

</div>
</div>

### print {#ae3067756d9df7843be2d25cedab37da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCExpr::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI, bool InParens=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">llvm::MCBinaryExpr::Div</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">llvm::MCBinaryExpr::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#af5d6e67c11188675c1309e098afac194">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a1032772abdf9ca7296d4b4f35fe199ac">llvm::MCUnaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a7744bb0ad33a4245610b0bb3d7f330ed">llvm::MCUnaryExpr::getSubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a1431e9c9bff3315f5a9681a1cfc6d44b">llvm::MCSymbolRefExpr::getVariantKindName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">llvm::MCBinaryExpr::GT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">llvm::MCBinaryExpr::GTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">llvm::MCBinaryExpr::LAnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa720aa777e91acde959f629de0f475126">llvm::MCUnaryExpr::LNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">llvm::MCBinaryExpr::LOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">llvm::MCBinaryExpr::LT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">llvm::MCBinaryExpr::LTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa23670b83f3704a21f5f8fcaf2701211a">llvm::MCUnaryExpr::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">llvm::MCBinaryExpr::Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">llvm::MCBinaryExpr::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa473ccb44d0bb542a3fa877acde7813ae">llvm::MCUnaryExpr::Not</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a952b1824a84c532fdcfa4e55e5548b5b">llvm::MCBinaryExpr::OrNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa43f553663c81a0962438aae8d8c44526">llvm::MCUnaryExpr::Plus</a>, <a href="#ae3067756d9df7843be2d25cedab37da4">print</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">SymbolRef</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">Target</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">Unary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a8835db48923d3b3c5aef9a73dd332709">llvm::MCAsmInfo::useParensForDollarSignNames</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a0532cd65b328c02669c0d570f7af7626">llvm::MCAsmInfo::useParensForSymbolVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">llvm::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">llvm::MCBinaryExpr::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aae6d9fb29c7a596c66c84d2ccb0457dd">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a664095c8afe2051a5e22b25100685b01">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a6807c6b1007827cfda4d5fa7fae5747e">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::emitLocalEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a34bd9da2c0260776c7eb80aef5229322">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a098013528950083b042ec1af0ff34605">anonymous{HexagonAsmParser.cpp}::HexagonOperand::print</a>, <a href="#ae3067756d9df7843be2d25cedab37da4">print</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aed2da08c30700cc19a7bd01eaf6b3f40">llvm::ARMInstPrinter::printAdrLabelOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2d69f7dd3e8c055a8aa9f8a6c401dc51">llvm::AMDGPU::printAMDGPUMCExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a0572b63082c110b3a4b2a2b9c8d31d0f">llvm::AArch64InstPrinter::printAMIndexedWB</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#ab5f670329da0b2f68a30d42d277033fc">llvm::CSKYInstPrinter::printConstpool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a488900b8c4238199da9f7f1f70e035ad">llvm::CSKYInstPrinter::printDataSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#ac31114afe8ec5070ba99a22c6a1cd75d">llvm::AArch64AuthMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a5a394a0cffa6632e417e87728dfd14a4">llvm::AVRMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a4de7a5304f764fd6583ec75b5ce6a5e6">llvm::HexagonMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#aa879516d2836ed2f4f6bf40d11489f94">llvm::MipsMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a15e0c4774eadff80f38b0b4a491f98fd">llvm::PPCMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a75d3a2429c144498e74b899dbb33506e">llvm::X86ATTInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a066020a10f4b28e5fd81783c3fa5b1de">llvm::X86IntelInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#a9d6ddfcd5d505f33df950fa433e601a1">printMemoryImmediateOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14a78c5a53b12d5137e5e5e3af8d4390">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#aa3bc43f980c1b1c92a3e059d7656e1fb">llvm::RISCVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#a1fbde6ef1b980af08ff6d9de6cdc1f7b">llvm::SparcInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a60c14b6310b40e44fed1f341556c55ac">llvm::SystemZInstPrinterCommon::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a568643b76a6a9fb21ee23f7394de92fe">llvm::VEInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a65b4d5c7caa06554c79a0a8f7637e3d6">printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#aba7a5e60523b2a3eb825f0ee302ae6fc">llvm::SystemZInstPrinterCommon::printPCRelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4480dd8734b70a12632d73053873d011">llvm::ARMInstPrinter::printThumbLdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1ebaad303ddd83b5203b3548e43c06d1">llvm::AArch64InstPrinter::printUImm12Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Expression Evaluation

### evaluateAsAbsolute {#a3118fd234d0cd907ed2e253fb2d41c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsAbsolute (int64_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac66fe51a73cdf1ab9f07ca6ead1652e7">SectionAddrMap</a> &amp; Addrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to evaluate the expression to an absolute value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The absolute value, if evaluation succeeds.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### evaluateAsAbsolute {#ad587d3ff60ad2437c383befa45bcf256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsAbsolute (int64_t &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

### evaluateAsAbsolute {#a2879fe2effc4cf9bf2b4c57988a8bc04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsAbsolute (int64_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

### evaluateAsAbsolute {#a663c9eb11c0a7c5ddf59a069f7cc341d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsAbsolute (int64_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>

</div>
</div>

### evaluateAsRelocatable {#aa770f9e822312cc252ee01659e0bc7d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsRelocatable (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> * Fixup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to evaluate the expression to a relocatable value, i.e.</p>


<p>an expression of the fixed form (a - b + constant).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The relocatable value, if evaluation succeeds.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Asm</td>
<td class="doxyParamItemDescription"><p>- The assembler object to use for evaluating values.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fixup</td>
<td class="doxyParamItemDescription"><p>- The Fixup object if available.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#a463e5963bd9b6fdcbb33e4fd003d2863">llvm::DelayedMCExprs::assignDocNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a47441d62aeb6dd0b51c59a0bdcb11748">llvm::AVRMCExpr::evaluateAsConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#ad9cf19b582cdee72421a730baa57b59f">llvm::PPCMCExpr::evaluateAsConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a742a0e5b5a151c9955edcdd8e04068ad">llvm::RISCVMCExpr::evaluateAsConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a3cee463d58774d5fade0dce5de3b86e6">llvm::CSKYMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a408cec492b050bec5d09a6780b2fa980">llvm::SparcMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#a6874f1bf101eb054bfac298fd0bd3f53">llvm::XtensaMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a1d5112681065033b21957cce5c39a006">anonymous{MipsAsmParser.cpp}::MipsAsmParser::isJalrRelocAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#aaf5208586509a15c29239a946b2a1236">llvm::MCAssembler::isThumbFunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#afde1d15893de3e2295907d9d88911f08">llvm::DelayedMCExprs::resolveDelayedExpressions</a>.</p>

</div>
</div>

### evaluateAsValue {#a07235c25b41769181e0d69078b61d9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateAsValue (<a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to evaluate the expression to the form (a - b + constant) where neither a nor b are variables.</p>


<p>This is a more aggressive variant of evaluateAsRelocatable. The intended use is for when relocations are not available, like the .size directive.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Reference <a href="#a5f1cbd9499b37094c4e6c9660d1dbe19">evaluateAsRelocatableImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#abc4d6b7d638e45034130bc3ab18e5be6">llvm::MCAssembler::computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>.</p>

</div>
</div>

### evaluateKnownAbsolute {#a9756a579fc66a3fbcc6d3e82866a289f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExpr::evaluateKnownAbsolute (int64_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Aggressive variant of evaluateAsRelocatable when relocations are unavailable (e.g.</p>


<p>.fill). Expects callers to handle errors when true is returned.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a2ea528bf7b0254b3ae2e1c0864022767">computeLabelDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a6ffd2d1f64a9104fc1a62c1387fca16e">llvm::LoongArchAsmBackend::relaxLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a0b10511c4a52fc282850610c648ba455">llvm::RISCVAsmBackend::relaxLEB128</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a9090caa8ccfc6c4298f8d31ffbc73ca4">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSymbol</a>.</p>

</div>
</div>

### findAssociatedFragment {#ae4694d7c3e8bb89a9c2fb6227b8aa1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * MCExpr::findAssociatedFragment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the "associated section" for this expression, which is currently defined as the absolute section for constants, or otherwise the section associated with the first defined symbol in the expression.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab889b3167a4e08aeb1268d4712f7221c">llvm::MCSymbol::AbsolutePseudoFragment</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">Constant</a>, <a href="#ae4694d7c3e8bb89a9c2fb6227b8aa1df">findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="#af5d6e67c11188675c1309e098afac194">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">SymbolRef</a>, <a href="#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">Target</a> and <a href="#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">Unary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a0b5a31b7b4cdb70bc9991f1fde3391b0">llvm::AMDGPUMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcexpr/#ae40a4e648fa976465d9796c304e598f9">llvm::ARMMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a138e6c66db9ffced264b6492b6355de9">llvm::AVRMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#aeee5ef0c182a3313754792e18ebcec90">llvm::CSKYMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a9aed9264622245a3e6e6dc366c1e701a">llvm::LanaiMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af13d0f778dbd80fe988df361238268f0">llvm::LoongArchMCExpr::findAssociatedFragment</a>, <a href="#ae4694d7c3e8bb89a9c2fb6227b8aa1df">findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#a0126936c6207ecb570fedf6fbeb92419">llvm::MipsMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a95e569b2938e4a31ca23ba709da624d8">llvm::PPCMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#abddeb9dfb6e1b81fe4d5ee0dd88eb6e4">llvm::RISCVMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#adfbbe2390073ea564aa0b9f4086d8c43">llvm::SparcMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#ac59be61c76a3001dabb7a2ec037e8494">llvm::SystemZMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a71c01ea8a9f7f30631202409dc4c6097">llvm::VEMCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#a4a5724a1befc0d0c2cd905c139fb9e1c">llvm::XtensaMCExpr::findAssociatedFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
