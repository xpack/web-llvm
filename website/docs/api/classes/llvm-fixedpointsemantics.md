---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fixedpointsemantics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FixedPointSemantics` Class

<p>The fixed point semantics work similarly to <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FixedPointSemantics { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">llvm/ADT/APFixedPoint.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a> (unsigned Width, unsigned Scale, bool IsSigned, bool IsSaturated, bool HasUnsignedPadding)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeaa87c01286145d6ebf3a27b759ad0c">FixedPointSemantics</a> (unsigned Width, Lsb Weight, bool IsSigned, bool IsSaturated, bool HasUnsignedPadding)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74164b0a3bd99d34d93470f7563c8f40">operator==</a> (FixedPointSemantics Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7086a2258539bb56b6ecead61d15a6ec">operator!=</a> (FixedPointSemantics Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9c92a6e83154b310262cc88a986a76">isValidLegacySema</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the Semantic follow the requirements of an older more limited version of this class. <a href="#aea9c92a6e83154b310262cc88a986a76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3dab29dd773a1faa002a701261db99">getWidth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb21a8a338a43390965253fb71d152d">getScale</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea346c0aab9c7f4608ce41a4c217fa5">getLsbWeight</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232037d122854fa07a16938f469c8921">getMsbWeight</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ad0838e692b5cdc021f49da8343187">isSigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56da39babaf07b5638145d232de64949">isSaturated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516540ad4950d71de2266507041b9c6e">hasUnsignedPadding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aee131cca702391b24efc6d75a6775a">setSaturated</a> (bool Saturated)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf36b3741d49fd77bfca7057fb8e2f3f">hasSignOrPaddingBit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>return true if the first bit doesn't have a strictly positive weight <a href="#acf36b3741d49fd77bfca7057fb8e2f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60827722079f839f42712dacafce3695">getIntegralBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of integral bits represented by these semantics. <a href="#a60827722079f839f42712dacafce3695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a> (const FixedPointSemantics &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> that allows for calculating the full precision semantic that can precisely represent the precision and ranges of both input values. <a href="#a6e44daa940bc6479c419855e43d5f765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a> (llvm::raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print semantics for debug purposes. <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30aaf95486d0b2aac87f3d9e1e450e3">fitsInFloatSemantics</a> (const fltSemantics &amp;FloatSema) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this fixed-point semantic with its value bits interpreted as an integer can fit in the given floating point semantic without overflowing to infinity. <a href="#ab30aaf95486d0b2aac87f3d9e1e450e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2929b0e3eeba003376ef5515a006882">toOpaqueInt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the semantics to a 32-bit unsigned integer. <a href="#ae2929b0e3eeba003376ef5515a006882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69581f6a6b95d54065e0a0ba69562fdb">Width</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">signed int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d75945d7a896ec9bda6e6259de0865a">LsbWeight</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0b43bc6965ab65054313b6b3482e24">IsSigned</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951cf00fa5e0dd1a04643b1b0f630526">IsSaturated</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811d85ed575e2e3d1c7577fbe1af2f3e">HasUnsignedPadding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc9b19a86db06690ffcc4904907e8be">GetIntegerSemantics</a> (unsigned Width, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> for an integer type. <a href="#aebc9b19a86db06690ffcc4904907e8be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd07c34ae344bc593539aa2adbb9ad2">getFromOpaqueInt</a> (uint32_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> object from an integer created via <a href="#ae2929b0e3eeba003376ef5515a006882">toOpaqueInt()</a>. <a href="#a0bd07c34ae344bc593539aa2adbb9ad2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dbb2fca569d938f330154451a67b24">WidthBitWidth</a> = 16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a5fd6a1b76c5697876a2674a08ed00">LsbWeightBitWidth</a> = 13</td>
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

<p>The fixed point semantics work similarly to <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a>.</p>


<p>The width specifies the whole bit width of the underlying scaled integer (with padding if any). The scale represents the number of fractional bits in this type. When HasUnsignedPadding is true and this type is unsigned, the first bit in the value this represents is treated as padding.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FixedPointSemantics() {#ae59a8566a4fccd51331fdfcbe2cba59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FixedPointSemantics::FixedPointSemantics (unsigned Width, unsigned Scale, bool IsSigned, bool IsSaturated, bool HasUnsignedPadding)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Reference <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a>.</p>


<p>Referenced by <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a>, <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a>, <a href="#a0bd07c34ae344bc593539aa2adbb9ad2">getFromOpaqueInt</a>, <a href="#aebc9b19a86db06690ffcc4904907e8be">GetIntegerSemantics</a>, <a href="#a7086a2258539bb56b6ecead61d15a6ec">operator!=</a> and <a href="#a74164b0a3bd99d34d93470f7563c8f40">operator==</a>.</p>

</div>
</div>

### FixedPointSemantics() {#adeaa87c01286145d6ebf3a27b759ad0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FixedPointSemantics::FixedPointSemantics (unsigned Width, <a href="/web-llvm/docs/api/structs/llvm/fixedpointsemantics/lsb">Lsb</a> Weight, bool IsSigned, bool IsSaturated, bool HasUnsignedPadding)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a7086a2258539bb56b6ecead61d15a6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::operator!= (<a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> Other)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a74164b0a3bd99d34d93470f7563c8f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::operator== (<a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> Other)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fitsInFloatSemantics() {#ab30aaf95486d0b2aac87f3d9e1e450e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::fitsInFloatSemantics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; FloatSema)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this fixed-point semantic with its value bits interpreted as an integer can fit in the given floating point semantic without overflowing to infinity.</p>


<p>For example, a signed 8-bit fixed-point semantic has a maximum and minimum integer representation of 127 and -128, respectively. If both of these values can be represented (possibly inexactly) in the floating point semantic without overflowing, this returns true.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ae7ca9ff56521cc2e2c51d96ad9a6005c">llvm::APFixedPoint::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a1c4398afd568f2c31f81dcecad35ef7b">llvm::APFixedPoint::getMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a82cc2364c94c614756f6013fd3fb902a">llvm::APFixedPoint::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>, <a href="#a05ad0838e692b5cdc021f49da8343187">isSigned</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa054516d40647594fd6e9e436a9aa308f">llvm::APFloatBase::opOverflow</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1289beadf5d399fa4a2c64e18903ac90">llvm::APFloatBase::rmNearestTiesToAway</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a>.</p>

</div>
</div>

### getCommonSemantics() {#a6e44daa940bc6479c419855e43d5f765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::FixedPointSemantics::getCommonSemantics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> that allows for calculating the full precision semantic that can precisely represent the precision and ranges of both input values.</p>


<p>This does not compute the resulting semantics for a given binary operation.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a>, <a href="#aaea346c0aab9c7f4608ce41a4c217fa5">getLsbWeight</a>, <a href="#a232037d122854fa07a16938f469c8921">getMsbWeight</a>, <a href="#acf36b3741d49fd77bfca7057fb8e2f3f">hasSignOrPaddingBit</a>, <a href="#a516540ad4950d71de2266507041b9c6e">hasUnsignedPadding</a>, <a href="#a56da39babaf07b5638145d232de64949">isSaturated</a>, <a href="#a05ad0838e692b5cdc021f49da8343187">isSigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#aa663208669ad36fe54f6eb540b5bbf9b">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a05b24458637907fb6e27a842cc8dc0fc">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#ac1e07222d14c1bc6e996ca85ca126e93">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateMul</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#ae314a9eee47df21fd46102d80f666b4d">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateSub</a>.</p>

</div>
</div>

### getIntegralBits() {#a60827722079f839f42712dacafce3695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::getIntegralBits ()</td>
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

<p>Return the number of integral bits represented by these semantics.</p>


<p>These are separate from the fractional bits and do not include the sign or padding bit.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a232037d122854fa07a16938f469c8921">getMsbWeight</a> and <a href="#acf36b3741d49fd77bfca7057fb8e2f3f">hasSignOrPaddingBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>.</p>

</div>
</div>

### getLsbWeight() {#aaea346c0aab9c7f4608ce41a4c217fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::FixedPointSemantics::getLsbWeight ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a> and <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a>.</p>

</div>
</div>

### getMsbWeight() {#a232037d122854fa07a16938f469c8921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::FixedPointSemantics::getMsbWeight ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a>, <a href="#a60827722079f839f42712dacafce3695">getIntegralBits</a> and <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a>.</p>

</div>
</div>

### getScale() {#a5eb21a8a338a43390965253fb71d152d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::getScale ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aea9c92a6e83154b310262cc88a986a76">isValidLegacySema</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a00109923471ab72b20f0959d8eb230b9">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFloating</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a> and <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a>.</p>

</div>
</div>

### getWidth() {#a2f3dab29dd773a1faa002a701261db99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::getWidth ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a> and <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a>.</p>

</div>
</div>

### hasSignOrPaddingBit() {#acf36b3741d49fd77bfca7057fb8e2f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::hasSignOrPaddingBit ()</td>
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

<p>return true if the first bit doesn't have a strictly positive weight</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a> and <a href="#a60827722079f839f42712dacafce3695">getIntegralBits</a>.</p>

</div>
</div>

### hasUnsignedPadding() {#a516540ad4950d71de2266507041b9c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::hasUnsignedPadding ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a27e29ec6d1cfc7d82adcefe7fef1cf56">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShl</a> and <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a>.</p>

</div>
</div>

### isSaturated() {#a56da39babaf07b5638145d232de64949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::isSaturated ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a27e29ec6d1cfc7d82adcefe7fef1cf56">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShl</a>, <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a>.</p>

</div>
</div>

### isSigned() {#a05ad0838e692b5cdc021f49da8343187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::isSigned ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a00109923471ab72b20f0959d8eb230b9">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFloating</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a0a1c9934f39747a96a2b6b42d0bec03e">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a27e29ec6d1cfc7d82adcefe7fef1cf56">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a5dce930d90c103945d94b3aff2ea5653">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShr</a>, <a href="#ab30aaf95486d0b2aac87f3d9e1e450e3">fitsInFloatSemantics</a>, <a href="#a6e44daa940bc6479c419855e43d5f765">getCommonSemantics</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a>.</p>

</div>
</div>

### isValidLegacySema() {#aea9c92a6e83154b310262cc88a986a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedPointSemantics::isValidLegacySema ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the Semantic follow the requirements of an older more limited version of this class.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a5eb21a8a338a43390965253fb71d152d">getScale</a> and <a href="#a90af0fe3872d1de7bef6b8d729aa81fc">print</a>.</p>

</div>
</div>

### print() {#a90af0fe3872d1de7bef6b8d729aa81fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FixedPointSemantics::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print semantics for debug purposes.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#aaea346c0aab9c7f4608ce41a4c217fa5">getLsbWeight</a>, <a href="#a232037d122854fa07a16938f469c8921">getMsbWeight</a>, <a href="#a5eb21a8a338a43390965253fb71d152d">getScale</a>, <a href="#a2f3dab29dd773a1faa002a701261db99">getWidth</a> and <a href="#aea9c92a6e83154b310262cc88a986a76">isValidLegacySema</a>.</p>

</div>
</div>

### setSaturated() {#a4aee131cca702391b24efc6d75a6775a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FixedPointSemantics::setSaturated (bool Saturated)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### toOpaqueInt() {#ae2929b0e3eeba003376ef5515a006882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::FixedPointSemantics::toOpaqueInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the semantics to a 32-bit unsigned integer.</p>


<p>The result is dependent on the host endianness and not stable across LLVM versions. See <a href="#a0bd07c34ae344bc593539aa2adbb9ad2">getFromOpaqueInt()</a> to convert it back to a <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> object.</p>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasUnsignedPadding {#a811d85ed575e2e3d1c7577fbe1af2f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::HasUnsignedPadding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### IsSaturated {#a951cf00fa5e0dd1a04643b1b0f630526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::IsSaturated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### IsSigned {#a6f0b43bc6965ab65054313b6b3482e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::IsSigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### LsbWeight {#a9d75945d7a896ec9bda6e6259de0865a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">signed int llvm::FixedPointSemantics::LsbWeight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### Width {#a69581f6a6b95d54065e0a0ba69562fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFromOpaqueInt() {#a0bd07c34ae344bc593539aa2adbb9ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::FixedPointSemantics::getFromOpaqueInt (uint32_t I)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> object from an integer created via <a href="#ae2929b0e3eeba003376ef5515a006882">toOpaqueInt()</a>.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### GetIntegerSemantics() {#aebc9b19a86db06690ffcc4904907e8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::FixedPointSemantics::GetIntegerSemantics (unsigned Width, bool IsSigned)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> for an integer type.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Reference <a href="#ae59a8566a4fccd51331fdfcbe2cba59a">FixedPointSemantics</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a1d99db3b205c5c656e11e25cc98b9917">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#ac2cb8d79fa94ae788233f1af991fd9c4">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateIntegerToFixed</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a738a0be04b7721972a680302c07c12bb">llvm::APFixedPoint::getFromIntValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### LsbWeightBitWidth {#a58a5fd6a1b76c5697876a2674a08ed00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::LsbWeightBitWidth = 13</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### WidthBitWidth {#a12dbb2fca569d938f330154451a67b24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedPointSemantics::WidthBitWidth = 16</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
