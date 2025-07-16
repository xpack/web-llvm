---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/doubleapfloat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DoubleAPFloat` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::detail::DoubleAPFloat { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b6e0b21d57ae08d2c0fcdb9b617de0">scalbn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f1d9f3476ae13feba62816a127620c">frexp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa75ab1b6e1de32bd60392773a0b9fef">hash_value</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a> (const fltSemantics &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c896ef9c440bdca6585370cf36a3801">DoubleAPFloat</a> (const fltSemantics &amp;S, uninitializedTag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c5f34c5604feda537319b1639ba41f">DoubleAPFloat</a> (const fltSemantics &amp;S, integerPart)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b828c30faa001a6e3b3cfcf5d173c99">DoubleAPFloat</a> (const fltSemantics &amp;S, const APInt &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04a423141d7ea1f5b766c5c2742e94f">DoubleAPFloat</a> (const fltSemantics &amp;S, APFloat &amp;&amp;First, APFloat &amp;&amp;Second)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c4aae9330efbe14fd584763b640bd8">DoubleAPFloat</a> (const DoubleAPFloat &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad064cb5210204eca6abae73b2343e93d">DoubleAPFloat</a> (DoubleAPFloat &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02fc43e817a40ffc89f5da97bbde4931">operator=</a> (const DoubleAPFloat &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade123b7f25c5fdbf04039784938a00b1">operator=</a> (DoubleAPFloat &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0cf0c7e02302aa62e1339f09d549bd">needsCleanup</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cc6b91ede24ffd11e5804afb950e3d">getFirst</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2509b7c74eb65c43dcf0f07078e90b75">getFirst</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0a3057868abd467a880ff5390d11a7">getSecond</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a56601f2fd189eaeca1e7737230c5a">getSecond</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d95621f2eb4bfd49078a9005b0f388">add</a> (const DoubleAPFloat &amp;RHS, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f71b277d8d03245a99b5faa642d107f">subtract</a> (const DoubleAPFloat &amp;RHS, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314c190b5e7220bc1daa2c7fa271a63c">multiply</a> (const DoubleAPFloat &amp;RHS, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4808fb08649caf3637752746bbc6bc2">divide</a> (const DoubleAPFloat &amp;RHS, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8f5b97d182a63fa132a5169d82a1e9">remainder</a> (const DoubleAPFloat &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11bb851f15cc8f484d5ba9948e14411">mod</a> (const DoubleAPFloat &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a3c008b93df2ac020b72d934c4d4c2">fusedMultiplyAdd</a> (const DoubleAPFloat &amp;Multiplicand, const DoubleAPFloat &amp;Addend, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b0430f59ff83e88ee055589e1c7387">roundToIntegral</a> (roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7673b95572ea1fcc00fdac680976a2">changeSign</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72861694815b642a9bb51515d93ecadc">compareAbsoluteValue</a> (const DoubleAPFloat &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44">fltCategory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c6882db1f9bd99a7e302f32fa5f6f3">getCategory</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af186c5b860bb04c1748239c7eb2a3bf9">isNegative</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874db9c0210bd1671cea824b4e6d7f8d">makeInf</a> (bool Neg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d7acd132e0e96668ea868ed0d3bd04">makeZero</a> (bool Neg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3bcd088b654049f686ac4cf7c3cc90c">makeLargest</a> (bool Neg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81088cb94f9459b8004ad9afab6f5757">makeSmallest</a> (bool Neg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003247d359fc96961140b0f23be2c47d">makeSmallestNormalized</a> (bool Neg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5ea12b0d71dda25b023cbe6e0fa8b1">makeNaN</a> (bool SNaN, bool Neg, const APInt *fill)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8a0d24edb510fef2e2cf6e62111594">compare</a> (const DoubleAPFloat &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e06634491024c4ee79ca22d1c6154a3">bitwiseIsEqual</a> (const DoubleAPFloat &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afdbe49400342f155b8076095f3e777">convertFromString</a> (StringRef, roundingMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867d044bc3f3ac08e29e98aee30c3e58">next</a> (bool nextDown)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6416a03ebbfc3c8e49c43f65c5a84d">convertToInteger</a> (MutableArrayRef&lt; integerPart &gt; Input, unsigned int Width, bool IsSigned, roundingMode RM, bool *IsExact) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477d9c111d2e0ae837de4f4efaf47058">convertFromAPInt</a> (const APInt &amp;Input, bool IsSigned, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f54bf233710b1041d2a2218b3d9775">convertFromSignExtendedInteger</a> (const integerPart *Input, unsigned int InputSize, bool IsSigned, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b587c3ee7248d56ec0bb9aa8bc4dfd">convertFromZeroExtendedInteger</a> (const integerPart *Input, unsigned int InputSize, bool IsSigned, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9bf262be438320cef2483bf01e7222c">convertToHexString</a> (char *DST, unsigned int HexDigits, bool UpperCase, roundingMode RM) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795f91a5b36b3c7ab7ac3d1ee2d6a3e6">isDenormal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955dabd11aa050766069762e107f7a1e">isInteger</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a87407767d65bd07b00a21d614a74d">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned FormatPrecision, unsigned FormatMaxPadding, bool TruncateZero=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ab6474b8e70068a974fa56622abd14">getExactInverse</a> (APFloat *inv) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b86718d8298cad3c74ba88cd1acc77">getExactLog2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ecda37fdadf402478d5bd62c2cb233">getExactLog2Abs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff991ed57ff55877923a6a1f22e3c2ec">addImpl</a> (const APFloat &amp;a, const APFloat &amp;aa, const APFloat &amp;c, const APFloat &amp;cc, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cac08cee4de2ccd561f2a7c8a92779a">addWithSpecial</a> (const DoubleAPFloat &amp;LHS, const DoubleAPFloat &amp;RHS, DoubleAPFloat &amp;Out, roundingMode RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4fe1f75ff3ffe4c3bd193430e5932f">Semantics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b467f8193bb24795ce5d2c8ce64d34">Floats</a></td>
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


<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<div class="doxySectionDef">

## Friends

### frexp {#af5f1d9f3476ae13feba62816a127620c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; X, int &amp; Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### hash\_value {#aaa75ab1b6e1de32bd60392773a0b9fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; Arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5252 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#aaa75ab1b6e1de32bd60392773a0b9fef">hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a63d1e69d1ec4f0beab0fb42d2ef3339a">llvm::detail::hash_value</a>.</p>


<p>Referenced by <a href="#aaa75ab1b6e1de32bd60392773a0b9fef">hash_value</a>.</p>

</div>
</div>

### scalbn {#aa2b6e0b21d57ae08d2c0fcdb9b617de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; X, int Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DoubleAPFloat() {#ab289b202c32cf7b49760915cec8f299a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4834 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>


<p>Referenced by <a href="#af1d95621f2eb4bfd49078a9005b0f388">add</a>, <a href="#a3e06634491024c4ee79ca22d1c6154a3">bitwiseIsEqual</a>, <a href="#acc8a0d24edb510fef2e2cf6e62111594">compare</a>, <a href="#a72861694815b642a9bb51515d93ecadc">compareAbsoluteValue</a>, <a href="#a477d9c111d2e0ae837de4f4efaf47058">convertFromAPInt</a>, <a href="#ae4f54bf233710b1041d2a2218b3d9775">convertFromSignExtendedInteger</a>, <a href="#a5afdbe49400342f155b8076095f3e777">convertFromString</a>, <a href="#a50b587c3ee7248d56ec0bb9aa8bc4dfd">convertFromZeroExtendedInteger</a>, <a href="#aa4808fb08649caf3637752746bbc6bc2">divide</a>, <a href="#aa0c4aae9330efbe14fd584763b640bd8">DoubleAPFloat</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="#ad064cb5210204eca6abae73b2343e93d">DoubleAPFloat</a>, <a href="#af5f1d9f3476ae13feba62816a127620c">frexp</a>, <a href="#ae5a3c008b93df2ac020b72d934c4d4c2">fusedMultiplyAdd</a>, <a href="#aaa75ab1b6e1de32bd60392773a0b9fef">hash_value</a>, <a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a>, <a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a>, <a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a>, <a href="#ab11bb851f15cc8f484d5ba9948e14411">mod</a>, <a href="#a314c190b5e7220bc1daa2c7fa271a63c">multiply</a>, <a href="#a867d044bc3f3ac08e29e98aee30c3e58">next</a>, <a href="#a02fc43e817a40ffc89f5da97bbde4931">operator=</a>, <a href="#ade123b7f25c5fdbf04039784938a00b1">operator=</a>, <a href="#a2f8f5b97d182a63fa132a5169d82a1e9">remainder</a>, <a href="#ae3b0430f59ff83e88ee055589e1c7387">roundToIntegral</a>, <a href="#aa2b6e0b21d57ae08d2c0fcdb9b617de0">scalbn</a> and <a href="#a5f71b277d8d03245a99b5faa642d107f">subtract</a>.</p>

</div>
</div>

### DoubleAPFloat() {#a4c896ef9c440bdca6585370cf36a3801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567f">uninitializedTag</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4840 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a50f731c0b18488ead25124edd63be589">llvm::detail::uninitialized</a>.</p>

</div>
</div>

### DoubleAPFloat() {#a98c5f34c5604feda537319b1639ba41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4847 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>

</div>
</div>

### DoubleAPFloat() {#a5b828c30faa001a6e3b3cfcf5d173c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4853 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>

</div>
</div>

### DoubleAPFloat() {#ab04a423141d7ea1f5b766c5c2742e94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;&amp; First, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;&amp; Second)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4861 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>.</p>

</div>
</div>

### DoubleAPFloat() {#aa0c4aae9330efbe14fd584763b640bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4870 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>

</div>
</div>

### DoubleAPFloat() {#ad064cb5210204eca6abae73b2343e93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::DoubleAPFloat::DoubleAPFloat (<a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4878 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a081a32b758ca3c58f2a937b3d04ca218">llvm::semBogus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a02fc43e817a40ffc89f5da97bbde4931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DoubleAPFloat &amp; llvm::detail::DoubleAPFloat::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4884 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>

</div>
</div>

### operator=() {#ade123b7f25c5fdbf04039784938a00b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DoubleAPFloat &amp; llvm::detail::DoubleAPFloat::operator= (<a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#af1d95621f2eb4bfd49078a9005b0f388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5023 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>


<p>Referenced by <a href="#a5f71b277d8d03245a99b5faa642d107f">subtract</a>.</p>

</div>
</div>

### bitcastToAPInt() {#a5231d94ec7d5c6a8962a30b0f6666478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::DoubleAPFloat::bitcastToAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>


<p>Referenced by <a href="#ae9bf262be438320cef2483bf01e7222c">convertToHexString</a>, <a href="#a7d6416a03ebbfc3c8e49c43f65c5a84d">convertToInteger</a>, <a href="#aa4808fb08649caf3637752746bbc6bc2">divide</a>, <a href="#ae5a3c008b93df2ac020b72d934c4d4c2">fusedMultiplyAdd</a>, <a href="#a58ab6474b8e70068a974fa56622abd14">getExactInverse</a>, <a href="#ab11bb851f15cc8f484d5ba9948e14411">mod</a>, <a href="#a867d044bc3f3ac08e29e98aee30c3e58">next</a>, <a href="#a2f8f5b97d182a63fa132a5169d82a1e9">remainder</a>, <a href="#ae3b0430f59ff83e88ee055589e1c7387">roundToIntegral</a> and <a href="#ab8a87407767d65bd07b00a21d614a74d">toString</a>.</p>

</div>
</div>

### bitwiseIsEqual() {#a3e06634491024c4ee79ca22d1c6154a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::bitwiseIsEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>

</div>
</div>

### changeSign() {#a0d7673b95572ea1fcc00fdac680976a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::changeSign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5170 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Referenced by <a href="#ac3bcd088b654049f686ac4cf7c3cc90c">makeLargest</a> and <a href="#a5f71b277d8d03245a99b5faa642d107f">subtract</a>.</p>

</div>
</div>

### compare() {#acc8a0d24edb510fef2e2cf6e62111594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::cmpResult llvm::detail::DoubleAPFloat::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a> and <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>


<p>Referenced by <a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a>, <a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a> and <a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a>.</p>

</div>
</div>

### compareAbsoluteValue() {#a72861694815b642a9bb51515d93ecadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::cmpResult llvm::detail::DoubleAPFloat::compareAbsoluteValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5176 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a5ad004323975537528a08db31f8e7246">llvm::detail::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3ccb8f46dd17053e9aaa648b3ae42279">llvm::detail::cmpLessThan</a> and <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>

</div>
</div>

### convertFromAPInt() {#a477d9c111d2e0ae837de4f4efaf47058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::convertFromAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Input, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5293 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7a046fe3d1230e4804494ce18bae1175">llvm::APFloat::convertFromAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### convertFromSignExtendedInteger() {#ae4f54bf233710b1041d2a2218b3d9775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::convertFromSignExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> * Input, unsigned int InputSize, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5304 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a6cc309055edb782bba7bcb11b415dd17">llvm::APFloat::convertFromSignExtendedInteger</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### convertFromString() {#a5afdbe49400342f155b8076095f3e777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APFloat::opStatus &gt; llvm::detail::DoubleAPFloat::convertFromString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5267 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac83df2fb4fcefd0a95deb09db83a0635">llvm::APFloat::convertFromString</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### convertFromZeroExtendedInteger() {#a50b587c3ee7248d56ec0bb9aa8bc4dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::convertFromZeroExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> * Input, unsigned int InputSize, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af8026384a9b6bfd57046298ab64b0ea1">llvm::APFloat::convertFromZeroExtendedInteger</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### convertToHexString() {#ae9bf262be438320cef2483bf01e7222c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::detail::DoubleAPFloat::convertToHexString (char * DST, unsigned int HexDigits, bool UpperCase, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5325 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a80fcf8584733a9b06176373b10e49b17">llvm::APFloat::convertToHexString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### convertToInteger() {#a7d6416a03ebbfc3c8e49c43f65c5a84d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::convertToInteger (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/detail/#afa56d865e527ea20a3023a93a825fe6d">integerPart</a> &gt; Input, unsigned int Width, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM, bool * IsExact)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5285 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aae1f09de4bf1aab27149a7d328715e30">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### divide() {#aa4808fb08649caf3637752746bbc6bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::divide (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a107d394b970c9f03a486a15cdd08f0df">llvm::APFloat::divide</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### fusedMultiplyAdd() {#ae5a3c008b93df2ac020b72d934c4d4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::fusedMultiplyAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; Multiplicand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; Addend, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9180d9a8c1fc9693c4b0a50937e904e6">llvm::APFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### getCategory() {#a33c6882db1f9bd99a7e302f32fa5f6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::fltCategory llvm::detail::DoubleAPFloat::getCategory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5196 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aedcb51a18420d09c182442e1388b7e04">llvm::detail::frexp</a>, <a href="#a795f91a5b36b3c7ab7ac3d1ee2d6a3e6">isDenormal</a>, <a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a>, <a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a> and <a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a>.</p>

</div>
</div>

### getExactInverse() {#a58ab6474b8e70068a974fa56622abd14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::getExactInverse (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> * inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5380 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a133fbd343970e5f7e689c3b94185a605">llvm::APFloat::getExactInverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### getExactLog2() {#a17b86718d8298cad3c74ba88cd1acc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::detail::DoubleAPFloat::getExactLog2 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5391 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### getExactLog2Abs() {#a43ecda37fdadf402478d5bd62c2cb233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::detail::DoubleAPFloat::getExactLog2Abs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5396 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### getFirst() {#a16cc6b91ede24ffd11e5804afb950e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat &amp; llvm::detail::DoubleAPFloat::getFirst ()</td>
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



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getFirst() {#a2509b7c74eb65c43dcf0f07078e90b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat &amp; llvm::detail::DoubleAPFloat::getFirst ()</td>
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



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getSecond() {#a3a0a3057868abd467a880ff5390d11a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat &amp; llvm::detail::DoubleAPFloat::getSecond ()</td>
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



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getSecond() {#a20a56601f2fd189eaeca1e7737230c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat &amp; llvm::detail::DoubleAPFloat::getSecond ()</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### isDenormal() {#a795f91a5b36b3c7ab7ac3d1ee2d6a3e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isDenormal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5334 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="#a33c6882db1f9bd99a7e302f32fa5f6f3">getCategory</a> and <a href="#a795f91a5b36b3c7ab7ac3d1ee2d6a3e6">isDenormal</a>.</p>


<p>Referenced by <a href="#a795f91a5b36b3c7ab7ac3d1ee2d6a3e6">isDenormal</a>.</p>

</div>
</div>

### isInteger() {#a955dabd11aa050766069762e107f7a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>

</div>
</div>

### isLargest() {#a1ca404ac9120920af2ed205435c936bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isLargest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5358 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="#acc8a0d24edb510fef2e2cf6e62111594">compare</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="#a33c6882db1f9bd99a7e302f32fa5f6f3">getCategory</a>, <a href="#af186c5b860bb04c1748239c7eb2a3bf9">isNegative</a> and <a href="#ac3bcd088b654049f686ac4cf7c3cc90c">makeLargest</a>.</p>

</div>
</div>

### isNegative() {#af186c5b860bb04c1748239c7eb2a3bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isNegative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5200 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Referenced by <a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a>, <a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a> and <a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a>.</p>

</div>
</div>

### isSmallest() {#a5da728127b81a9ef1c5b907ca6e6c362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isSmallest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5341 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="#acc8a0d24edb510fef2e2cf6e62111594">compare</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="#a33c6882db1f9bd99a7e302f32fa5f6f3">getCategory</a>, <a href="#af186c5b860bb04c1748239c7eb2a3bf9">isNegative</a> and <a href="#a81088cb94f9459b8004ad9afab6f5757">makeSmallest</a>.</p>

</div>
</div>

### isSmallestNormalized() {#aaf6520258494aab010c0378b65b5a891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::isSmallestNormalized ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5349 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae50e2424b94617896454547784f783e5">llvm::detail::cmpEqual</a>, <a href="#acc8a0d24edb510fef2e2cf6e62111594">compare</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="#a33c6882db1f9bd99a7e302f32fa5f6f3">getCategory</a>, <a href="#af186c5b860bb04c1748239c7eb2a3bf9">isNegative</a> and <a href="#a003247d359fc96961140b0f23be2c47d">makeSmallestNormalized</a>.</p>

</div>
</div>

### makeInf() {#a874db9c0210bd1671cea824b4e6d7f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeInf (bool Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5202 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### makeLargest() {#ac3bcd088b654049f686ac4cf7c3cc90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeLargest (bool Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0d7673b95572ea1fcc00fdac680976a2">changeSign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>


<p>Referenced by <a href="#a1ca404ac9120920af2ed205435c936bc">isLargest</a>.</p>

</div>
</div>

### makeNaN() {#afd5ea12b0d71dda25b023cbe6e0fa8b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeNaN (bool SNaN, bool Neg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * fill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5234 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### makeSmallest() {#a81088cb94f9459b8004ad9afab6f5757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeSmallest (bool Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5220 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>


<p>Referenced by <a href="#a5da728127b81a9ef1c5b907ca6e6c362">isSmallest</a>.</p>

</div>
</div>

### makeSmallestNormalized() {#a003247d359fc96961140b0f23be2c47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeSmallestNormalized (bool Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>


<p>Referenced by <a href="#aaf6520258494aab010c0378b65b5a891">isSmallestNormalized</a>.</p>

</div>
</div>

### makeZero() {#a97d7acd132e0e96668ea868ed0d3bd04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::makeZero (bool Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5207 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### mod() {#ab11bb851f15cc8f484d5ba9948e14411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::mod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5141 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac3126d0302ebe7754bf962fdaa25e286">llvm::APFloat::mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### multiply() {#a314c190b5e7220bc1daa2c7fa271a63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::multiply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5036 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a44602b2ea058f08b290a8fa0185909d1">llvm::APFloat::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa714c595736fb5c03730601244b3e097">llvm::detail::fcInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a21d1e6fecdc833392793b8bc83fa1201">llvm::detail::fcNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a6c6b455d00dc7465c123eb6200636750">llvm::detail::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a582a70a1f361d031912bc4f4738936b6">llvm::detail::fcZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9180d9a8c1fc9693c4b0a50937e904e6">llvm::APFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a58e11ed4a62124e2cc8d96c1417a1d91">llvm::detail::opOK</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### needsCleanup() {#aeb0cf0c7e02302aa62e1339f09d549bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::DoubleAPFloat::needsCleanup ()</td>
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



<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### next() {#a867d044bc3f3ac08e29e98aee30c3e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::next (bool nextDown)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5276 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab0fdc79bb75e8fe845f98e2199f9d451">llvm::APFloat::next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### remainder() {#a2f8f5b97d182a63fa132a5169d82a1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::remainder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5132 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a95aaadfb3026e47b75223d2733df62f1">llvm::APFloat::remainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### roundToIntegral() {#ae3b0430f59ff83e88ee055589e1c7387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::roundToIntegral (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5162 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae4eca54fe8b71670e3bd3a2b18469d73">llvm::APFloat::roundToIntegral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>

</div>
</div>

### subtract() {#a5f71b277d8d03245a99b5faa642d107f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::subtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5028 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#af1d95621f2eb4bfd49078a9005b0f388">add</a>, <a href="#a0d7673b95572ea1fcc00fdac680976a2">changeSign</a> and <a href="#ab289b202c32cf7b49760915cec8f299a">DoubleAPFloat</a>.</p>

</div>
</div>

### toString() {#ab8a87407767d65bd07b00a21d614a74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::DoubleAPFloat::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned FormatPrecision, unsigned FormatMaxPadding, bool TruncateZero=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5371 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5231d94ec7d5c6a8962a30b0f6666478">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a> and <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a416dc650964ad640df99464a32aa49da">llvm::APFloat::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addImpl() {#aff991ed57ff55877923a6a1f22e3c2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::addImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; aa, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; c, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; cc, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4898 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

### addWithSpecial() {#a9cac08cee4de2ccd561f2a7c8a92779a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::detail::DoubleAPFloat::addWithSpecial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> &amp; Out, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 4977 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Floats {#aa3b467f8193bb24795ce5d2c8ce64d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;APFloat[]&gt; llvm::detail::DoubleAPFloat::Floats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### Semantics {#aca4fe1f75ff3ffe4c3bd193430e5932f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics* llvm::detail::DoubleAPFloat::Semantics</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
