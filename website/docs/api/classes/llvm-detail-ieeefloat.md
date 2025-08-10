---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/ieeefloat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IEEEFloat` Class



## Declaration

<div class="doxyDeclaration">
class llvm::detail::IEEEFloat { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ec5cfce4a8b6896193c822f2dc5894">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to compute a hash code for an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> value. <a href="#a87ec5cfce4a8b6896193c822f2dc5894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the exponent of the internal representation of the <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#a835817b2c14c68ccbb8da31e459b4e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f1d8bb5b89fd73a09dc011ce20b1b3">scalbn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns: X * 2^Exp for integral exponents. <a href="#ad8f1d8bb5b89fd73a09dc011ce20b1b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66faf2a98cef6c52d3778071dacb5699">frexp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14d1d39e4c23e0fa460321afead1b77">operator==</a> (const IEEEFloat &amp;) const =delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The definition of equality is not straightforward for floating point, so we won't use operator==. <a href="#ad14d1d39e4c23e0fa460321afead1b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ba4af33319080da8715ee47901f471">operator=</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad8214dd85f8138c04677fa3b27e6f5">operator=</a> (IEEEFloat &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e119adf6aa7c995f76726da74ba3b1">needsCleanup</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this instance allocated memory. <a href="#a21e119adf6aa7c995f76726da74ba3b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296ec">cmpResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3482cd2270813afec01825fd5ba575d6">compare</a> (const IEEEFloat &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE comparison with another floating point number (NaNs compare unordered, 0==-0). <a href="#a3482cd2270813afec01825fd5ba575d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bf292e85a0c04c818ddfd734533769">bitwiseIsEqual</a> (const IEEEFloat &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise comparison for equality (QNaNs compare equal, 0!=-0). <a href="#a96bf292e85a0c04c818ddfd734533769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032bb65d786b0169e342f753901000e0">convertToHexString</a> (char *dst, unsigned int hexDigits, bool upperCase, roundingMode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write out a hexadecimal representation of the floating point value to DST, which must be of sufficient size, in the C99 form [-]0xh.hhhhp[+-]d. <a href="#a032bb65d786b0169e342f753901000e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462d954821ce6386847608cf825ed480">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned FormatPrecision=0, unsigned FormatMaxPadding=3, bool TruncateZero=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this value into a decimal string. <a href="#a462d954821ce6386847608cf825ed480">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a> (APFloat *inv) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this value has an exact multiplicative inverse, store it in inv and return true. <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a250ae807ddec8d1d8881d01a7d24dc44">getExactLog2Abs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85740a44b2f435c6844cf491be1e20e">getExactLog2</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296ec">cmpResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a> (const IEEEFloat &amp;) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;const fltSemantics &amp; S&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c7ee7bff7364d324f6f5587a068c636">convertIEEEFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab66e545a92e39e10147e4bc4051a50e">convertHalfAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac60d2d2089f65a058f032f046865156">convertBFloatAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cfdc755ac2f56e6e411af2bcdbbd19">convertFloatAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe17f506923f7c95d28318fa9028ff0">convertDoubleAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e2727352b38e298d03be5303be713c">convertQuadrupleAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5115e659f3b633dd8121ac2197f64c4">convertF80LongDoubleAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc3d9a8207a9c9ec022cbda4998b447">convertPPCDoubleDoubleLegacyAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809b3f84167e11c51a96fc78cd3bc023">convertFloat8E5M2APFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e79eda0397356b9619c56ba49a96d20">convertFloat8E5M2FNUZAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532330e6b6cd58a1bdc1787c422caa45">convertFloat8E4M3APFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1797eba72386e1a0a3b76d93d76d8ab9">convertFloat8E4M3FNAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50ad6d4f8f339eb346fc221790b2e96">convertFloat8E4M3FNUZAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0c06cbdbf82b8f0c74b83d04584e0b">convertFloat8E4M3B11FNUZAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69cc11ab2abf6cd9af6402f28aff6bdf">convertFloat8E3M4APFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9902547dea99804623c76bea596588">convertFloatTF32APFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9e7694521da2cde73188691b2033d8">convertFloat8E8M0FNUAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ced3467d9c3d5a8065b70078e6bfd8c">convertFloat6E3M2FNAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18056d15545ae90085f8a3946056a83e">convertFloat6E2M3FNAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42688d7b4d29c9632ff7817e73c8c29a">convertFloat4E2M1FNAPFloatToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3671b28fbd8c14742a464a377d42fb05">initFromAPInt</a> (const fltSemantics *Sem, const APInt &amp;api)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Treat api as containing the bits of a floating point number. <a href="#a3671b28fbd8c14742a464a377d42fb05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;const fltSemantics &amp; S&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c4f7e82caee0637376f7ee84d828d26">initFromIEEEAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3295d8e172a0bb1881c1fa39b4bda3f">initFromHalfAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1976d4095f12c8a6822e46b519f010f">initFromBFloatAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e479ef8b1aa4d435a0187442a9ebad">initFromFloatAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e13229e5b6049e28e1ac4fdd0c11c91">initFromDoubleAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72eac6cf5de5786d9fa1e8913e900ffe">initFromQuadrupleAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5dc8751c3a36617ecee652ddb8475c">initFromF80LongDoubleAPInt</a> (const APInt &amp;api)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Integer bit is explicit in this format. <a href="#a3e5dc8751c3a36617ecee652ddb8475c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e4c4e96addb18fd22e0c48b6689141">initFromPPCDoubleDoubleLegacyAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f75b9fd48e6bfcb448cdb81c5184575">initFromFloat8E5M2APInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede279d57f02bd3c636b2800682c0c76">initFromFloat8E5M2FNUZAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0214ce0842eeb751e8be992c241e893">initFromFloat8E4M3APInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620b2163434d66762a9efc524ba1fe3d">initFromFloat8E4M3FNAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fdf67b6e8bddaff78a8a1ce07f5815">initFromFloat8E4M3FNUZAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ef8493c2ac631a94a099f193f75cf7">initFromFloat8E4M3B11FNUZAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337327ab142fb73dbf072dbf725728d7">initFromFloat8E3M4APInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c4a1dde7bba50e8ce8dc1fa17fc2c5">initFromFloatTF32APInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82c42759ca0404085f192ae47da0b53">initFromFloat8E8M0FNUAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79309307c84bae42f7b7c2fed1fbc3e9">initFromFloat6E3M2FNAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b8f25c96f75c88656097940062ae6d">initFromFloat6E2M3FNAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801c627a690860660dad8bd53813e294">initFromFloat4E2M1FNAPInt</a> (const APInt &amp;api)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2bfeff1768f6f990fe3c29e76dbd19">assign</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f40e5a3b1117b311b2c92db29e1b7d">copySignificand</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a9e00e12f036f90af9bfacb6c65aac">freeSignificand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0fdd2a9fa34892f8753fd37965672d">semantics</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note: this must be the first data member. <a href="#a4c0fdd2a9fa34892f8753fd37965672d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union llvm::detail::IEEEFloat::Significand</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f183ecb454e34a393375eb679a9007">significand</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6516d416a36a2fb0ad78c9d099ccadaf">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463959ead3aa59e8766049cc52f51b09">exponent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The signed unbiased exponent of the value. <a href="#a463959ead3aa59e8766049cc52f51b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44">fltCategory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3178acae8098327101b0781b396d41af">category</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What kind of floating point number this is. <a href="#a3178acae8098327101b0781b396d41af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fdeea8fcb0faa9196f676db553b687">sign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sign bit of the number. <a href="#ad2fdeea8fcb0faa9196f676db553b687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> (const fltSemantics &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e77cbb7cccf5f258defe80863f8a915">IEEEFloat</a> (const fltSemantics &amp;, integerPart)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b994f89fde604079654b5a5204f78b7">IEEEFloat</a> (const fltSemantics &amp;, uninitializedTag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0510dd366fe77866e27c1ed87298ca42">IEEEFloat</a> (const fltSemantics &amp;, const APInt &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa9aea599b4c595c1ed9b8aa676895d">IEEEFloat</a> (double d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc40250b6f1e913ab361a17c2ca02e43">IEEEFloat</a> (float f)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a67da4467c149e6ea2c2dd37410914e">IEEEFloat</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1285ee29a226da29aabc677446278836">IEEEFloat</a> (IEEEFloat &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba6734c74d2db57c8b828cb87822b97">~IEEEFloat</a> ()</td>
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

## Arithmetic Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa059590a2b13eab35037154841e81c">add</a> (const IEEEFloat &amp;, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42066115d96555269402c2393431c527">subtract</a> (const IEEEFloat &amp;, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f299d5597a5c8dfa677a1989ae339c">multiply</a> (const IEEEFloat &amp;, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379365c0d805bb6c8e75120fcef1c7fd">divide</a> (const IEEEFloat &amp;, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a> (const IEEEFloat &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE remainder. <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a> (const IEEEFloat &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>C fmod, or llvm frem. <a href="#a08b873c60c5bdb77993fbe575d54ad29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab102c7db7b7fa823f866cc4ce9519a0b">fusedMultiplyAdd</a> (const IEEEFloat &amp;, const IEEEFloat &amp;, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a> (roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7488323ce38642acc4938efe0bcc82">next</a> (bool nextDown)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R 5.3.1: nextUp/nextDown. <a href="#abe7488323ce38642acc4938efe0bcc82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Sign operations. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af209287742aa0cc1a91160768251986a">changeSign</a> ()</td>
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

## Conversions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee22783789ff4a16e831ce3edd759766">convert</a> (const fltSemantics &amp;, roundingMode, bool *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aee22783789ff4a16e831ce3edd759766">IEEEFloat::convert</a> - convert a value of one floating point type to another. <a href="#aee22783789ff4a16e831ce3edd759766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c4dc333adfdd30afcce056b9b97484">convertToInteger</a> (MutableArrayRef&lt; integerPart &gt;, unsigned int, bool, roundingMode, bool *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135db5ce97b04855e9e8f44d26d30d43">convertFromAPInt</a> (const APInt &amp;, bool, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da3eaf2f546dd6c6f631f2e2c2436a2">convertFromSignExtendedInteger</a> (const integerPart *, unsigned int, bool, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eea8656eab72e6218242f811ec6fc1f">convertFromZeroExtendedInteger</a> (const integerPart *, unsigned int, bool, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d9194822bc4e6c84bc71a8ea89db5c">convertFromString</a> (StringRef, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e2aa177d7bde390e924b99b0f1092b">bitcastToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d43c52f31748261cbdd0e2b0bbad94a">convertToDouble</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee96d60e840c18bbd08398261142ad7">convertToFloat</a> () const</td>
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

## IEEE-754R 5.7.2 General operations. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R isSignMinus: Returns true if and only if the current value is negative. <a href="#a35a8501e30440512c90175d5c9da1e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f5d65ea623492751a48ee350032faf">isNormal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R isNormal: Returns true if and only if the current value is normal. <a href="#a53f5d65ea623492751a48ee350032faf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the current value is zero, subnormal, or normal. <a href="#a6c13a0ae341758009ad824f46c05a865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the float is plus or minus zero. <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R isSubnormal(): Returns true if and only if the float is a denormal. <a href="#af24d88dc1da69292f443d3a4cd0bbce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55b5d9082d1c4466113b3223464759f">isInfinity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R isInfinite(): Returns true if and only if the float is infinity. <a href="#ac55b5d9082d1c4466113b3223464759f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the float is a quiet or signaling NaN. <a href="#a3abc0e386496d9bed38ce2836e8129ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the float is a signaling NaN. <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Simple Queries Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44">fltCategory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e452a21ca3258bb1b33b521e0ec332d">getCategory</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6440b9e1ccd1be8461c1f338fe96a90">getSemantics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1580863be673e7462a9b6fe0716c9b09">isNonZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabede636da031cc9d94da7dc4e1074a8">isPosZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f0e55d618f91f704acd7d7c6c05925">isNegZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af87f3f592d4275a826af6f5ff9cc960a">isSmallest</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the number has the smallest possible non-zero magnitude in the current semantics. <a href="#af87f3f592d4275a826af6f5ff9cc960a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea95ec18f93073627398d4727840503">isSmallestNormalized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the smallest (by magnitude) normalized finite number in the given semantics. <a href="#a5ea95ec18f93073627398d4727840503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ad336dde9a51ae13b2d854313a0693">isLargest</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the number has the largest possible finite magnitude in the current semantics. <a href="#a65ad336dde9a51ae13b2d854313a0693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30ac008fd033ba8fd7c5d144f5b084a">isInteger</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if and only if the number is an exact integer. <a href="#aa30ac008fd033ba8fd7c5d144f5b084a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fa13064b49084660328c4ef8b1eca7">significandParts</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2466e9a2f3c7e93c6a47154c9d5f24ac">significandParts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779f203bd839df13e87a9e935c346126">partCount</a> () const</td>
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

## Special value setters. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24207471f23ede2b08d380dadd5898cf">makeLargest</a> (bool Neg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this number the largest magnitude normal number in the given semantics. <a href="#a24207471f23ede2b08d380dadd5898cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d72a16f5c9b1344026b49a271878059">makeSmallest</a> (bool Neg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this number the smallest magnitude denormal number in the given semantics. <a href="#a4d72a16f5c9b1344026b49a271878059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af36259c05fe6d814df34aa9932c9db">makeNaN</a> (bool SNaN=false, bool Neg=false, const APInt *fill=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eab9b80c0530c91c8075b6e461db19f">makeInf</a> (bool Neg=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae278d92a6dd0133695b2c02d9a6d39d7">makeZero</a> (bool Neg=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a> (bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the smallest (by magnitude) normalized finite number in the given semantics. <a href="#a97eaebabb01bb9d32ee07f5459be3a60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Significand operations. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a370529bdbc530901fd4a3e96c9d255">addSignificand</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea25853bb45b56ab183ad21b3df286bc">subtractSignificand</a> (const IEEEFloat &amp;, integerPart)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5eb7124fff613f28f29baec6817cba">addOrSubtractSignificand</a> (const IEEEFloat &amp;, bool subtract)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3955bbaaaaab1a6754f21fb457d14dfe">multiplySignificand</a> (const IEEEFloat &amp;, IEEEFloat, bool ignoreAddend=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340afe48fd523d6d8d600e57f5a0ad7b">multiplySignificand</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830975d21109f3167038022e54b7e815">divideSignificand</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad624a7cf693f4e4ea2825306d11d7145">incrementSignificand</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094b88bc5d59b99f57778d0c4fd876f8">initialize</a> (const fltSemantics *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1570082ddea93e37066b0ab5f1601f">shiftSignificandLeft</a> (unsigned int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99e74614f30740d1f7ee7a895d3f635">shiftSignificandRight</a> (unsigned int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d15735d28a2b82e60c750aafc18e65">significandLSB</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af166256fdd1bb98c94b596c5411affa8">significandMSB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20711c8d468e3259b23fe61951c1c62">zeroSignificand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac969a9204dd41d25bcea6d9fc9082afd">getNumHighBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b374b530c981d666d4d1fa33130041">isSignificandAllOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the significand excluding the integral bit is all ones. <a href="#ab6b374b530c981d666d4d1fa33130041">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45919cc129da59349234e1d7e5882590">isSignificandAllOnesExceptLSB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfe6232ce89a5baaa058647a6b08ecc">isSignificandAllZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the significand excluding the integral bit is all zeros. <a href="#a2dfe6232ce89a5baaa058647a6b08ecc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bae2b93152f952d3054102bf94a759">isSignificandAllZerosExceptMSB</a> () const</td>
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

## Arithmetic on special values. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d03e4118419b71fc529cc95b9d1c2e">addOrSubtractSpecials</a> (const IEEEFloat &amp;, bool subtract)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f892a42e87b20bad75921dcdd47bce">divideSpecials</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4bfeef15929068050babd3efa166865">multiplySpecials</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94be750b823117121a9659665a46a7ab">modSpecials</a> (const IEEEFloat &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99587d671ade3611b654e0617e7764a">remainderSpecials</a> (const IEEEFloat &amp;)</td>
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

## Miscellany Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac27aec3e1f120f97ff86f50bc1768c">convertFromStringSpecials</a> (StringRef str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554952f9ab2530040d61115f8b1f1533">normalize</a> (roundingMode, lostFraction)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcad9d05d27878ec78097aa5387d14a8">addOrSubtract</a> (const IEEEFloat &amp;, roundingMode, bool subtract)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0dc4f3568361be672a4e9c00a706402">handleOverflow</a> (roundingMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700605f43d59ce71cccdc99d374b4b34">roundAwayFromZero</a> (roundingMode, lostFraction, unsigned int) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9146e5637d0b7584a12f8421bb25106a">convertToSignExtendedInteger</a> (MutableArrayRef&lt; integerPart &gt;, unsigned int, bool, roundingMode, bool *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480428f9df78aa2323a08639ddb8db7f">convertFromUnsignedParts</a> (const integerPart *, unsigned int, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392e52dab34bbe1ebff4ede602c5b546">convertFromHexadecimalString</a> (StringRef, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8d698e353249bb569e0904ebb49dd7">convertFromDecimalString</a> (StringRef, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9792505f5f89e753f24ad7809abfda7d">convertNormalToHexString</a> (char *, unsigned int, bool, roundingMode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88389f0c9674a41bafb5349ae9d059f">roundSignificandWithExponent</a> (const integerPart *, unsigned int, int, roundingMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6516d416a36a2fb0ad78c9d099ccadaf">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70be3f6ed16fe1689f05c4496098c381">exponentNaN</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6516d416a36a2fb0ad78c9d099ccadaf">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97336b20400f8fe7117126e62e8f34a7">exponentInf</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6516d416a36a2fb0ad78c9d099ccadaf">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519f8d14a1f53d35cb938fe3ad8c7da4">exponentZero</a> () const</td>
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


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<div class="doxySectionDef">

## Friends

### frexp {#a66faf2a98cef6c52d3778071dacb5699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; X, int &amp; Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4815 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca4c1772918997b32aa846df0cf32ca5f1">llvm::APFloatBase::IEK_Inf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca23abe3c9be234401b670eed6856bc850">llvm::APFloatBase::IEK_NaN</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca92ab3f7aab17e3be64ddf42a7fa88cd0">llvm::APFloatBase::IEK_Zero</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d9d5328bc7a7ba4906fb7a366cc9a32a098753f8980036f4b936e3d4b6997111">llvm::Quiet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7757f52e61c8e086d79bdd166f50bb02">llvm::scalbn</a>.</p>

</div>
</div>

### hash\_value {#a87ec5cfce4a8b6896193c822f2dc5894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; Arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overload to compute a hash code for an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> value.</p>


<p>Note that the use of hash codes for floating point values is in general frought with peril. Equality is hard to define for these values. For example, should negative and positive zero hash to different codes? Are they equal or not? This hash value implementation specifically emphasizes producing different codes for different inputs in order to be used in canonicalization and memoization. As such, equality is bitwiseIsEqual, and 0 != -0.</p>


<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3498 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a> and <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a>.</p>

</div>
</div>

### ilogb {#a835817b2c14c68ccbb8da31e459b4e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend int <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; Arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the exponent of the internal representation of the <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>


<p>Because the radix of <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> is 2, this is equivalent to floor(log2(x)). For special <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> values, this returns special error codes:</p>


<p>NaN -&gt; <span class="doxyComputerOutput">IEK_NaN</span> 0 -&gt; <span class="doxyComputerOutput">IEK_Zero</span> Inf -&gt; <span class="doxyComputerOutput">IEK_Inf</span></p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4776 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ac6440b9e1ccd1be8461c1f338fe96a90">getSemantics</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca4c1772918997b32aa846df0cf32ca5f1">llvm::APFloatBase::IEK_Inf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca23abe3c9be234401b670eed6856bc850">llvm::APFloatBase::IEK_NaN</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca92ab3f7aab17e3be64ddf42a7fa88cd0">llvm::APFloatBase::IEK_Zero</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a>, <a href="#ac55b5d9082d1c4466113b3223464759f">isInfinity</a>, <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="#a66faf2a98cef6c52d3778071dacb5699">frexp</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a> and <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>.</p>

</div>
</div>

### scalbn {#ad8f1d8bb5b89fd73a09dc011ce20b1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> X, int Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RoundingMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns: X * 2^Exp for integral exponents.</p>

<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4794 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a90ba4af33319080da8715ee47901f471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IEEEFloat &amp; llvm::detail::IEEEFloat::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>

</div>
</div>

### operator=() {#a3ad8214dd85f8138c04677fa3b27e6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IEEEFloat &amp; llvm::detail::IEEEFloat::operator= (<a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;&amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1010 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a081a32b758ca3c58f2a937b3d04ca218">llvm::semBogus</a>.</p>

</div>
</div>

### operator==() {#ad14d1d39e4c23e0fa460321afead1b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;)</td>
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

<p>The definition of equality is not straightforward for floating point, so we won't use operator==.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> one of the following, or write whatever it is you really mean.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bitwiseIsEqual() {#a96bf292e85a0c04c818ddfd734533769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::bitwiseIsEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitwise comparison for equality (QNaNs compare equal, 0!=-0).</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>.</p>

</div>
</div>

### compare() {#a3482cd2270813afec01825fd5ba575d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::cmpResult llvm::detail::IEEEFloat::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE comparison with another floating point number (NaNs compare unordered, 0==-0).</p>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2459 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a5ad004323975537528a08db31f8e7246">llvm::detail::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3ccb8f46dd17053e9aaa648b3ae42279">llvm::detail::cmpLessThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a9f7251c22383564b2db88f6aba8410c8">llvm::detail::cmpUnordered</a>, <a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp/#a628267865ea4996936b227ed15b3f1eb">PackCategoriesIntoKey</a>.</p>


<p>Referenced by <a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a>, <a href="#aa30ac008fd033ba8fd7c5d144f5b084a">isInteger</a> and <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a>.</p>

</div>
</div>

### compareAbsoluteValue() {#a0832f8a0b59ae97b62e74839c83898b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::cmpResult llvm::detail::IEEEFloat::compareAbsoluteValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1537 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a5ad004323975537528a08db31f8e7246">llvm::detail::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3ccb8f46dd17053e9aaa648b3ae42279">llvm::detail::cmpLessThan</a>, <a href="#a3482cd2270813afec01825fd5ba575d6">compare</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a3dd574e063a1cfeaa96175c5f9c4afa9">llvm::APInt::tcCompare</a>.</p>


<p>Referenced by <a href="#a3482cd2270813afec01825fd5ba575d6">compare</a> and <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>.</p>

</div>
</div>

### convertToHexString() {#a032bb65d786b0169e342f753901000e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::convertToHexString (char * dst, unsigned int hexDigits, bool upperCase, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write out a hexadecimal representation of the floating point value to DST, which must be of sufficient size, in the C99 form [-]0xh.hhhhp[+-]d.</p>


<p>Return the number of characters written, excluding the terminating NUL.</p>


<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3349 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b93a45027abbb1dbbebca1698cabfec">llvm::infinityL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62a8177c2603b1c5964ea7d75dcf1fe1">llvm::infinityU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54f79b4309a23e693c3d0e2465f7fc9d">llvm::NaNL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9d904f786caf826365f9dc2eeb71e1">llvm::NaNU</a>.</p>

</div>
</div>

### getExactInverse() {#a21d5827d6fe2592fea86c1f7bf386fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::getExactInverse (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> * inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this value has an exact multiplicative inverse, store it in inv and return true.</p>

<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4522 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a379365c0d805bb6c8e75120fcef1c7fd">divide</a>, <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ac3a5f03151dfa723fbbf0afab1cdd7ba">llvm::detail::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>.</p>

</div>
</div>

### getExactLog2() {#ae85740a44b2f435c6844cf491be1e20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY int llvm::detail::IEEEFloat::getExactLog2 ()</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a250ae807ddec8d1d8881d01a7d24dc44">getExactLog2Abs</a> and <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a>.</p>

</div>
</div>

### getExactLog2Abs() {#a250ae807ddec8d1d8881d01a7d24dc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::detail::IEEEFloat::getExactLog2Abs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4551 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">llvm::APInt::APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#a250ae807ddec8d1d8881d01a7d24dc44">getExactLog2Abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74f807e3ffa9720347aa991a0877eba7">llvm::isFinite</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="#ae85740a44b2f435c6844cf491be1e20e">getExactLog2</a> and <a href="#a250ae807ddec8d1d8881d01a7d24dc44">getExactLog2Abs</a>.</p>

</div>
</div>

### needsCleanup() {#a21e119adf6aa7c995f76726da74ba3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::needsCleanup ()</td>
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

<p>Returns whether this instance allocated memory.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### toString() {#a462d954821ce6386847608cf825ed480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned FormatPrecision=0, unsigned FormatMaxPadding=3, bool TruncateZero=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts this value into a decimal string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FormatPrecision</td>
<td class="doxyParamItemDescription"><p>The maximum number of digits of precision to output. If there are fewer digits available, zero padding will not be used unless the value is integral and small enough to be expressed in FormatPrecision digits. 0 means to use the natural precision of the number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FormatMaxPadding</td>
<td class="doxyParamItemDescription"><p>The maximum number of zeros to consider inserting before falling back to scientific notation. 0 means to always use scientific notation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TruncateZero</td>
<td class="doxyParamItemDescription"><p>Indicate whether to remove the trailing zero in fraction part or not. Also setting this parameter to false forcing producing of output more similar to default printf behavior. Specifically the lower e is used as exponent delimiter and exponent always contains no less than two digits.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Number Precision MaxPadding Result</p>


<hr/>


<p>1.01E+4 5 2 10100 1.01E+4 4 2 1.01E+4 1.01E+4 5 1 1.01E+4 1.01E-2 5 2 0.0101 1.01E-2 4 2 0.0101 1.01E-2 4 1 1.01E-2</p>


<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4479 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a> and <a href="#a462d954821ce6386847608cf825ed480">toString</a>.</p>


<p>Referenced by <a href="#a462d954821ce6386847608cf825ed480">toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assign() {#aba2bfeff1768f6f990fe3c29e76dbd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::assign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertBFloatAPFloatToAPInt() {#aac60d2d2089f65a058f032f046865156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertBFloatAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3683 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertDoubleAPFloatToAPInt() {#a2fe17f506923f7c95d28318fa9028ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertDoubleAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3673 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertF80LongDoubleAPFloatToAPInt() {#ae5115e659f3b633dd8121ac2197f64c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertF80LongDoubleAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3522 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat4E2M1FNAPFloatToAPInt() {#a42688d7b4d29c9632ff7817e73c8c29a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat4E2M1FNAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3748 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat6E2M3FNAPFloatToAPInt() {#a18056d15545ae90085f8a3946056a83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat6E2M3FNAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3743 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat6E3M2FNAPFloatToAPInt() {#a4ced3467d9c3d5a8065b70078e6bfd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat6E3M2FNAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3738 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E3M4APFloatToAPInt() {#a69cc11ab2abf6cd9af6402f28aff6bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E3M4APFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3723 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E4M3APFloatToAPInt() {#a532330e6b6cd58a1bdc1787c422caa45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E4M3APFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3703 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E4M3B11FNUZAPFloatToAPInt() {#acc0c06cbdbf82b8f0c74b83d04584e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E4M3B11FNUZAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3718 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E4M3FNAPFloatToAPInt() {#a1797eba72386e1a0a3b76d93d76d8ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E4M3FNAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3708 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E4M3FNUZAPFloatToAPInt() {#ab50ad6d4f8f339eb346fc221790b2e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E4M3FNUZAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3713 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E5M2APFloatToAPInt() {#a809b3f84167e11c51a96fc78cd3bc023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E5M2APFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3693 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E5M2FNUZAPFloatToAPInt() {#a3e79eda0397356b9619c56ba49a96d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E5M2FNUZAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3698 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloat8E8M0FNUAPFloatToAPInt() {#aec9e7694521da2cde73188691b2033d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloat8E8M0FNUAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3733 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloatAPFloatToAPInt() {#a60cfdc755ac2f56e6e411af2bcdbbd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloatAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3678 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFloatTF32APFloatToAPInt() {#a1e9902547dea99804623c76bea596588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertFloatTF32APFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3728 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertHalfAPFloatToAPInt() {#aab66e545a92e39e10147e4bc4051a50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertHalfAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3688 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertIEEEFloatToAPInt() {#a3c7ee7bff7364d324f6f5587a068c636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;const fltSemantics &amp; S&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertIEEEFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3602 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertPPCDoubleDoubleLegacyAPFloatToAPInt() {#aecc3d9a8207a9c9ec022cbda4998b447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertPPCDoubleDoubleLegacyAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3552 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertQuadrupleAPFloatToAPInt() {#ae9e2727352b38e298d03be5303be713c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::convertQuadrupleAPFloatToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3668 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### copySignificand() {#a25f40e5a3b1117b311b2c92db29e1b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::copySignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### freeSignificand() {#af2a9e00e12f036f90af9bfacb6c65aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::freeSignificand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromAPInt() {#a3671b28fbd8c14742a464a377d42fb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> * Sem, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Treat api as containing the bits of a floating point number.</p>

<p>Declaration at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4082 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromBFloatAPInt() {#af1976d4095f12c8a6822e46b519f010f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromBFloatAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4029 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromDoubleAPInt() {#a8e13229e5b6049e28e1ac4fdd0c11c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromDoubleAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4021 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromF80LongDoubleAPInt() {#a3e5dc8751c3a36617ecee652ddb8475c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromF80LongDoubleAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Integer bit is explicit in this format.</p>


<p>Intel hardware (387 and later) does not support these bit patterns: exponent = all 1's, integer bit 0, significand 0 ("pseudoinfinity") exponent = all 1's, integer bit 0, significand nonzero ("pseudoNaN") exponent!=0 nor all 1's, integer bit 0 ("unnormal") exponent = 0, integer bit 1 ("pseudodenormal") At the moment, the first three are treated as NaNs, the last one as Normal.</p>


<p>Declaration at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3847 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat4E2M1FNAPInt() {#a801c627a690860660dad8bd53813e294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat4E2M1FNAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4077 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat6E2M3FNAPInt() {#a84b8f25c96f75c88656097940062ae6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat6E2M3FNAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4073 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat6E3M2FNAPInt() {#a79309307c84bae42f7b7c2fed1fbc3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat6E3M2FNAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4069 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E3M4APInt() {#a337327ab142fb73dbf072dbf725728d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E3M4APInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4061 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E4M3APInt() {#ae0214ce0842eeb751e8be992c241e893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E4M3APInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4045 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E4M3B11FNUZAPInt() {#a13ef8493c2ac631a94a099f193f75cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E4M3B11FNUZAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4057 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E4M3FNAPInt() {#a620b2163434d66762a9efc524ba1fe3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E4M3FNAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4049 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E4M3FNUZAPInt() {#a95fdf67b6e8bddaff78a8a1ce07f5815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E4M3FNUZAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4053 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E5M2APInt() {#a4f75b9fd48e6bfcb448cdb81c5184575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E5M2APInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4037 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E5M2FNUZAPInt() {#aede279d57f02bd3c636b2800682c0c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E5M2FNUZAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4041 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloat8E8M0FNUAPInt() {#ad82c42759ca0404085f192ae47da0b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloat8E8M0FNUAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3906 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloatAPInt() {#a75e479ef8b1aa4d435a0187442a9ebad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloatAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4025 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromFloatTF32APInt() {#a97c4a1dde7bba50e8ce8dc1fa17fc2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromFloatTF32APInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4065 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromHalfAPInt() {#aa3295d8e172a0bb1881c1fa39b4bda3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromHalfAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4033 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromIEEEAPInt() {#a0c4f7e82caee0637376f7ee84d828d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;const fltSemantics &amp; S&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromIEEEAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3935 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromPPCDoubleDoubleLegacyAPInt() {#a72e4c4e96addb18fd22e0c48b6689141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromPPCDoubleDoubleLegacyAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3878 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initFromQuadrupleAPInt() {#a72eac6cf5de5786d9fa1e8913e900ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initFromQuadrupleAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; api)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4017 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### category {#a3178acae8098327101b0781b396d41af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fltCategory llvm::detail::IEEEFloat::category</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>What kind of floating point number this is.</p>


<p>Only 2 bits are required, but VisualStudio incorrectly sign extends it. Using the extra bit keeps it from failing under VisualStudio.</p>


<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### exponent {#a463959ead3aa59e8766049cc52f51b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExponentType llvm::detail::IEEEFloat::exponent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The signed unbiased exponent of the value.</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### semantics {#a4c0fdd2a9fa34892f8753fd37965672d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics* llvm::detail::IEEEFloat::semantics</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Note: this must be the first data member.</p>


<p>The semantics that this value obeys.</p>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### sign {#ad2fdeea8fcb0faa9196f676db553b687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::sign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sign bit of the number.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### significand {#ae2f183ecb454e34a393375eb679a9007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::detail::IEEEFloat::Significand llvm::detail::IEEEFloat::significand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### \~IEEEFloat {#a4ba6734c74d2db57c8b828cb87822b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::~IEEEFloat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### IEEEFloat {#aaf97dd1294231bc3dd4d6e414f703baa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; ourSemantics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#ab3820f5dd38e5f39bca385d6a39d1779">llvm::fltSemantics::hasZero</a>, <a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a> and <a href="#ae278d92a6dd0133695b2c02d9a6d39d7">makeZero</a>.</p>


<p>Referenced by <a href="#a6aa059590a2b13eab35037154841e81c">add</a>, <a href="#a96bf292e85a0c04c818ddfd734533769">bitwiseIsEqual</a>, <a href="#a3482cd2270813afec01825fd5ba575d6">compare</a>, <a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a>, <a href="#a379365c0d805bb6c8e75120fcef1c7fd">divide</a>, <a href="#a66faf2a98cef6c52d3778071dacb5699">frexp</a>, <a href="#ab102c7db7b7fa823f866cc4ce9519a0b">fusedMultiplyAdd</a>, <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>, <a href="#a87ec5cfce4a8b6896193c822f2dc5894">hash_value</a>, <a href="#a0510dd366fe77866e27c1ed87298ca42">IEEEFloat</a>, <a href="#a5b994f89fde604079654b5a5204f78b7">IEEEFloat</a>, <a href="#a3a67da4467c149e6ea2c2dd37410914e">IEEEFloat</a>, <a href="#a8aa9aea599b4c595c1ed9b8aa676895d">IEEEFloat</a>, <a href="#adc40250b6f1e913ab361a17c2ca02e43">IEEEFloat</a>, <a href="#a1285ee29a226da29aabc677446278836">IEEEFloat</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#aa30ac008fd033ba8fd7c5d144f5b084a">isInteger</a>, <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>, <a href="#a84f299d5597a5c8dfa677a1989ae339c">multiply</a>, <a href="#a90ba4af33319080da8715ee47901f471">operator=</a>, <a href="#a3ad8214dd85f8138c04677fa3b27e6f5">operator=</a>, <a href="#ad14d1d39e4c23e0fa460321afead1b77">operator==</a>, <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a>, <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>, <a href="#ad8f1d8bb5b89fd73a09dc011ce20b1b3">scalbn</a> and <a href="#a42066115d96555269402c2393431c527">subtract</a>.</p>

</div>
</div>

### IEEEFloat {#a7e77cbb7cccf5f258defe80863f8a915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; ourSemantics, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ac3a5f03151dfa723fbbf0afab1cdd7ba">llvm::detail::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">llvm::detail::unit&lt; Period &gt;::value</a>.</p>

</div>
</div>

### IEEEFloat {#a5b994f89fde604079654b5a5204f78b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; ourSemantics, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567f">uninitializedTag</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>

</div>
</div>

### IEEEFloat {#a0510dd366fe77866e27c1ed87298ca42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; API)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4190 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>

</div>
</div>

### IEEEFloat {#a8aa9aea599b4c595c1ed9b8aa676895d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (double d)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4198 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#ac174a45e376a00ec9b2e9e8730f982c0">llvm::APInt::doubleToBits</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>

</div>
</div>

### IEEEFloat {#adc40250b6f1e913ab361a17c2ca02e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (float f)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4194 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a4b160c2704ee3819d8fda70345b4d19f">llvm::APInt::floatToBits</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7754dc9e65dfebb21bf7179fb690de9c">llvm::semIEEEsingle</a>.</p>

</div>
</div>

### IEEEFloat {#a3a67da4467c149e6ea2c2dd37410914e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>

</div>
</div>

### IEEEFloat {#a1285ee29a226da29aabc677446278836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::IEEEFloat::IEEEFloat (<a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;&amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a081a32b758ca3c58f2a937b3d04ca218">llvm::semBogus</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arithmetic

### add {#a6aa059590a2b13eab35037154841e81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>


<p>Referenced by <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### divide {#a379365c0d805bb6c8e75120fcef1c7fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::divide (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a078e0c7d94556af84b4e2264db4a1a84">llvm::detail::opInexact</a>.</p>


<p>Referenced by <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>.</p>

</div>
</div>

### fusedMultiplyAdd {#ab102c7db7b7fa823f866cc4ce9519a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::fusedMultiplyAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; multiplicand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; addend, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2326 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a078e0c7d94556af84b4e2264db4a1a84">llvm::detail::opInexact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#abbeaca18fca881e94be0a95c16f0c35d">llvm::detail::opUnderflow</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa354c1a394c0cd817844d448c89fd810">llvm::detail::rmTowardNegative</a>.</p>

</div>
</div>

### mod {#a08b873c60c5bdb77993fbe575d54ad29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::mod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>C fmod, or llvm frem.</p>

<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2288 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3ccb8f46dd17053e9aaa648b3ae42279">llvm::detail::cmpLessThan</a>, <a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ac3a5f03151dfa723fbbf0afab1cdd7ba">llvm::detail::rmNearestTiesToEven</a>, <a href="#ad8f1d8bb5b89fd73a09dc011ce20b1b3">scalbn</a> and <a href="#a42066115d96555269402c2393431c527">subtract</a>.</p>


<p>Referenced by <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a>.</p>

</div>
</div>

### multiply {#a84f299d5597a5c8dfa677a1989ae339c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::multiply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a078e0c7d94556af84b4e2264db4a1a84">llvm::detail::opInexact</a>.</p>

</div>
</div>

### next {#abe7488323ce38642acc4938efe0bcc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::next (bool nextDown)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE-754R 5.3.1: nextUp/nextDown.</p>


<p>IEEE-754R 2008 5.3.1: nextUp/nextDown.</p>


<p><em>NOTE</em> since nextDown(x) = -nextUp(-x), we only implement nextUp with appropriate sign switching before/after the computation.</p>


<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4596 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af209287742aa0cc1a91160768251986a">changeSign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eae574ed55b8fdf720e808271239fec3cc">llvm::FiniteOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af0ef7731beb4deaba4d953f79e1731d1">llvm::APFloat::hasSignificand</a>, <a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a>, <a href="#a65ad336dde9a51ae13b2d854313a0693">isLargest</a>, <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="#af87f3f592d4275a826af6f5ff9cc960a">isSmallest</a>, <a href="#a24207471f23ede2b08d380dadd5898cf">makeLargest</a>, <a href="#a7af36259c05fe6d814df34aa9932c9db">makeNaN</a>, <a href="#a4d72a16f5c9b1344026b49a271878059">makeSmallest</a>, <a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a75267ed3af879b99e5fa13b94a5383ca">llvm::detail::opInvalidOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83af504b239085c1725913aa1743e040">llvm::APInt::tcDecrement</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a06fd1421d0b30ea9b865b7238b8ca89d">llvm::APInt::tcSetBit</a>.</p>


<p>Referenced by <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### remainder {#a3bca128877cdeaf409dd5fc68dfeb96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::remainder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE remainder.</p>

<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2178 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a6aa059590a2b13eab35037154841e81c">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a5ad004323975537528a08db31f8e7246">llvm::detail::cmpGreaterThan</a>, <a href="#a3482cd2270813afec01825fd5ba575d6">compare</a>, <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a259e56c00894bdd3606974a6e3a6464e">llvm::fltSemantics::maxExponent</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a775c20ec722ff6779370b64d2251d954">llvm::fltSemantics::minExponent</a>, <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a22ff3f8dc3fb2863d778bd6edc091ce4">llvm::detail::opDivByZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ac3a5f03151dfa723fbbf0afab1cdd7ba">llvm::detail::rmNearestTiesToEven</a> and <a href="#a42066115d96555269402c2393431c527">subtract</a>.</p>

</div>
</div>

### roundToIntegral {#a90425b7a8031ab778f7fbbdf07c1b948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::roundToIntegral (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2372 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a6aa059590a2b13eab35037154841e81c">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af209287742aa0cc1a91160768251986a">changeSign</a>, <a href="#a135db5ce97b04855e9e8f44d26d30d43">convertFromAPInt</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#ac55b5d9082d1c4466113b3223464759f">isInfinity</a>, <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>, <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>, <a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb65eef479f0473d0fe1666b80155237">llvm::NextPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a75267ed3af879b99e5fa13b94a5383ca">llvm::detail::opInvalidOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ac3a5f03151dfa723fbbf0afab1cdd7ba">llvm::detail::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6530cd829b7e8d4df2c29d950039961e">llvm::APFloatBase::semanticsPrecision</a> and <a href="#a42066115d96555269402c2393431c527">subtract</a>.</p>

</div>
</div>

### subtract {#a42066115d96555269402c2393431c527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::subtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2132 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>.</p>


<p>Referenced by <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>, <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Sign operations.

### changeSign {#af209287742aa0cc1a91160768251986a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::changeSign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2082 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>, <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>.</p>


<p>Referenced by <a href="#abe7488323ce38642acc4938efe0bcc82">next</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Conversions

### bitcastToAPInt {#a30e2aa177d7bde390e924b99b0f1092b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::IEEEFloat::bitcastToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3757 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0204614712901c08052fd64e0e6607c">llvm::semBFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78e3dcad9f6b12186ad03ad5393c02ab">llvm::semFloat4E2M1FN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20739cd51291ceb86fb7a94b4279017a">llvm::semFloat6E2M3FN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47846115528d616ad9673e2703cf9374">llvm::semFloat6E3M2FN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0c6473763345fc4fad9690798754a24">llvm::semFloat8E3M4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8b943441d508a929d62ab9444d35dd6">llvm::semFloat8E4M3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa215f65f2c225222d546711a5bad178">llvm::semFloat8E4M3B11FNUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a583afa2665e59069dfb9fc42c408723c">llvm::semFloat8E4M3FN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ced5d9cf31beb3eb87c3ca575b1f8f9">llvm::semFloat8E4M3FNUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d0f43624747b09541310d90b6674144">llvm::semFloat8E5M2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7440eebc93a0c37645a7c1ee67e4df1d">llvm::semFloat8E5M2FNUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1bceb2114f6460962c9e988f8dcf9246">llvm::semFloat8E8M0FNU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac072554936469e5afe54c3c48c529c76">llvm::semFloatTF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a81a3dea1d2b584030458c05f0dd109b7">llvm::semIEEEhalf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a425a13121bd69ca1416cc3d1da205d07">llvm::semIEEEquad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7754dc9e65dfebb21bf7179fb690de9c">llvm::semIEEEsingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abc695eee95f8cbb17f7bdfb60134704e">llvm::semX87DoubleExtended</a>.</p>


<p>Referenced by <a href="#a3d43c52f31748261cbdd0e2b0bbad94a">convertToDouble</a> and <a href="#a3ee96d60e840c18bbd08398261142ad7">convertToFloat</a>.</p>

</div>
</div>

### convert {#aee22783789ff4a16e831ce3edd759766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; toSemantics, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, bool * losesInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#aee22783789ff4a16e831ce3edd759766">IEEEFloat::convert</a> - convert a value of one floating point type to another.</p>


<p>The return value corresponds to the IEEE754 exceptions. *losesInfo records whether the transformation lost information, i.e. whether converting the result back to the original type will produce the original value (this is almost the same as return value==fsOK, but there are edge cases where this is not so).</p>


<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2536 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286afbe67ef8f3a5fcac94b2f9c074c8ad3d">llvm::lfExactlyZero</a>, <a href="#a7af36259c05fe6d814df34aa9932c9db">makeNaN</a>, <a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a>, <a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a775c20ec722ff6779370b64d2251d954">llvm::fltSemantics::minExponent</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#ad7ec63ba9c1917d7432329b8ab00e3b0">llvm::fltSemantics::nanEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a627fc7f98b788a5ed6da4856a414736b">llvm::fltSemantics::nonFiniteBehavior</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a078e0c7d94556af84b4e2264db4a1a84">llvm::detail::opInexact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a75267ed3af879b99e5fa13b94a5383ca">llvm::detail::opInvalidOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a>, <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc695eee95f8cbb17f7bdfb60134704e">llvm::semX87DoubleExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d12f6a4d4f315160afadae72c161394">llvm::shiftRight</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5027d1fc1fcb950cc207e0b39821fd10">llvm::APInt::tcAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a06fd1421d0b30ea9b865b7238b8ca89d">llvm::APInt::tcSetBit</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bd8fe361c9d102eb08cf77f6e4bfda4">llvm::APInt::tcShiftLeft</a>.</p>


<p>Referenced by <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a>.</p>

</div>
</div>

### convertFromAPInt {#a135db5ce97b04855e9e8f44d26d30d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertFromAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val, bool isSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2858 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a5fa938f247b20cccc87cc8a6e5d20aa6">llvm::APInt::getNumWords</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada7af1de63a848b2f452d63958de39fe">llvm::APInt::getRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>.</p>


<p>Referenced by <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### convertFromSignExtendedInteger {#a3da3eaf2f546dd6c6f631f2e2c2436a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertFromSignExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> * src, unsigned int srcCount, bool isSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2876 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6046f2430fdd4c273218e51e4b9bdaf3">llvm::detail::integerPartWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5027d1fc1fcb950cc207e0b39821fd10">llvm::APInt::tcAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0ffdc10d44b22d3f312c42c8922f294e">llvm::APInt::tcExtractBit</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#abece2572a121bb1dd2c34621c1e13f76">llvm::APInt::tcNegate</a>.</p>

</div>
</div>

### convertFromString {#a74d9194822bc4e6c84bc71a8ea89db5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APFloat::opStatus &gt; llvm::detail::IEEEFloat::convertFromString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3292 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f159cd1ce91fea2e7ed0b1de3b381b9">llvm::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### convertFromZeroExtendedInteger {#a4eea8656eab72e6218242f811ec6fc1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertFromZeroExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> * parts, unsigned int width, bool isSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2902 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada7af1de63a848b2f452d63958de39fe">llvm::APInt::getRawData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a0ffdc10d44b22d3f312c42c8922f294e">llvm::APInt::tcExtractBit</a>.</p>

</div>
</div>

### convertToDouble {#a3d43c52f31748261cbdd0e2b0bbad94a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::detail::IEEEFloat::convertToDouble ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3824 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a30e2aa177d7bde390e924b99b0f1092b">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acda0d1f0e4b7b739aff9601d8b4ef4e3">llvm::APInt::bitsToDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>.</p>

</div>
</div>

### convertToFloat {#a3ee96d60e840c18bbd08398261142ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::detail::IEEEFloat::convertToFloat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3817 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a30e2aa177d7bde390e924b99b0f1092b">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aaefac1a605f4e104e7c7a20ab0856889">llvm::APInt::bitsToFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7754dc9e65dfebb21bf7179fb690de9c">llvm::semIEEEsingle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a8269fab998356ea27a76ad45bd6cc8fe">llvm::APFloat::convertToFloat</a>.</p>

</div>
</div>

### convertToInteger {#af5c4dc333adfdd30afcce056b9b97484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertToInteger (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> &gt; parts, unsigned int width, bool isSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, bool * isExact)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2798 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a0bf5f8e45bfccb0805b5e12d44622271">llvm::MutableArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a75267ed3af879b99e5fa13b94a5383ca">llvm::detail::opInvalidOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a42cd9369bafb2b36e67352d993845390">llvm::detail::tcSetLeastSignificantBits</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bd8fe361c9d102eb08cf77f6e4bfda4">llvm::APInt::tcShiftLeft</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## IEEE-754R 5.7.2 General operations.

### isDenormal {#af24d88dc1da69292f443d3a4cd0bbce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isDenormal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE-754R isSubnormal(): Returns true if and only if the float is a denormal.</p>

<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a0ffdc10d44b22d3f312c42c8922f294e">llvm::APInt::tcExtractBit</a>.</p>


<p>Referenced by <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#a53f5d65ea623492751a48ee350032faf">isNormal</a> and <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### isFinite {#a6c13a0ae341758009ad824f46c05a865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isFinite ()</td>
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

<p>Returns true if and only if the current value is zero, subnormal, or normal.</p>


<p>This means that the value is not infinite or NaN.</p>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ac55b5d9082d1c4466113b3223464759f">isInfinity</a> and <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>.</p>


<p>Referenced by <a href="#ab102c7db7b7fa823f866cc4ce9519a0b">fusedMultiplyAdd</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a> and <a href="#aa30ac008fd033ba8fd7c5d144f5b084a">isInteger</a>.</p>

</div>
</div>

### isInfinity {#ac55b5d9082d1c4466113b3223464759f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isInfinity ()</td>
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

<p>IEEE-754R isInfinite(): Returns true if and only if the float is infinity.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>.</p>


<p>Referenced by <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### isNaN {#a3abc0e386496d9bed38ce2836e8129ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isNaN ()</td>
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

<p>Returns true if and only if the float is a quiet or signaling NaN.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>.</p>


<p>Referenced by <a href="#af209287742aa0cc1a91160768251986a">changeSign</a>, <a href="#a87ec5cfce4a8b6896193c822f2dc5894">hash_value</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### isNegative {#a35a8501e30440512c90175d5c9da1e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isNegative ()</td>
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

<p>IEEE-754R isSignMinus: Returns true if and only if the current value is negative.</p>


<p>This applies to zeros and NaNs as well.</p>


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#ae85740a44b2f435c6844cf491be1e20e">getExactLog2</a>, <a href="#af9f0e55d618f91f704acd7d7c6c05925">isNegZero</a>, <a href="#aabede636da031cc9d94da7dc4e1074a8">isPosZero</a>, <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>, <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a> and <a href="#a462d954821ce6386847608cf825ed480">toString</a>.</p>

</div>
</div>

### isNormal {#a53f5d65ea623492751a48ee350032faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isNormal ()</td>
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

<p>IEEE-754R isNormal: Returns true if and only if the current value is normal.</p>


<p>This implies that the current value of the float is not zero, subnormal, infinite, or NaN following the definition of normality from IEEE-754R.</p>


<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a> and <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>.</p>

</div>
</div>

### isSignaling {#accc978f15db9b1b2b8e3ac171cbac4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSignaling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if and only if the float is a signaling NaN.</p>

<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4580 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eae574ed55b8fdf720e808271239fec3cc">llvm::FiniteOnly</a>, <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a0ffdc10d44b22d3f312c42c8922f294e">llvm::APInt::tcExtractBit</a>.</p>


<p>Referenced by <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#accc978f15db9b1b2b8e3ac171cbac4e3">isSignaling</a>, <a href="#abe7488323ce38642acc4938efe0bcc82">next</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### isZero {#ac87cc1729c30fb26cbdf03b618bfb43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isZero ()</td>
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

<p>Returns true if and only if the float is plus or minus zero.</p>

<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#af209287742aa0cc1a91160768251986a">changeSign</a>, <a href="#a379365c0d805bb6c8e75120fcef1c7fd">divide</a>, <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>, <a href="#af9f0e55d618f91f704acd7d7c6c05925">isNegZero</a>, <a href="#aabede636da031cc9d94da7dc4e1074a8">isPosZero</a>, <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a>, <a href="#a84f299d5597a5c8dfa677a1989ae339c">multiply</a>, <a href="#a3bca128877cdeaf409dd5fc68dfeb96f">remainder</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Simple Queries

### getCategory {#a0e452a21ca3258bb1b33b521e0ec332d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fltCategory llvm::detail::IEEEFloat::getCategory ()</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#a5ea95ec18f93073627398d4727840503">isSmallestNormalized</a>.</p>

</div>
</div>

### getSemantics {#ac6440b9e1ccd1be8461c1f338fe96a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::detail::IEEEFloat::getSemantics ()</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#a835817b2c14c68ccbb8da31e459b4e96">ilogb</a>.</p>

</div>
</div>

### isFiniteNonZero {#a1c09ec6870a33a37ffc1732c8a93e2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isFiniteNonZero ()</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a> and <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>.</p>


<p>Referenced by <a href="#a96bf292e85a0c04c818ddfd734533769">bitwiseIsEqual</a>, <a href="#a0832f8a0b59ae97b62e74839c83898b1">compareAbsoluteValue</a>, <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#a379365c0d805bb6c8e75120fcef1c7fd">divide</a>, <a href="#ab102c7db7b7fa823f866cc4ce9519a0b">fusedMultiplyAdd</a>, <a href="#a21d5827d6fe2592fea86c1f7bf386fe9">getExactInverse</a>, <a href="#a87ec5cfce4a8b6896193c822f2dc5894">hash_value</a>, <a href="#af24d88dc1da69292f443d3a4cd0bbce5">isDenormal</a>, <a href="#a65ad336dde9a51ae13b2d854313a0693">isLargest</a>, <a href="#a53f5d65ea623492751a48ee350032faf">isNormal</a>, <a href="#af87f3f592d4275a826af6f5ff9cc960a">isSmallest</a>, <a href="#a08b873c60c5bdb77993fbe575d54ad29">mod</a> and <a href="#a84f299d5597a5c8dfa677a1989ae339c">multiply</a>.</p>

</div>
</div>

### isInteger {#aa30ac008fd033ba8fd7c5d144f5b084a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if and only if the number is an exact integer.</p>

<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="#a3482cd2270813afec01825fd5ba575d6">compare</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a6c13a0ae341758009ad824f46c05a865">isFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ab993157bbf7d4713b4c9ada49ef35b04">llvm::detail::rmTowardZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086aac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>

</div>
</div>

### isLargest {#a65ad336dde9a51ae13b2d854313a0693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isLargest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if and only if the number has the largest possible finite magnitude in the current semantics.</p>

<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af0ef7731beb4deaba4d953f79e1731d1">llvm::APFloat::hasSignificand</a>, <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a>.</p>


<p>Referenced by <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### isNegZero {#af9f0e55d618f91f704acd7d7c6c05925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isNegZero ()</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a> and <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>.</p>

</div>
</div>

### isNonZero {#a1580863be673e7462a9b6fe0716c9b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isNonZero ()</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### isPosZero {#aabede636da031cc9d94da7dc4e1074a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isPosZero ()</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a35a8501e30440512c90175d5c9da1e21">isNegative</a> and <a href="#ac87cc1729c30fb26cbdf03b618bfb43a">isZero</a>.</p>

</div>
</div>

### isSmallest {#af87f3f592d4275a826af6f5ff9cc960a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSmallest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if and only if the number has the smallest possible non-zero magnitude in the current semantics.</p>

<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#a1c09ec6870a33a37ffc1732c8a93e2d6">isFiniteNonZero</a>.</p>


<p>Referenced by <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### isSmallestNormalized {#a5ea95ec18f93073627398d4727840503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSmallestNormalized ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is the smallest (by magnitude) normalized finite number in the given semantics.</p>

<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a> and <a href="#a0e452a21ca3258bb1b33b521e0ec332d">getCategory</a>.</p>

</div>
</div>

### partCount {#a779f203bd839df13e87a9e935c346126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::partCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### significandParts {#a00fa13064b49084660328c4ef8b1eca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::integerPart * llvm::detail::IEEEFloat::significandParts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### significandParts {#a2466e9a2f3c7e93c6a47154c9d5f24ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat::integerPart * llvm::detail::IEEEFloat::significandParts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1222 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Special value setters.

### makeInf {#a4eab9b80c0530c91c8075b6e461db19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeInf (bool Neg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4741 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b89de94efd0a3ddead86511989c9c0">llvm::exponentInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eae574ed55b8fdf720e808271239fec3cc">llvm::FiniteOnly</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a4eab9b80c0530c91c8075b6e461db19f">makeInf</a>, <a href="#a7af36259c05fe6d814df34aa9932c9db">makeNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a>.</p>


<p>Referenced by <a href="#a4eab9b80c0530c91c8075b6e461db19f">makeInf</a>.</p>

</div>
</div>

### makeLargest {#a24207471f23ede2b08d380dadd5898cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeLargest (bool Neg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this number the largest magnitude normal number in the given semantics.</p>

<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4128 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6046f2430fdd4c273218e51e4b9bdaf3">llvm::detail::integerPartWidth</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a24207471f23ede2b08d380dadd5898cf">makeLargest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a>.</p>


<p>Referenced by <a href="#a24207471f23ede2b08d380dadd5898cf">makeLargest</a> and <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### makeNaN {#a7af36259c05fe6d814df34aa9932c9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeNaN (bool SNaN=false, bool Neg=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * fill=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eae574ed55b8fdf720e808271239fec3cc">llvm::FiniteOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5fa938f247b20cccc87cc8a6e5d20aa6">llvm::APInt::getNumWords</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada7af1de63a848b2f452d63958de39fe">llvm::APInt::getRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc695eee95f8cbb17f7bdfb60134704e">llvm::semX87DoubleExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5027d1fc1fcb950cc207e0b39821fd10">llvm::APInt::tcAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a826ad54b94fed65913c45e223099f149">llvm::APInt::tcClearBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9a0a3652a0b9cd851e5b67ae442028e4">llvm::APInt::tcIsZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a06fd1421d0b30ea9b865b7238b8ca89d">llvm::APInt::tcSetBit</a>.</p>


<p>Referenced by <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#a4eab9b80c0530c91c8075b6e461db19f">makeInf</a> and <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### makeQuiet {#a639825b8b65055547446e8fab3709b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeQuiet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4770 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3abc0e386496d9bed38ce2836e8129ea">isNaN</a>, <a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eac71bc68340af8790b07db8f234d89fa6">llvm::NanOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a06fd1421d0b30ea9b865b7238b8ca89d">llvm::APInt::tcSetBit</a>.</p>


<p>Referenced by <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#a639825b8b65055547446e8fab3709b6f">makeQuiet</a> and <a href="#a90425b7a8031ab778f7fbbdf07c1b948">roundToIntegral</a>.</p>

</div>
</div>

### makeSmallest {#a4d72a16f5c9b1344026b49a271878059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeSmallest (bool Neg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this number the smallest magnitude denormal number in the given semantics.</p>

<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4160 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a4d72a16f5c9b1344026b49a271878059">makeSmallest</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a>.</p>


<p>Referenced by <a href="#a4d72a16f5c9b1344026b49a271878059">makeSmallest</a> and <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### makeSmallestNormalized {#a97eaebabb01bb9d32ee07f5459be3a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeSmallestNormalized (bool Negative=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the smallest (by magnitude) normalized finite number in the given semantics.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>- True iff the number should be negative</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a06fd1421d0b30ea9b865b7238b8ca89d">llvm::APInt::tcSetBit</a>.</p>


<p>Referenced by <a href="#aee22783789ff4a16e831ce3edd759766">convert</a>, <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a>, <a href="#a97eaebabb01bb9d32ee07f5459be3a60">makeSmallestNormalized</a> and <a href="#abe7488323ce38642acc4938efe0bcc82">next</a>.</p>

</div>
</div>

### makeZero {#ae278d92a6dd0133695b2c02d9a6d39d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::makeZero (bool Neg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4756 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a24191f42e0fd67fffdbf64a9fc6639ac">llvm::exponentZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae278d92a6dd0133695b2c02d9a6d39d7">makeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a062a7e7a762600c65f4435eb53a6f17a">llvm::NegativeZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a082bdaab3ddeb1d8e28759423242e2d5">llvm::APInt::tcSet</a>.</p>


<p>Referenced by <a href="#aaf97dd1294231bc3dd4d6e414f703baa">IEEEFloat</a> and <a href="#ae278d92a6dd0133695b2c02d9a6d39d7">makeZero</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Significand operations.

### addOrSubtractSignificand {#a6e5eb7124fff613f28f29baec6817cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lostFraction llvm::detail::IEEEFloat::addOrSubtractSignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, bool subtract)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### addSignificand {#a6a370529bdbc530901fd4a3e96c9d255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::integerPart llvm::detail::IEEEFloat::addSignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### divideSignificand {#a830975d21109f3167038022e54b7e815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lostFraction llvm::detail::IEEEFloat::divideSignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### getNumHighBits {#ac969a9204dd41d25bcea6d9fc9082afd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::getNumHighBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### incrementSignificand {#ad624a7cf693f4e4ea2825306d11d7145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::incrementSignificand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### initialize {#a094b88bc5d59b99f57778d0c4fd876f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> * ourSemantics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### isSignificandAllOnes {#ab6b374b530c981d666d4d1fa33130041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSignificandAllOnes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the significand excluding the integral bit is all ones.</p>

<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### isSignificandAllOnesExceptLSB {#a45919cc129da59349234e1d7e5882590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSignificandAllOnesExceptLSB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### isSignificandAllZeros {#a2dfe6232ce89a5baaa058647a6b08ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSignificandAllZeros ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the significand excluding the integral bit is all zeros.</p>

<p>Declaration at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### isSignificandAllZerosExceptMSB {#a15bae2b93152f952d3054102bf94a759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::isSignificandAllZerosExceptMSB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### multiplySignificand {#a3955bbaaaaab1a6754f21fb457d14dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lostFraction llvm::detail::IEEEFloat::multiplySignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> addend, bool ignoreAddend=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### multiplySignificand {#a340afe48fd523d6d8d600e57f5a0ad7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lostFraction llvm::detail::IEEEFloat::multiplySignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### shiftSignificandLeft {#a7e1570082ddea93e37066b0ab5f1601f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::shiftSignificandLeft (unsigned int bits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### shiftSignificandRight {#ae99e74614f30740d1f7ee7a895d3f635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lostFraction llvm::detail::IEEEFloat::shiftSignificandRight (unsigned int bits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### significandLSB {#ae8d15735d28a2b82e60c750aafc18e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::significandLSB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### significandMSB {#af166256fdd1bb98c94b596c5411affa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::IEEEFloat::significandMSB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### subtractSignificand {#aea25853bb45b56ab183ad21b3df286bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::integerPart llvm::detail::IEEEFloat::subtractSignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> borrow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### zeroSignificand {#ae20711c8d468e3259b23fe61951c1c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::IEEEFloat::zeroSignificand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arithmetic on special values.

### addOrSubtractSpecials {#ab0d03e4118419b71fc529cc95b9d1c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::addOrSubtractSpecials (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, bool subtract)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1783 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### divideSpecials {#a71f892a42e87b20bad75921dcdd47bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::divideSpecials (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1956 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### modSpecials {#a94be750b823117121a9659665a46a7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::modSpecials (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2005 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### multiplySpecials {#af4bfeef15929068050babd3efa166865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::multiplySpecials (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### remainderSpecials {#ab99587d671ade3611b654e0617e7764a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::remainderSpecials (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2043 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Miscellany

### addOrSubtract {#adcad9d05d27878ec78097aa5387d14a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::addOrSubtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp; rhs, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, bool subtract)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2093 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFromDecimalString {#a0e8d698e353249bb569e0904ebb49dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APFloat::opStatus &gt; llvm::detail::IEEEFloat::convertFromDecimalString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3097 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFromHexadecimalString {#a392e52dab34bbe1ebff4ede602c5b546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APFloat::opStatus &gt; llvm::detail::IEEEFloat::convertFromHexadecimalString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> s, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2918 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFromStringSpecials {#acac27aec3e1f120f97ff86f50bc1768c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::convertFromStringSpecials (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3221 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertFromUnsignedParts {#a480428f9df78aa2323a08639ddb8db7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertFromUnsignedParts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> * src, unsigned int srcCount, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2830 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertNormalToHexString {#a9792505f5f89e753f24ad7809abfda7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::detail::IEEEFloat::convertNormalToHexString (char * dst, unsigned int hexDigits, bool upperCase, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3396 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### convertToSignExtendedInteger {#a9146e5637d0b7584a12f8421bb25106a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::convertToSignExtendedInteger (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> &gt; parts, unsigned int width, bool isSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, bool * isExact)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 2684 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### exponentInf {#a97336b20400f8fe7117126e62e8f34a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::ExponentType llvm::detail::IEEEFloat::exponentInf ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4733 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### exponentNaN {#a70be3f6ed16fe1689f05c4496098c381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::ExponentType llvm::detail::IEEEFloat::exponentNaN ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4729 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### exponentZero {#a519f8d14a1f53d35cb938fe3ad8c7da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::ExponentType llvm::detail::IEEEFloat::exponentZero ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4737 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### handleOverflow {#ae0dc4f3568361be672a4e9c00a706402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::handleOverflow (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1579 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### normalize {#a554952f9ab2530040d61115f8b1f1533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::normalize (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a> lost_fraction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1649 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### roundAwayFromZero {#a700605f43d59ce71cccdc99d374b4b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::IEEEFloat::roundAwayFromZero (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> rounding_mode, <a href="/web-llvm/docs/api/namespaces/llvm/#a663d7637c110daee5beee1f03a9ac286">lostFraction</a> lost_fraction, unsigned int bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### roundSignificandWithExponent {#af88389f0c9674a41bafb5349ae9d059f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::IEEEFloat::roundSignificandWithExponent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> *, unsigned int, int, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 3012 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
