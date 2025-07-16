---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/apfixedpoint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `APFixedPoint` Class Reference

<p>The <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> class works similarly to APInt/APSInt in that it is a functional replacement for a scaled integer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::APFixedPoint { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">llvm/ADT/APFixedPoint.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a> (const APInt &amp;Val, const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b4f8481895096ec305970353ad8c56">APFixedPoint</a> (uint64_t Val, const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1242c6135519977403a4e241c0c91a">APFixedPoint</a> (const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216ce548f1cd023c727795ffdffff49c">operator==</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3022758530a92c344fe3f8877737167c">operator!=</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65c52eba10c72efa9eb898fa18ed739">operator&gt;</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a103e1f19f86181a3005fe69fd8789">operator&lt;</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6467ad69c8c4846f1d7dc0810bda3e">operator&gt;=</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8741de8b1e6d09a771c4af2a5dbdf7">operator&lt;=</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bbd87101e38731ac9741e1736aab9d">getWidth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79086dcf3036e01d4a3a17a342fcdee8">getScale</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cee643e8cd580a1649e05b8e52a5be5">getLsbWeight</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4afb726fd0234263746c5d7a3ebd6e">getMsbWeight</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73df3f58a4080fc9e76cc35ddf62af0">isSaturated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5c35033396ab686cf586ebdd083dbe">isSigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8620074c0bd46468a2c2938bd96553">hasPadding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497d79bdcaa01eb124b6f1c73b662ecb">getSemantics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b44d173844ad150cc542b8ee1e9ba9">getBoolValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fa4c8635e7f41be7af6f9297db0aff">convert</a> (const FixedPointSemantics &amp;DstSema, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69d1c99b0af08146faf9bdf2d9c8709">add</a> (const APFixedPoint &amp;Other, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9ba22fe2a57b958ba00d8b3382fffd">sub</a> (const APFixedPoint &amp;Other, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1188d3cd694bbba2756d1b7aaad6e19">mul</a> (const APFixedPoint &amp;Other, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7a0970dbe748e4fec6bd94d353476c">div</a> (const APFixedPoint &amp;Other, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa494dc35a29c6f78f26ea04679887f0d">shl</a> (unsigned Amt, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4caae593a7219532aebcb8fd5e151d">shr</a> (unsigned Amt, bool *Overflow=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f8d0cff6a04b5d6aed128badf08862">negate</a> (bool *Overflow=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a unary negation (-X) on this fixed point type, taking into account saturation if applicable. <a href="#aa2f8d0cff6a04b5d6aed128badf08862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2268a8da9de7921a854b4f3e0028ae5">getIntPart</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the integral part of this fixed point number, rounded towards zero. <a href="#ad2268a8da9de7921a854b4f3e0028ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0f7939bae61f761380e0334523469b">convertToInt</a> (unsigned DstWidth, bool DstSign, bool *Overflow=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the integral part of this fixed point number, rounded towards zero. <a href="#a5c0f7939bae61f761380e0334523469b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f50fded9ec4a127a18b88ef2a61163e">convertToFloat</a> (const fltSemantics &amp;FloatSema) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this fixed point number to a floating point value with the provided semantics. <a href="#a6f50fded9ec4a127a18b88ef2a61163e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07384ea9d8fdfb208574ff59715e5be2">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab65ed18c6afa42aaa83b5e472b39a2">toString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eec241f62165c439959b940599c3bb0">print</a> (raw_ostream &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a730a632147603ed96aef4cd6f0e92bf7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> (const APFixedPoint &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae749f00c669846f164d35b1126fbef73">Val</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a6c60eeeba305f1272bd1295611f3e">Sema</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a> (const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a> (const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89e3e44e5cd5dc12dce33313ffef244">getEpsilon</a> (const FixedPointSemantics &amp;Sema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca508af3c3b25de78d97741420a9ff9e">promoteFloatSemantics</a> (const fltSemantics *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a floating point semantic, return the next floating point semantic with a larger exponent and larger or equal mantissa. <a href="#aca508af3c3b25de78d97741420a9ff9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738a0be04b7721972a680302c07c12bb">getFromIntValue</a> (const APSInt &amp;Value, const FixedPointSemantics &amp;DstFXSema, bool *Overflow=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> with a value equal to that of the provided integer, and in the same semantics as the provided target semantics. <a href="#a738a0be04b7721972a680302c07c12bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a> (const APFloat &amp;Value, const FixedPointSemantics &amp;DstFXSema, bool *Overflow=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> with a value equal to that of the provided floating point value, in the provided target semantics. <a href="#a67272093577b2c99e6138e38c647abe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> class works similarly to APInt/APSInt in that it is a functional replacement for a scaled integer.</p>


<p>It supports a wide range of semantics including the one used by fixed point types proposed in ISO/IEC JTC1 SC22 WG14 N1169. The class carries the value and semantics of a fixed point, and provides different operations that would normally be performed on fixed point types.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### APFixedPoint() {#a17de6476b95be00e26e2a67b4bdd105f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFixedPoint::APFixedPoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9a5c35033396ab686cf586ebdd083dbe">isSigned</a>.</p>


<p>Referenced by <a href="#ad69d1c99b0af08146faf9bdf2d9c8709">add</a>, <a href="#a6c1242c6135519977403a4e241c0c91a">APFixedPoint</a>, <a href="#a71b4f8481895096ec305970353ad8c56">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a>, <a href="#a04fa4c8635e7f41be7af6f9297db0aff">convert</a>, <a href="#acb7a0970dbe748e4fec6bd94d353476c">div</a>, <a href="#ac89e3e44e5cd5dc12dce33313ffef244">getEpsilon</a>, <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>, <a href="#a738a0be04b7721972a680302c07c12bb">getFromIntValue</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a>, <a href="#ad1188d3cd694bbba2756d1b7aaad6e19">mul</a>, <a href="#aa2f8d0cff6a04b5d6aed128badf08862">negate</a>, <a href="#a3022758530a92c344fe3f8877737167c">operator!=</a>, <a href="#a56a103e1f19f86181a3005fe69fd8789">operator&lt;</a>, <a href="#aad8741de8b1e6d09a771c4af2a5dbdf7">operator&lt;=</a>, <a href="#a216ce548f1cd023c727795ffdffff49c">operator==</a>, <a href="#ac65c52eba10c72efa9eb898fa18ed739">operator&gt;</a>, <a href="#a9c6467ad69c8c4846f1d7dc0810bda3e">operator&gt;=</a>, <a href="#aa494dc35a29c6f78f26ea04679887f0d">shl</a>, <a href="#a5f4caae593a7219532aebcb8fd5e151d">shr</a> and <a href="#a6d9ba22fe2a57b958ba00d8b3382fffd">sub</a>.</p>

</div>
</div>

### APFixedPoint() {#a71b4f8481895096ec305970353ad8c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFixedPoint::APFixedPoint (uint64_t Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a87bbd87101e38731ac9741e1736aab9d">getWidth</a>, <a href="#a9a5c35033396ab686cf586ebdd083dbe">isSigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### APFixedPoint() {#a6c1242c6135519977403a4e241c0c91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFixedPoint::APFixedPoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Reference <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a3022758530a92c344fe3f8877737167c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&lt;() {#a56a103e1f19f86181a3005fe69fd8789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&lt;=() {#aad8741de8b1e6d09a771c4af2a5dbdf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a216ce548f1cd023c727795ffdffff49c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&gt;() {#ac65c52eba10c72efa9eb898fa18ed739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&gt;=() {#a9c6467ad69c8c4846f1d7dc0810bda3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ad69d1c99b0af08146faf9bdf2d9c8709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a694293446a074c3d64270e7671bb5052">llvm::APInt::sadd_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c1e0381aeb551ad0ba58effe9232f97">llvm::APInt::sadd_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8268fbc3014081004056f6466452c904">llvm::APInt::uadd_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ab4c04665274d4f30d732639dc055821c">llvm::APInt::uadd_sat</a>.</p>

</div>
</div>

### compare() {#a505208677eadb6d75acfdfc01911c8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::APFixedPoint::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="#a3cee643e8cd580a1649e05b8e52a5be5">getLsbWeight</a>, <a href="#adc4afb726fd0234263746c5d7a3ebd6e">getMsbWeight</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada19a89b7c62ce0bb713a7254b002445">llvm::APInt::isSignBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="#a3022758530a92c344fe3f8877737167c">operator!=</a>, <a href="#a56a103e1f19f86181a3005fe69fd8789">operator&lt;</a>, <a href="#aad8741de8b1e6d09a771c4af2a5dbdf7">operator&lt;=</a>, <a href="#a216ce548f1cd023c727795ffdffff49c">operator==</a>, <a href="#ac65c52eba10c72efa9eb898fa18ed739">operator&gt;</a> and <a href="#a9c6467ad69c8c4846f1d7dc0810bda3e">operator&gt;=</a>.</p>

</div>
</div>

### convert() {#a04fa4c8635e7f41be7af6f9297db0aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::convert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstSema, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ad62f39c993a3723a7b735652e1e14f57">llvm::APSInt::extend</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aeaf22e8d92fd978a5eca9ab031994399">llvm::APInt::getBitsSetFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a60827722079f839f42712dacafce3695">llvm::FixedPointSemantics::getIntegralBits</a>, <a href="#a3cee643e8cd580a1649e05b8e52a5be5">getLsbWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#aaea346c0aab9c7f4608ce41a4c217fa5">llvm::FixedPointSemantics::getLsbWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a2f3dab29dd773a1faa002a701261db99">llvm::FixedPointSemantics::getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a16fd96ce7d6d8206ad35461a688a780f">llvm::APSInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a56da39babaf07b5638145d232de64949">llvm::FixedPointSemantics::isSaturated</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa9bfb82b935461edaeaff0a95e39d929">llvm::APSInt::relativeShl</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#a83a47f2f0f20023cf6ed21dd467202de">llvm::APSInt::setIsSigned</a>.</p>

</div>
</div>

### convertToFloat() {#a6f50fded9ec4a127a18b88ef2a61163e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFixedPoint::convertToFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; FloatSema)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this fixed point number to a floating point value with the provided semantics.</p>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11534cddb9d36ce7b049eefacc295a96">Flt</a>, <a href="#aca508af3c3b25de78d97741420a9ff9e">promoteFloatSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>


<p>Referenced by <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>.</p>

</div>
</div>

### convertToInt() {#a5c0f7939bae61f761380e0334523469b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APFixedPoint::convertToInt (unsigned DstWidth, bool DstSign, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the integral part of this fixed point number, rounded towards zero.</p>


<p>The value is stored into an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> with the provided width and sign. If the overflow parameter is provided, and the integral value is not able to be fully stored in the provided width and sign, the overflow parameter is set to true.</p>


<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apsint/#ad62f39c993a3723a7b735652e1e14f57">llvm::APSInt::extend</a>, <a href="#ad2268a8da9de7921a854b4f3e0028ae5">getIntPart</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a5cba4d26a4ef4ecf1cea7faac29b1786">llvm::APSInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0a441f49b4e67f435392c937e056d2d4">llvm::APSInt::getMinValue</a> and <a href="#a87bbd87101e38731ac9741e1736aab9d">getWidth</a>.</p>

</div>
</div>

### div() {#acb7a0970dbe748e4fec6bd94d353476c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::div (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a16fd96ce7d6d8206ad35461a688a780f">llvm::APSInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a24187c2e178af0df22dac26cd5229294">llvm::APInt::sdivrem</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### dump() {#a730a632147603ed96aef4cd6f0e92bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::APFixedPoint::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a7eec241f62165c439959b940599c3bb0">print</a>.</p>

</div>
</div>

### getBoolValue() {#ad7b44d173844ad150cc542b8ee1e9ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::getBoolValue ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### getIntPart() {#ad2268a8da9de7921a854b4f3e0028ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APFixedPoint::getIntPart ()</td>
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

<p>Return the integral part of this fixed point number, rounded towards zero.</p>


<p>(-2.5k -&gt; -2)</p>


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apsint/#ad62f39c993a3723a7b735652e1e14f57">llvm::APSInt::extend</a>, <a href="#a3cee643e8cd580a1649e05b8e52a5be5">getLsbWeight</a>, <a href="#adc4afb726fd0234263746c5d7a3ebd6e">getMsbWeight</a>, <a href="#a87bbd87101e38731ac9741e1736aab9d">getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa9bfb82b935461edaeaff0a95e39d929">llvm::APSInt::relativeShl</a>.</p>


<p>Referenced by <a href="#a5c0f7939bae61f761380e0334523469b">convertToInt</a>.</p>

</div>
</div>

### getLsbWeight() {#a3cee643e8cd580a1649e05b8e52a5be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::APFixedPoint::getLsbWeight ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a>, <a href="#a04fa4c8635e7f41be7af6f9297db0aff">convert</a>, <a href="#ad2268a8da9de7921a854b4f3e0028ae5">getIntPart</a> and <a href="#a07384ea9d8fdfb208574ff59715e5be2">toString</a>.</p>

</div>
</div>

### getMsbWeight() {#adc4afb726fd0234263746c5d7a3ebd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::APFixedPoint::getMsbWeight ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a> and <a href="#ad2268a8da9de7921a854b4f3e0028ae5">getIntPart</a>.</p>

</div>
</div>

### getScale() {#a79086dcf3036e01d4a3a17a342fcdee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APFixedPoint::getScale ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### getSemantics() {#a497d79bdcaa01eb124b6f1c73b662ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::APFixedPoint::getSemantics ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a878c7852c8f3761c4416ef3e37a54566">llvm::hash_value</a>.</p>

</div>
</div>

### getValue() {#a82cc2364c94c614756f6013fd3fb902a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APFixedPoint::getValue ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#ad69d1c99b0af08146faf9bdf2d9c8709">add</a>, <a href="#a505208677eadb6d75acfdfc01911c8dc">compare</a>, <a href="#acb7a0970dbe748e4fec6bd94d353476c">div</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a>, <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a878c7852c8f3761c4416ef3e37a54566">llvm::hash_value</a>, <a href="#ad1188d3cd694bbba2756d1b7aaad6e19">mul</a>, <a href="#aa494dc35a29c6f78f26ea04679887f0d">shl</a>, <a href="#a6d9ba22fe2a57b958ba00d8b3382fffd">sub</a> and <a href="#a07384ea9d8fdfb208574ff59715e5be2">toString</a>.</p>

</div>
</div>

### getWidth() {#a87bbd87101e38731ac9741e1736aab9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APFixedPoint::getWidth ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a71b4f8481895096ec305970353ad8c56">APFixedPoint</a>, <a href="#a5c0f7939bae61f761380e0334523469b">convertToInt</a>, <a href="#ad2268a8da9de7921a854b4f3e0028ae5">getIntPart</a> and <a href="#a07384ea9d8fdfb208574ff59715e5be2">toString</a>.</p>

</div>
</div>

### hasPadding() {#a9c8620074c0bd46468a2c2938bd96553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::hasPadding ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### isSaturated() {#ac73df3f58a4080fc9e76cc35ddf62af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::isSaturated ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#aa2f8d0cff6a04b5d6aed128badf08862">negate</a>.</p>

</div>
</div>

### isSigned() {#a9a5c35033396ab686cf586ebdd083dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFixedPoint::isSigned ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Referenced by <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#a71b4f8481895096ec305970353ad8c56">APFixedPoint</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a> and <a href="#aa2f8d0cff6a04b5d6aed128badf08862">negate</a>.</p>

</div>
</div>

### mul() {#ad1188d3cd694bbba2756d1b7aaad6e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::mul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a793e27a4e7b6ec5ecab8e7616e0d4ac0">llvm::APInt::relativeAShl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3bbf73dc4411a52b8d03e582a09893ce">llvm::APInt::relativeLShl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac155d7c568fc1aba25723e77b6888908">llvm::APInt::smul_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a028f4d1eead63cc33499ce3459bd27c7">llvm::APInt::umul_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### negate() {#aa2f8d0cff6a04b5d6aed128badf08862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::negate (bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a unary negation (-X) on this fixed point type, taking into account saturation if applicable.</p>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#ac73df3f58a4080fc9e76cc35ddf62af0">isSaturated</a> and <a href="#a9a5c35033396ab686cf586ebdd083dbe">isSigned</a>.</p>

</div>
</div>

### print() {#a7eec241f62165c439959b940599c3bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFixedPoint::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>Reference <a href="#a7ab65ed18c6afa42aaa83b5e472b39a2">toString</a>.</p>


<p>Referenced by <a href="#a730a632147603ed96aef4cd6f0e92bf7">dump</a>.</p>

</div>
</div>

### shl() {#aa494dc35a29c6f78f26ea04679887f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::shl (unsigned Amt, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### shr() {#a5f4caae593a7219532aebcb8fd5e151d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::shr (unsigned Amt, bool * Overflow=nullptr)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Reference <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>.</p>

</div>
</div>

### sub() {#a6d9ba22fe2a57b958ba00d8b3382fffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::sub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> &amp; Other, bool * Overflow=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae324de5041feaf7eb8433221cdaca9aa">llvm::APInt::ssub_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af888cb3cadd9a4e5f422c96e5674de88">llvm::APInt::ssub_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d622af4cca05108d8d7eb9bfd79977">llvm::APInt::usub_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a059dc64e71df065315050d2270cbfba5">llvm::APInt::usub_sat</a>.</p>

</div>
</div>

### toString() {#a07384ea9d8fdfb208574ff59715e5be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFixedPoint::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apsint/#a12104865ac55c27d5a97bd72d4b750b7">llvm::APSInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="#a3cee643e8cd580a1649e05b8e52a5be5">getLsbWeight</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="#a87bbd87101e38731ac9741e1736aab9d">getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab89f1db02887aa569176f0e29622eb47">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### toString() {#a7ab65ed18c6afa42aaa83b5e472b39a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::APFixedPoint::toString ()</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>


<p>Reference <a href="#a7ab65ed18c6afa42aaa83b5e472b39a2">toString</a>.</p>


<p>Referenced by <a href="#a7eec241f62165c439959b940599c3bb0">print</a> and <a href="#a7ab65ed18c6afa42aaa83b5e472b39a2">toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Sema {#a77a6c60eeeba305f1272bd1295611f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::APFixedPoint::Sema</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

### Val {#ae749f00c669846f164d35b1126fbef73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APFixedPoint::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEpsilon() {#ac89e3e44e5cd5dc12dce33313ffef244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::getEpsilon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>Reference <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>.</p>

</div>
</div>

### getFromFloatValue() {#a67272093577b2c99e6138e38c647abe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::getFromFloatValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstFXSema, bool * Overflow=nullptr)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> with a value equal to that of the provided floating point value, in the provided target semantics.</p>


<p>If the value is not able to fit in the specified fixed point semantics and the overflow parameter is specified, it is set to true. For NaN, the Overflow flag is always set. For +inf and -inf, if the semantic is saturating, the value saturates. Otherwise, the Overflow flag is set.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="#a6f50fded9ec4a127a18b88ef2a61163e">convertToFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#aaea346c0aab9c7f4608ce41a4c217fa5">llvm::FixedPointSemantics::getLsbWeight</a>, <a href="#ae7ca9ff56521cc2e2c51d96ad9a6005c">getMax</a>, <a href="#a1c4398afd568f2c31f81dcecad35ef7b">getMin</a>, <a href="#a82cc2364c94c614756f6013fd3fb902a">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a2f3dab29dd773a1faa002a701261db99">llvm::FixedPointSemantics::getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a56da39babaf07b5638145d232de64949">llvm::FixedPointSemantics::isSaturated</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>, <a href="#aca508af3c3b25de78d97741420a9ff9e">promoteFloatSemantics</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>

</div>
</div>

### getFromIntValue() {#a738a0be04b7721972a680302c07c12bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::getFromIntValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstFXSema, bool * Overflow=nullptr)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint">APFixedPoint</a> with a value equal to that of the provided integer, and in the same semantics as the provided target semantics.</p>


<p>If the value is not able to fit in the specified fixed point semantics, and the overflow parameter is provided, it is set to true.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#aebc9b19a86db06690ffcc4904907e8be">llvm::FixedPointSemantics::GetIntegerSemantics</a>.</p>

</div>
</div>

### getMax() {#ae7ca9ff56521cc2e2c51d96ad9a6005c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::getMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a5cba4d26a4ef4ecf1cea7faac29b1786">llvm::APSInt::getMaxValue</a> and <a href="#a9a5c35033396ab686cf586ebdd083dbe">isSigned</a>.</p>


<p>Referenced by <a href="#acb7a0970dbe748e4fec6bd94d353476c">div</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a>, <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>, <a href="#ad1188d3cd694bbba2756d1b7aaad6e19">mul</a>, <a href="#aa2f8d0cff6a04b5d6aed128badf08862">negate</a> and <a href="#aa494dc35a29c6f78f26ea04679887f0d">shl</a>.</p>

</div>
</div>

### getMin() {#a1c4398afd568f2c31f81dcecad35ef7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFixedPoint llvm::APFixedPoint::getMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="#a17de6476b95be00e26e2a67b4bdd105f">APFixedPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0a441f49b4e67f435392c937e056d2d4">llvm::APSInt::getMinValue</a>.</p>


<p>Referenced by <a href="#acb7a0970dbe748e4fec6bd94d353476c">div</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a>, <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>, <a href="#ad1188d3cd694bbba2756d1b7aaad6e19">mul</a> and <a href="#aa494dc35a29c6f78f26ea04679887f0d">shl</a>.</p>

</div>
</div>

### promoteFloatSemantics() {#aca508af3c3b25de78d97741420a9ff9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics * llvm::APFixedPoint::promoteFloatSemantics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> * S)</td>
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

<p>Given a floating point semantic, return the next floating point semantic with a larger exponent and larger or equal mantissa.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfixedpoint-h">APFixedPoint.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfixedpoint-cpp">APFixedPoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ab46ff1a80ee89c9e22ca17c179a89ab1">llvm::APFloatBase::BFloat</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a494661a175e7785032f9a05d963fc0e9">llvm::APFloatBase::IEEEquad</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a6f50fded9ec4a127a18b88ef2a61163e">convertToFloat</a> and <a href="#a67272093577b2c99e6138e38c647abe3">getFromFloatValue</a>.</p>

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
