---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantrange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantRange` Class

<p>This class represents a range of values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantRange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PreferredRangeType { <a href="#a0e6f2069000829208cbac185a07d8082">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If represented precisely, the result of some range operations may consist of multiple disjoint ranges. <a href="#a0e6f2069000829208cbac185a07d8082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OverflowResult { <a href="#ac5a96896a96f880fbd295aec85a81a87">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents whether an operation on the given constant range is known to always or never overflow. <a href="#ac5a96896a96f880fbd295aec85a81a87">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a> (uint32_t BitWidth, bool isFullSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a full or empty set for the specified bit width. <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8863b38c3cf398d6e49eb2ddf4d794a0">ConstantRange</a> (APInt Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range to hold the single specified value. <a href="#a8863b38c3cf398d6e49eb2ddf4d794a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d4542296a6b1d3954afa57fd256948">ConstantRange</a> (APInt Lower, APInt Upper)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range of values explicitly. <a href="#a61d4542296a6b1d3954afa57fd256948">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8748bc223c6110faf90246950c579112">operator==</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this range is equal to another range. <a href="#a8748bc223c6110faf90246950c579112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f0de2ee6d1ca4bb53bba22b237dee9">operator!=</a> (const ConstantRange &amp;CR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a> (CmpInst::Predicate Pred, const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the predicate <span class="doxyComputerOutput">Pred</span> hold between ranges this and <span class="doxyComputerOutput">Other</span>? <a href="#a53f1dcccf8991c637acec7883aba7bfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1616515fc811646b8cc5e6625e36b954">getEquivalentICmp</a> (CmpInst::Predicate &amp;Pred, APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up <span class="doxyComputerOutput">Pred</span> and <span class="doxyComputerOutput">RHS</span> such that ConstantRange::makeExactICmpRegion(Pred, RHS) == *this. <a href="#a1616515fc811646b8cc5e6625e36b954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a> (CmpInst::Predicate &amp;Pred, APInt &amp;RHS, APInt &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">RHS</span> and <span class="doxyComputerOutput">Offset</span> such that (V + Offset) Pred RHS is true iff V is in the range. <a href="#a81dc31883e0cc431912d8744c6cf9172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f4339e49343721146062b10c144052">getLower</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the lower value for this range. <a href="#a23f4339e49343721146062b10c144052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the upper value for this range. <a href="#aa1955c426e1ff66455b4bb6657ee995d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bit width of this <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#ad7f81241f958a1f5917a3410942d3199">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains all of the elements possible for this data-type. <a href="#a4f6242fab5145c424cee29230fefe746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains no members. <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set wraps around the unsigned domain. <a href="#a76bca22a9253d0962fd07031c89b98e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the exclusive upper bound wraps around the unsigned domain. <a href="#aa1a0c35225268e93dc3afd67e079f826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set wraps around the signed domain. <a href="#a66d4b4c9a335549fc329921f27ac67fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055ace4be97619b5dae7d6b3c4dbb4aa">isUpperSignWrapped</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the (exclusive) upper bound wraps around the signed domain. <a href="#a055ace4be97619b5dae7d6b3c4dbb4aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a> (const APInt &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified value is in the set. <a href="#aaca3a4d2b25c24b11179cbd01079b73c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbc1c19b39eab8b8473d97df0470855">contains</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the other range is a subset of this one. <a href="#a2dbc1c19b39eab8b8473d97df0470855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this set contains a single element, return it, otherwise return null. <a href="#a1d705f2b7894d43bae1ff46eaf600181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21152e890e7ed361d9ec662af218c4c8">getSingleMissingElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this set contains all but a single element, return it, otherwise return null. <a href="#a21152e890e7ed361d9ec662af218c4c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91cf2c952ea87d701fe608fe4aaabfe4">isSingleElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains exactly one member. <a href="#a91cf2c952ea87d701fe608fe4aaabfe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af656a14964b9cf9e049c1064b5f30c2b">isSizeStrictlySmallerThan</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare set size of this range with the range CR. <a href="#af656a14964b9cf9e049c1064b5f30c2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688f2c4ca99eb7f935cab42c4f6398e7">isSizeLargerThan</a> (uint64_t MaxSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare set size of this range with <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a688f2c4ca99eb7f935cab42c4f6398e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all values in this range are negative. <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a9706be916441a29cd5b93b64f033b">isAllNonNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all values in this range are non-negative. <a href="#a99a9706be916441a29cd5b93b64f033b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4ebbc65a04c2c87c8c0e60c6659ebd">isAllPositive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all values in this range are positive. <a href="#a5d4ebbc65a04c2c87c8c0e60c6659ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the largest unsigned value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the smallest unsigned value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#a4d69e164b5fb0f73a15a07119c4302f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the largest signed value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#ac45b1557ea43684a07058cb74396c435">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the smallest signed value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#a6c03477d3ea04e382431f02a0f21aa41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059a0dff9799816117b8b2fd73bd1425">getActiveBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the maximal number of active bits needed to represent every value in this range. <a href="#a059a0dff9799816117b8b2fd73bd1425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4">getMinSignedBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the maximal number of bits needed to represent every value in this signed range. <a href="#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d29074c7a610816d4f328b7cd9b783d">subtract</a> (const APInt &amp;CI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract the specified constant from the endpoints of this constant range. <a href="#a1d29074c7a610816d4f328b7cd9b783d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4790febf2bf7aa44f5283a74ddf744">difference</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract the specified range from this range (aka relative complement of the sets). <a href="#a4f4790febf2bf7aa44f5283a74ddf744">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a> (const ConstantRange &amp;CR, PreferredRangeType Type=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range that results from the intersection of this range with another range. <a href="#ac098fe4f07549fb029fbf950dbe78fd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a> (const ConstantRange &amp;CR, PreferredRangeType Type=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range that results from the union of this range with another range. <a href="#aa81521f99442a5c30f9061b8c6ce795e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb018856949929729145bb2488154fb">exactIntersectWith</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect the two ranges and return the result if it can be represented exactly, otherwise return std::nullopt. <a href="#aabb018856949929729145bb2488154fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">exactUnionWith</a> (const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Union the two ranges and return the result if it can be represented exactly, otherwise return std::nullopt. <a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a> (Instruction::CastOps CastOp, uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an application of the specified cast operator to this range. <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a> (uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range in the specified integer type, which must be strictly larger than the current type. <a href="#a636ddf018d314a1d73f98e2fa4efbafb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a> (uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range in the specified integer type, which must be strictly larger than the current type. <a href="#a9c8872e25eeddcc398a41e003e7c3f55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a> (uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range in the specified integer type, which must be strictly smaller than the current type. <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ef50c1573b919a575fccb31cc523b4">zextOrTrunc</a> (uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this range have the bit width given by <span class="doxyComputerOutput">BitWidth</span>. <a href="#a05ef50c1573b919a575fccb31cc523b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc1456c2e4f9d6d95aa0b089b3df535">sextOrTrunc</a> (uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this range have the bit width given by <span class="doxyComputerOutput">BitWidth</span>. <a href="#aebc1456c2e4f9d6d95aa0b089b3df535">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> (Instruction::BinaryOps BinOp, const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an application of the specified binary operator to an left hand side of this range and a right hand side of <span class="doxyComputerOutput">Other</span>. <a href="#ae23c0a0a029dcfece9ccade74a1e1536">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a> (Instruction::BinaryOps BinOp, const ConstantRange &amp;Other, unsigned NoWrapKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an application of the specified overflowing binary operator to a left hand side of this range and a right hand side of <span class="doxyComputerOutput">Other</span> given the provided knowledge about lack of wrapping <span class="doxyComputerOutput">NoWrapKind</span>. <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an addition of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a> (const ConstantRange &amp;Other, unsigned NoWrapKind, PreferredRangeType RangeType=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an addition with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#abf866ac0b6eda39783bee0cd94b659ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a subtraction of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a> (const ConstantRange &amp;Other, unsigned NoWrapKind, PreferredRangeType RangeType=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an subtraction with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a8e5ef756d3fd31508cb35427065209c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0309899567234d74bf87a3899207bc15">multiply</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a multiplication of a value in this range and a value in <span class="doxyComputerOutput">Other</span>, treating both this and <span class="doxyComputerOutput">Other</span> as unsigned ranges. <a href="#a0309899567234d74bf87a3899207bc15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a> (const ConstantRange &amp;Other, unsigned NoWrapKind, PreferredRangeType RangeType=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a multiplication with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return range of possible values for a signed multiplication of this and <span class="doxyComputerOutput">Other</span>. <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d25c37392410b0b31e43feae19489c">smax</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a signed maximum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#ae0d25c37392410b0b31e43feae19489c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d98815d214fb4c80537873777e91fb">umax</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an unsigned maximum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a99d98815d214fb4c80537873777e91fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a signed minimum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#ad14e808f6eb7296b587b22cc49919da7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an unsigned minimum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a4cabbd29371bbe4737500f0bf60774fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad41d307fed42f6776d36397336e81985">udiv</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an unsigned division of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#ad41d307fed42f6776d36397336e81985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a signed division of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#aa160a2ac0c31b48c41da949e53cc21b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from an unsigned remainder operation of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a336e2050c47c9d72b2cb4b13726fbba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ae77be815f3771d7e0e1837204af01">srem</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a signed remainder operation of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a51ae77be815f3771d7e0e1837204af01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a binary-xor of a value in this range by an all-one value, aka bitwise complement operation. <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a binary-and of a value in this range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#aac5f27f8d0ff473183fff55780e5796c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a binary-or of a value in this range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#ae3a906a72244158de8ae4a764e861d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a binary-xor of a value in this range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a left shift of a value in this range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#a62222502f5be2dd8e300b48469aeab4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a> (const ConstantRange &amp;Other, unsigned NoWrapKind, PreferredRangeType RangeType=Smallest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a left shift with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#aa3896afe885ae893809f7de1b23c8d7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a logical right shift of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#a452f6ecfc69e273b9005e5bac75583a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range representing the possible values resulting from a arithmetic right shift of a value in this range and a value in <span class="doxyComputerOutput">Other</span>. <a href="#aabcad8746eb26dcbb5831974e39a3d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform an unsigned saturating addition of two constant ranges. <a href="#a81da9170db4b7b8f89c9d196c07a6efb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a signed saturating addition of two constant ranges. <a href="#a54097522b509c08dd84e5ce59437c8b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform an unsigned saturating subtraction of two constant ranges. <a href="#a7a13c7e552038eb1d567e1572d91c411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a signed saturating subtraction of two constant ranges. <a href="#a993a75b630274a45cb0c20938962796f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform an unsigned saturating multiplication of two constant ranges. <a href="#a19eb872c58979381c922e31a1344e0f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a signed saturating multiplication of two constant ranges. <a href="#a5c68869b0c18ead32284ec3b461bcbf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform an unsigned saturating left shift of this constant range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#a554ba11140af2b294a7e46761dfa7865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a signed saturating left shift of this constant range by a value in <span class="doxyComputerOutput">Other</span>. <a href="#a36128583fce0d74508c8dc73e56ee905">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new range that is the logical not of the current set. <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8069837b71990713a285cb590a0eb2">abs</a> (bool IntMinIsPoison=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate absolute value range. <a href="#a6c8069837b71990713a285cb590a0eb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a> (bool ZeroIsPoison=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate ctlz range. <a href="#aea93f76a9c663074d87afbac598f5590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e6bafefba3a5989e135575377032d">cttz</a> (bool ZeroIsPoison=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate cttz range. <a href="#acc1e6bafefba3a5989e135575377032d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate ctpop range. <a href="#acde7e3c58a91a9ba77071d8a84626184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5a96896a96f880fbd295aec85a81a87">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf71829dbcdadbd24d3c22814113ebf">unsignedAddMayOverflow</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether unsigned add of the two ranges always/never overflows. <a href="#a2bf71829dbcdadbd24d3c22814113ebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5a96896a96f880fbd295aec85a81a87">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether signed add of the two ranges always/never overflows. <a href="#ab1e4a3ec7de159965bcee94fae9df74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5a96896a96f880fbd295aec85a81a87">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a99adda34abba8c6988f8292a93815">unsignedSubMayOverflow</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether unsigned sub of the two ranges always/never overflows. <a href="#a24a99adda34abba8c6988f8292a93815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5a96896a96f880fbd295aec85a81a87">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether signed sub of the two ranges always/never overflows. <a href="#ae907195afbb8c9442691836e26ac0001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5a96896a96f880fbd295aec85a81a87">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ccba85d5176205f41ad55236b7d8204">unsignedMulMayOverflow</a> (const ConstantRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether unsigned mul of the two ranges always/never overflows. <a href="#a8ccba85d5176205f41ad55236b7d8204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for values in this range. <a href="#a47ce2e594a05222051dc71da56d75d9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8831f85b65cbcc9cf42d70988845a9f6">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out the bounds to a stream. <a href="#a8831f85b65cbcc9cf42d70988845a9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e43abf85f6911f09023f40cf86cc5f">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow printing from a debugger easily. <a href="#a59e43abf85f6911f09023f40cf86cc5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3303a9b527e663fedb07bb1a01c6414">getEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create empty constant range with same bitwidth. <a href="#aa3303a9b527e663fedb07bb1a01c6414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a065ec1c29537924087dde980463d61">getFull</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create full constant range with same bitwidth. <a href="#a0a065ec1c29537924087dde980463d61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ee547501b471ca645626351803c3c1">Lower</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4394049a395030d4dc367a1c81d741e">Upper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff6f6c6a6df94af8be1bd5accff28a71">getEmpty</a> (uint32_t BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create empty constant range with the given bit width. <a href="#aff6f6c6a6df94af8be1bd5accff28a71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20bc7c6f540132189d07ad7f73bda1ee">getFull</a> (uint32_t BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create full constant range with the given bit width. <a href="#a20bc7c6f540132189d07ad7f73bda1ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a> (APInt Lower, APInt Upper)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create non-empty constant range with the given bounds. <a href="#acd8afecbb15ee69487d5339371f64a76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a211874a1535ba321cab61942cde9398f">fromKnownBits</a> (const KnownBits &amp;Known, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range based on a known bits constraint. <a href="#a211874a1535ba321cab61942cde9398f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a> (CmpInst::Predicate Pred, const ConstantRange &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the smallest range such that all values that may satisfy the given predicate with any value contained within Other is contained in the returned range. <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">makeSatisfyingICmpRegion</a> (CmpInst::Predicate Pred, const ConstantRange &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the largest range such that all values in the returned range satisfy the given predicate with all values contained within Other. <a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89e9cec92a0b38d2f47a077bf12cc98">makeExactICmpRegion</a> (CmpInst::Predicate Pred, const APInt &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the exact range such that all values in the returned range satisfy the given predicate with any value contained within Other. <a href="#aa89e9cec92a0b38d2f47a077bf12cc98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a> (const ConstantRange &amp;CR1, const ConstantRange &amp;CR2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff CR1 ult CR2 is equivalent to CR1 slt CR2. <a href="#acbd3b47b716de422bfaee19a11427884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a> (const ConstantRange &amp;CR1, const ConstantRange &amp;CR2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff CR1 ult CR2 is equivalent to CR1 sge CR2. <a href="#aaf85420850c216451bd6dcfe857bca32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca4520a4894a14c70f390091ee8d05d">getEquivalentPredWithFlippedSignedness</a> (CmpInst::Predicate Pred, const ConstantRange &amp;CR1, const ConstantRange &amp;CR2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the comparison between constant ranges this and Other is insensitive to the signedness of the comparison predicate, return a predicate equivalent to <span class="doxyComputerOutput">Pred</span>, with flipped signedness (i.e. <a href="#a1ca4520a4894a14c70f390091ee8d05d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a> (Instruction::BinaryOps BinOp, const ConstantRange &amp;Other, unsigned NoWrapKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the largest range containing all X such that "X BinOp Y" is guaranteed not to wrap (overflow) for <em>all</em> Y in Other. <a href="#ace208c0bd1d845fe49f319be6a954764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeddb6f4f9ffcb9e893e5cb321b7a7f83">makeExactNoWrapRegion</a> (Instruction::BinaryOps BinOp, const APInt &amp;Other, unsigned NoWrapKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the range that contains X if and only if "X BinOp Other" does not wrap. <a href="#aeddb6f4f9ffcb9e893e5cb321b7a7f83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac5641e821739845b8c56fa071f44ca">makeMaskNotEqualRange</a> (const APInt &amp;Mask, const APInt &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range containing all values X that satisfy <span class="doxyComputerOutput">(X &amp; Mask) != C</span>. <a href="#acac5641e821739845b8c56fa071f44ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb096a8dd6c61e17e87bc9f86db91ec">isIntrinsicSupported</a> (Intrinsic::ID IntrinsicID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> calculations are supported for intrinsic with <span class="doxyComputerOutput">IntrinsicID</span>. <a href="#a6fb096a8dd6c61e17e87bc9f86db91ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5959d13e50c78592ca89a8a964fb510c">intrinsic</a> (Intrinsic::ID IntrinsicID, ArrayRef&lt; ConstantRange &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute range of intrinsic result for the given operand ranges. <a href="#a5959d13e50c78592ca89a8a964fb510c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents a range of values.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OverflowResult {#ac5a96896a96f880fbd295aec85a81a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ConstantRange::OverflowResult </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents whether an operation on the given constant range is known to always or never overflow.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlwaysOverflowsLow<a id="ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1"></a></td>
<td class="doxyEnumItemDescription">Always overflows in the direction of signed/unsigned min value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlwaysOverflowsHigh<a id="ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e"></a></td>
<td class="doxyEnumItemDescription">Always overflows in the direction of signed/unsigned max value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayOverflow<a id="ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a"></a></td>
<td class="doxyEnumItemDescription">May or may not overflow</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NeverOverflows<a id="ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03"></a></td>
<td class="doxyEnumItemDescription">Never overflows</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

### PreferredRangeType {#a0e6f2069000829208cbac185a07d8082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ConstantRange::PreferredRangeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If represented precisely, the result of some range operations may consist of multiple disjoint ranges.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Smallest<a id="a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsigned<a id="a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Signed<a id="a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>As only a single range may be returned, any range covering these disjoint ranges constitutes a valid result, but some may be more useful than others depending on context. The preferred range type specifies whether a range that is non-wrapping in the unsigned or signed domain, or has the smallest size, is preferred. If a signedness is preferred but all ranges are non-wrapping or all wrapping, then the smallest set size is preferred. If there are multiple smallest sets, any one of them may be returned.</p>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConstantRange() {#a8cbe37c4ba99ff3bc99338fcc618c618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::ConstantRange (uint32_t BitWidth, bool isFullSet)</td>
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

<p>Initialize a full or empty set for the specified bit width.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">llvm::Full</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>, <a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a>, <a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a>, <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="#a2dbc1c19b39eab8b8473d97df0470855">contains</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="#a4f4790febf2bf7aa44f5283a74ddf744">difference</a>, <a href="#aabb018856949929729145bb2488154fb">exactIntersectWith</a>, <a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">exactUnionWith</a>, <a href="#a211874a1535ba321cab61942cde9398f">fromKnownBits</a>, <a href="#aff6f6c6a6df94af8be1bd5accff28a71">getEmpty</a>, <a href="#a1ca4520a4894a14c70f390091ee8d05d">getEquivalentPredWithFlippedSignedness</a>, <a href="#a20bc7c6f540132189d07ad7f73bda1ee">getFull</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5959d13e50c78592ca89a8a964fb510c">intrinsic</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a>, <a href="#af656a14964b9cf9e049c1064b5f30c2b">isSizeStrictlySmallerThan</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#aa89e9cec92a0b38d2f47a077bf12cc98">makeExactICmpRegion</a>, <a href="#aeddb6f4f9ffcb9e893e5cb321b7a7f83">makeExactNoWrapRegion</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>, <a href="#acac5641e821739845b8c56fa071f44ca">makeMaskNotEqualRange</a>, <a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">makeSatisfyingICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="#ac9f0de2ee6d1ca4bb53bba22b237dee9">operator!=</a>, <a href="#a8748bc223c6110faf90246950c579112">operator==</a>, <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#aebc1456c2e4f9d6d95aa0b089b3df535">sextOrTrunc</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a>, <a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a>, <a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a>, <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="#a1d29074c7a610816d4f328b7cd9b783d">subtract</a>, <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>, <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>, <a href="#a2bf71829dbcdadbd24d3c22814113ebf">unsignedAddMayOverflow</a>, <a href="#a8ccba85d5176205f41ad55236b7d8204">unsignedMulMayOverflow</a>, <a href="#a24a99adda34abba8c6988f8292a93815">unsignedSubMayOverflow</a>, <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>, <a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a>, <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a>, <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a> and <a href="#a05ef50c1573b919a575fccb31cc523b4">zextOrTrunc</a>.</p>

</div>
</div>

### ConstantRange() {#a8863b38c3cf398d6e49eb2ddf4d794a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::ConstantRange (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a range to hold the single specified value.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### ConstantRange() {#a61d4542296a6b1d3954afa57fd256948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::ConstantRange (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Lower, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Upper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a range of values explicitly.</p>


<p>This will assert out if Lower==Upper and Lower != Min or Max value for its type. It will also assert out if the two <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s are not the same bit width.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ac9f0de2ee6d1ca4bb53bba22b237dee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRange::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a>.</p>

</div>
</div>

### operator==() {#a8748bc223c6110faf90246950c579112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRange::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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

<p>Return true if this range is equal to another range.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Reference <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### abs() {#a6c8069837b71990713a285cb590a0eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::abs (bool IntMinIsPoison=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate absolute value range.</p>


<p>If the original range contains signed min, then the resulting range will contain signed min if and only if <span class="doxyComputerOutput">IntMinIsPoison</span> is false.</p>


<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1943 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>.</p>

</div>
</div>

### add() {#a04b4ad79ea8ce56e62e0e0323d302eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an addition of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>, <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>.</p>

</div>
</div>

### addWithNoWrap() {#abf866ac0b6eda39783bee0cd94b659ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::addWithNoWrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> RangeType=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an addition with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>If the result range is disjoint, the preferred range is determined by the <span class="doxyComputerOutput"><a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a></span>.</p>


<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a> and <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>.</p>


<p>Referenced by <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>.</p>

</div>
</div>

### ashr() {#aabcad8746eb26dcbb5831974e39a3d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::ashr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a arithmetic right shift of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6006923d1a3139d70abc8f6552a7960">llvm::APInt::ashr</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> and <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>.</p>

</div>
</div>

### binaryAnd() {#aac5f27f8d0ff473183fff55780e5796c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::binaryAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a binary-and of a value in this range by a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1580 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a437967d8acddbcdb8cb345412f22f9dd">estimateBitMaskedAndLowerBound</a>, <a href="#a211874a1535ba321cab61942cde9398f">fromKnownBits</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a61e3236cbe0cbc94e306beb52ae1093d">canScalarizeAccess</a>.</p>

</div>
</div>

### binaryNot() {#adc0733404e2b3c8b3bd7edb2e9021fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::binaryNot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a binary-xor of a value in this range by an all-one value, aka bitwise complement operation.</p>

<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1519 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a> and <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>.</p>


<p>Referenced by <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>.</p>

</div>
</div>

### binaryOp() {#ae23c0a0a029dcfece9ccade74a1e1536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::binaryOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> BinOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an application of the specified binary operator to an left hand side of this range and a right hand side of <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a> and <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>.</p>


<p>Referenced by <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>.</p>

</div>
</div>

### binaryOr() {#ae3a906a72244158de8ae4a764e861d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::binaryOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a binary-or of a value in this range by a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1592 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a437967d8acddbcdb8cb345412f22f9dd">estimateBitMaskedAndLowerBound</a>, <a href="#a211874a1535ba321cab61942cde9398f">fromKnownBits</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>.</p>

</div>
</div>

### binaryXor() {#a1f9b8b85cda6501eec16b6804b22c8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::binaryXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a binary-xor of a value in this range by a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1612 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a211874a1535ba321cab61942cde9398f">fromKnownBits</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a91cf2c952ea87d701fe608fe4aaabfe4">isSingleElement</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a>, <a href="#a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc">Unsigned</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>.</p>

</div>
</div>

### castOp() {#a4c3a3d6e30e1512fd3b160cae4025f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::castOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> CastOp, uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an application of the specified cast operator to this range.</p>


<p><span class="doxyComputerOutput">BitWidth</span> is the target bitwidth of the cast. For casts which don't change bitwidth, it must be the same as the source bitwidth. For casts which do change bitwidth, the bitwidth must be consistent with the requested cast and source bitwidth.</p>


<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### contains() {#aaca3a4d2b25c24b11179cbd01079b73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified value is in the set.</p>

<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a35dd2e0efa71641e526e898918af9ef6">addNoUndefAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a61e3236cbe0cbc94e306beb52ae1093d">canScalarizeAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#acd47afc26efebd49949d38018cfc29ce">cmpExcludesZero</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a17e35fd9a6e590c201fd05105589ce47">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afbd26f64ed2e22a81bf690e93aa121a0">llvm::ValueLatticeElement::markConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ac436d2178c40d1c44632daa737b39323">narrowSDivOrSRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a7003e88a45464bf7190910b8a8de6778">processBinOp</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a002b7ea3a854166ae7ffe9d0e3e994d7">simplifySwitchOnSelectUsingRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a52da671999cb61370bfe5c7e9fee966f">willNotOverflow</a>.</p>

</div>
</div>

### contains() {#a2dbc1c19b39eab8b8473d97df0470855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the other range is a subset of this one.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ctlz() {#aea93f76a9c663074d87afbac598f5590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::ctlz (bool ZeroIsPoison=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate ctlz range.</p>


<p>If <span class="doxyComputerOutput">ZeroIsPoison</span> is set, the range is computed ignoring a possible zero value contained in the input range.</p>


<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1985 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>

</div>
</div>

### ctpop() {#acde7e3c58a91a9ba77071d8a84626184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::ctpop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate ctpop range.</p>

<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2117 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a623310118173612285ce605149f43264">getUnsignedPopCountRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>

</div>
</div>

### cttz() {#acc1e6bafefba3a5989e135575377032d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::cttz (bool ZeroIsPoison=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate cttz range.</p>


<p>If <span class="doxyComputerOutput">ZeroIsPoison</span> is set, the range is computed ignoring a possible zero value contained in the input range.</p>


<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#ae6e0521392f7c7e8a1daa7511a533201">getUnsignedCountTrailingZerosRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>

</div>
</div>

### difference() {#a4f4790febf2bf7aa44f5283a74ddf744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::difference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract the specified range from this range (aka relative complement of the sets).</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a> and <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>.</p>

</div>
</div>

### dump() {#a59e43abf85f6911f09023f40cf86cc5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ConstantRange::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow printing from a debugger easily.</p>

<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2259 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a8831f85b65cbcc9cf42d70988845a9f6">print</a>.</p>

</div>
</div>

### exactIntersectWith() {#aabb018856949929729145bb2488154fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; ConstantRange::exactIntersectWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Intersect the two ranges and return the result if it can be represented exactly, otherwise return std::nullopt.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>.</p>

</div>
</div>

### exactUnionWith() {#a104cf3ac04ba840d0bd3b37685d6cdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; ConstantRange::exactUnionWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Union the two ranges and return the result if it can be represented exactly, otherwise return std::nullopt.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>.</p>

</div>
</div>

### getActiveBits() {#a059a0dff9799816117b8b2fd73bd1425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ConstantRange::getActiveBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the maximal number of active bits needed to represent every value in this range.</p>

<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a> and <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a54ea77d9e8070a1a18b224d984b12c1b">llvm::TargetLoweringBase::getBitWidthForCttzElements</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a4e3963b153cad98b7c128ef627f20b65">narrowUDivOrURem</a>.</p>

</div>
</div>

### getBitWidth() {#ad7f81241f958a1f5917a3410942d3199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConstantRange::getBitWidth ()</td>
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

<p>Get the bit width of this <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a8c825d8718637fb081db2cf8fbade190">getDomain</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="#a688f2c4ca99eb7f935cab42c4f6398e7">isSizeLargerThan</a>, <a href="#af656a14964b9cf9e049c1064b5f30c2b">isSizeStrictlySmallerThan</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#aebc1456c2e4f9d6d95aa0b089b3df535">sextOrTrunc</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a>, <a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a1d29074c7a610816d4f328b7cd9b783d">subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>, <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>, <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a> and <a href="#a05ef50c1573b919a575fccb31cc523b4">zextOrTrunc</a>.</p>

</div>
</div>

### getEquivalentICmp() {#a1616515fc811646b8cc5e6625e36b954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::getEquivalentICmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &amp; Pred, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up <span class="doxyComputerOutput">Pred</span> and <span class="doxyComputerOutput">RHS</span> such that ConstantRange::makeExactICmpRegion(Pred, RHS) == *this.</p>


<p>Return true if successful.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a1616515fc811646b8cc5e6625e36b954">getEquivalentICmp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="#a1616515fc811646b8cc5e6625e36b954">getEquivalentICmp</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>.</p>

</div>
</div>

### getEquivalentICmp() {#a81dc31883e0cc431912d8744c6cf9172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantRange::getEquivalentICmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &amp; Pred, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">RHS</span> and <span class="doxyComputerOutput">Offset</span> such that (V + Offset) Pred RHS is true iff V is in the range.</p>


<p>Prefers using Offset == 0 if possible.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#a21152e890e7ed361d9ec662af218c4c8">getSingleMissingElement</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="#aa89e9cec92a0b38d2f47a077bf12cc98">makeExactICmpRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getLower() {#a23f4339e49343721146062b10c144052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt &amp; llvm::ConstantRange::getLower ()</td>
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

<p>Return the lower value for this range.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Referenced by <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1f33826a7081abb8cd61583464d7ca51">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getMDNodeForConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a81f32bf88f0c95803ac134210308d54c">llvm::ConstantRangeList::print</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#af02f5875e490164276cc8aac0f31b78e">llvm::AttributeImpl::Profile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#ad16e6a0c972042439d77b4a665f69d9f">llvm::ConstantRangeList::unionWith</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>.</p>

</div>
</div>

### getMinSignedBits() {#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ConstantRange::getMinSignedBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the maximal number of bits needed to represent every value in this signed range.</p>

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a> and <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ac436d2178c40d1c44632daa737b39323">narrowSDivOrSRem</a>.</p>

</div>
</div>

### getSignedMax() {#ac45b1557ea43684a07058cb74396c435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantRange::getSignedMax ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the largest signed value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>

<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a055ace4be97619b5dae7d6b3c4dbb4aa">isUpperSignWrapped</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4">getMinSignedBits</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a>, <a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a>, <a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a> and <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>.</p>

</div>
</div>

### getSignedMin() {#a6c03477d3ea04e382431f02a0f21aa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantRange::getSignedMin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the smallest signed value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>

<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4">getMinSignedBits</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a>, <a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a>, <a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a> and <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>.</p>

</div>
</div>

### getSingleElement() {#a1d705f2b7894d43bae1ff46eaf600181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt * llvm::ConstantRange::getSingleElement ()</td>
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

<p>If this set contains a single element, return it, otherwise return null.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a414095f3b62e33f0c3113205c44b65fd">llvm::ValueLatticeElement::asConstantInteger</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a1e99011cd6c37ad4ab5be287c94735bf">llvm::AAValueConstantRange::getAssumedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a8da33528c75f7337a0a4b87118c63340">llvm::LazyValueInfo::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a267e38911b1fc5417bb5f634ac53a261">llvm::SCCPInstVisitor::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a4185eb721dbdc35f95d06445db6ad5e8">llvm::LazyValueInfo::getConstantOnEdge</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e362f3699fd2c3f46c7a3690031dda3">llvm::SelectionDAG::getVScale</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#a91cf2c952ea87d701fe608fe4aaabfe4">isSingleElement</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a> and <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>.</p>

</div>
</div>

### getSingleMissingElement() {#a21152e890e7ed361d9ec662af218c4c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt * llvm::ConstantRange::getSingleMissingElement ()</td>
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

<p>If this set contains all but a single element, return it, otherwise return null.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Referenced by <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>.</p>

</div>
</div>

### getUnsignedMax() {#ab7f67c2ed8b2799c64ec64ca31d75c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantRange::getUnsignedMax ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the largest unsigned value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>

<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>.</p>


<p>Referenced by <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#a059a0dff9799816117b8b2fd73bd1425">getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a2003053288ba4f0e1cd9ebf82b6a1987">mustBeFiniteCountedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a08d14454ee4850cd50dd4e1dbb48d19f">processAnd</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a>, <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>, <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>, <a href="#a2bf71829dbcdadbd24d3c22814113ebf">unsignedAddMayOverflow</a>, <a href="#a8ccba85d5176205f41ad55236b7d8204">unsignedMulMayOverflow</a>, <a href="#a24a99adda34abba8c6988f8292a93815">unsignedSubMayOverflow</a>, <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>, <a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a> and <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a>.</p>

</div>
</div>

### getUnsignedMin() {#a4d69e164b5fb0f73a15a07119c4302f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantRange::getUnsignedMin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the smallest unsigned value contained in the <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>

<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a>.</p>


<p>Referenced by <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a>, <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>, <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>, <a href="#a2bf71829dbcdadbd24d3c22814113ebf">unsignedAddMayOverflow</a>, <a href="#a8ccba85d5176205f41ad55236b7d8204">unsignedMulMayOverflow</a>, <a href="#a24a99adda34abba8c6988f8292a93815">unsignedSubMayOverflow</a>, <a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a> and <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a>.</p>

</div>
</div>

### getUpper() {#aa1955c426e1ff66455b4bb6657ee995d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt &amp; llvm::ConstantRange::getUpper ()</td>
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

<p>Return the upper value for this range.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Referenced by <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1f33826a7081abb8cd61583464d7ca51">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getMDNodeForConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a81f32bf88f0c95803ac134210308d54c">llvm::ConstantRangeList::print</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#af02f5875e490164276cc8aac0f31b78e">llvm::AttributeImpl::Profile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#ad16e6a0c972042439d77b4a665f69d9f">llvm::ConstantRangeList::unionWith</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>.</p>

</div>
</div>

### icmp() {#a53f1dcccf8991c637acec7883aba7bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::icmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the predicate <span class="doxyComputerOutput">Pred</span> hold between ranges this and <span class="doxyComputerOutput">Other</span>?</p>


<p>NOTE: false does not mean that inverse predicate holds!</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae2b7d8c018c8a37fa8ea422a13bfd412">llvm::APInt::sge</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e8226e6453c8bcf7e5c06d28b1e207b">llvm::APInt::sle</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a3017b0d25a7e8961371e80a5fe4b10c7">expandUDivOrURem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a8c825d8718637fb081db2cf8fbade190">getDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4f30233ac0c825f0a38b55470569d7b7">isImpliedCondCommonOperandWithCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aaa116d55b70fa3716c4ee6f0eb3488d8">processCmpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### intersectWith() {#ac098fe4f07549fb029fbf950dbe78fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::intersectWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> Type=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the range that results from the intersection of this range with another range.</p>


<p>If the intersection is disjoint, such that two results are possible, the preferred range is determined by the <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a>.</p>


<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#abae944a67cbc6299389596f63df4359a">areNonOverlapSameBaseLoadAndStore</a>, <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0eb8e591794bfc8e474a0a68c1135b0">llvm::computeConstantRangeIncludingKnownBits</a>, <a href="#a4f4790febf2bf7aa44f5283a74ddf744">difference</a>, <a href="#aabb018856949929729145bb2488154fb">exactIntersectWith</a>, <a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">exactUnionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a975cd575019795ff8714252a22f27c26">llvm::ValueLatticeElement::intersect</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a> and <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>.</p>

</div>
</div>

### inverse() {#aaaa2f5e2c6c3122d2b484f9e50950e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::inverse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range that is the logical not of the current set.</p>

<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1935 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a> and <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="#a4f4790febf2bf7aa44f5283a74ddf744">difference</a>, <a href="#aabb018856949929729145bb2488154fb">exactIntersectWith</a>, <a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">exactUnionWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">makeSatisfyingICmpRegion</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>.</p>

</div>
</div>

### isAllNegative() {#a256a302a20f8f9c2c02c9ca2d41ea78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isAllNegative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all values in this range are negative.</p>

<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a055ace4be97619b5dae7d6b3c4dbb4aa">isUpperSignWrapped</a>.</p>


<p>Referenced by <a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a>, <a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a3017b0d25a7e8961371e80a5fe4b10c7">expandUDivOrURem</a> and <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>.</p>

</div>
</div>

### isAllNonNegative() {#a99a9706be916441a29cd5b93b64f033b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isAllNonNegative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all values in this range are non-negative.</p>

<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Reference <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>.</p>


<p>Referenced by <a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a>, <a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a8c825d8718637fb081db2cf8fbade190">getDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#adb80e83dbc996ecb55080dd0756eb5ba">processPossibleNonNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>.</p>

</div>
</div>

### isAllPositive() {#a5d4ebbc65a04c2c87c8c0e60c6659ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isAllPositive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all values in this range are positive.</p>

<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>.</p>

</div>
</div>

### isEmptySet() {#a5bd6d98b4a7ecc1dcdc571e4352fcc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isEmptySet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set contains no members.</p>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>, <a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a>, <a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#abae944a67cbc6299389596f63df4359a">areNonOverlapSameBaseLoadAndStore</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="#a2dbc1c19b39eab8b8473d97df0470855">contains</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="#a059a0dff9799816117b8b2fd73bd1425">getActiveBits</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a1e99011cd6c37ad4ab5be287c94735bf">llvm::AAValueConstantRange::getAssumedConstant</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="#ad46cf5ed2886b5dbbcfb1c80dcfbf9d4">getMinSignedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="#a53f1dcccf8991c637acec7883aba7bfc">icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a>, <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>, <a href="#a5d4ebbc65a04c2c87c8c0e60c6659ebd">isAllPositive</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a12fa48f6f87955f0d3b9a0912669ef38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afbd26f64ed2e22a81bf690e93aa121a0">llvm::ValueLatticeElement::markConstantRange</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="#a8831f85b65cbcc9cf42d70988845a9f6">print</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a679c2e4baff0b3b8eff40752f5a3e222">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::setRangeMetadataIfisBetterRange</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a>, <a href="#ab1e4a3ec7de159965bcee94fae9df74b">signedAddMayOverflow</a>, <a href="#ae907195afbb8c9442691836e26ac0001">signedSubMayOverflow</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a>, <a href="#a51ae77be815f3771d7e0e1837204af01">srem</a>, <a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a>, <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>, <a href="#a47ce2e594a05222051dc71da56d75d9b">toKnownBits</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>, <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>, <a href="#a2bf71829dbcdadbd24d3c22814113ebf">unsignedAddMayOverflow</a>, <a href="#a8ccba85d5176205f41ad55236b7d8204">unsignedMulMayOverflow</a>, <a href="#a24a99adda34abba8c6988f8292a93815">unsignedSubMayOverflow</a>, <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>, <a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a>, <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a> and <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a>.</p>

</div>
</div>

### isFullSet() {#a4f6242fab5145c424cee29230fefe746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isFullSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set contains all of the elements possible for this data-type.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#a04b4ad79ea8ce56e62e0e0323d302eec">add</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a773374bcf6e6f638f8a996c1df6cc998">llvm::AttrBuilder::addConstantRangeAttr</a>, <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>, <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="#a2dbc1c19b39eab8b8473d97df0470855">contains</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1f33826a7081abb8cd61583464d7ca51">llvm::Attribute::get</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a>, <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>, <a href="#a5d4ebbc65a04c2c87c8c0e60c6659ebd">isAllPositive</a>, <a href="#a688f2c4ca99eb7f935cab42c4f6398e7">isSizeLargerThan</a>, <a href="#af656a14964b9cf9e049c1064b5f30c2b">isSizeStrictlySmallerThan</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a12fa48f6f87955f0d3b9a0912669ef38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afbd26f64ed2e22a81bf690e93aa121a0">llvm::ValueLatticeElement::markConstantRange</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="#a8831f85b65cbcc9cf42d70988845a9f6">print</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#ad208209f7eed8f99f1b06f30d6177647">anonymous{StackSafetyAnalysis.cpp}::resolveAllCalls</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a>.</p>

</div>
</div>

### isSignWrappedSet() {#a66d4b4c9a335549fc329921f27ac67fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isSignWrappedSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set wraps around the signed domain.</p>


<p>Special cases:</p>


<ul class="doxyList ">
<li>Empty set: Not wrapped.</li>
<li>Full set: Not wrapped.</li>
<li>[X, SignedMin) == [X, SignedMax]: Not wrapped.</li>
</ul>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a99a9706be916441a29cd5b93b64f033b">isAllNonNegative</a>, <a href="#a5d4ebbc65a04c2c87c8c0e60c6659ebd">isAllPositive</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a> and <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>.</p>

</div>
</div>

### isSingleElement() {#a91cf2c952ea87d701fe608fe4aaabfe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRange::isSingleElement ()</td>
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

<p>Return true if this set contains exactly one member.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Reference <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>.</p>


<p>Referenced by <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a59121faba668261cf400df39e3592637">hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc80238c61c9232dfd8114e30dbf7c18">llvm::hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ad443783793d65506b0b69745c79d26d5">llvm::SCCPSolver::isConstant</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a12fa48f6f87955f0d3b9a0912669ef38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest</a>.</p>

</div>
</div>

### isSizeLargerThan() {#a688f2c4ca99eb7f935cab42c4f6398e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isSizeLargerThan (uint64_t MaxSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare set size of this range with <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>.</p>

</div>
</div>

### isSizeStrictlySmallerThan() {#af656a14964b9cf9e049c1064b5f30c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isSizeStrictlySmallerThan (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare set size of this range with the range CR.</p>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a> and <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>.</p>

</div>
</div>

### isUpperSignWrapped() {#a055ace4be97619b5dae7d6b3c4dbb4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isUpperSignWrapped ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the (exclusive) upper bound wraps around the signed domain.</p>


<p>Special cases:</p>


<ul class="doxyList ">
<li>Empty set: Not wrapped.</li>
<li>Full set: Not wrapped.</li>
<li>[X, SignedMin): Wrapped.</li>
</ul>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a> and <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>.</p>

</div>
</div>

### isUpperWrapped() {#aa1a0c35225268e93dc3afd67e079f826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isUpperWrapped ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the exclusive upper bound wraps around the unsigned domain.</p>


<p>Special cases:</p>


<ul class="doxyList ">
<li>Empty set: Not wrapped.</li>
<li>Full set: Not wrapped.</li>
<li>[X, 0): Wrapped.</li>
</ul>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="#a2dbc1c19b39eab8b8473d97df0470855">contains</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a> and <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a>.</p>

</div>
</div>

### isWrappedSet() {#a76bca22a9253d0962fd07031c89b98e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isWrappedSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set wraps around the unsigned domain.</p>


<p>Special cases:</p>


<ul class="doxyList ">
<li>Empty set: Not wrapped.</li>
<li>Full set: Not wrapped.</li>
<li>[X, 0) == [X, Max]: Not wrapped.</li>
</ul>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a> and <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>.</p>

</div>
</div>

### lshr() {#a452f6ecfc69e273b9005e5bac75583a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::lshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a logical right shift of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1789 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> and <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>.</p>

</div>
</div>

### multiply() {#a0309899567234d74bf87a3899207bc15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::multiply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a multiplication of a value in this range and a value in <span class="doxyComputerOutput">Other</span>, treating both this and <span class="doxyComputerOutput">Other</span> as unsigned ranges.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="#af656a14964b9cf9e049c1064b5f30c2b">isSizeStrictlySmallerThan</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a> and <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>.</p>

</div>
</div>

### multiplyWithNoWrap() {#af8daf8a07b3ab8645d4a6524caf57e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::multiplyWithNoWrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> RangeType=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a multiplication with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>If the result range is disjoint, the preferred range is determined by the <span class="doxyComputerOutput"><a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a></span>.</p>


<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aac3172f238278728e355fc9a87c439dd5">llvm::OverflowingBinaryOperator::NoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aa7d34304df400cdb020e71e182ac06cb7">llvm::OverflowingBinaryOperator::NoUnsignedWrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a> and <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>.</p>


<p>Referenced by <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>.</p>

</div>
</div>

### overflowingBinaryOp() {#a87d22942f8d1a8b5e8eb92072b6dfc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::overflowingBinaryOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> BinOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an application of the specified overflowing binary operator to a left hand side of this range and a right hand side of <span class="doxyComputerOutput">Other</span> given the provided knowledge about lack of wrapping <span class="doxyComputerOutput">NoWrapKind</span>.</p>

<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a> and <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>.</p>

</div>
</div>

### print() {#a8831f85b65cbcc9cf42d70988845a9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantRange::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out the bounds to a stream.</p>

<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2249 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a> and <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>.</p>


<p>Referenced by <a href="#a59e43abf85f6911f09023f40cf86cc5f">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad0413bda2ca1ab6c3fc7575b4172100">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a5d9712817e5a3a55a593c62ed3a698">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a77b275a78beac200ef1f703d2a5fbb7d">llvm::ScalarEvolution::print</a>.</p>

</div>
</div>

### sadd\_sat() {#a54097522b509c08dd84e5ce59437c8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::sadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a signed saturating addition of two constant ranges.</p>

<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1858 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c1e0381aeb551ad0ba58effe9232f97">llvm::APInt::sadd_sat</a>.</p>


<p>Referenced by <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a>.</p>

</div>
</div>

### sdiv() {#aa160a2ac0c31b48c41da949e53cc21b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::sdiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a signed division of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>Division by zero and division of SignedMin by -1 are considered undefined behavior, in line with IR, and do not contribute towards the result.</p>


<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#aaca3a4d2b25c24b11179cbd01079b73c">contains</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1">Signed</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a> and <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>.</p>

</div>
</div>

### sextOrTrunc() {#aebc1456c2e4f9d6d95aa0b089b3df535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::sextOrTrunc (uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this range have the bit width given by <span class="doxyComputerOutput">BitWidth</span>.</p>


<p>The value is sign extended, truncated, or left alone to make it that width.</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a9c8872e25eeddcc398a41e003e7c3f55">signExtend</a> and <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#ad208209f7eed8f99f1b06f30d6177647">anonymous{StackSafetyAnalysis.cpp}::resolveAllCalls</a>.</p>

</div>
</div>

### shl() {#a62222502f5be2dd8e300b48469aeab4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::shl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a left shift of a value in this range by a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>TODO: This isn't fully implemented yet.</p>


<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa619d96a87c8a5be606b1a4a4ac0115d">llvm::APInt::countl_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aeaf22e8d92fd978a5eca9ab031994399">llvm::APInt::getBitsSetFrom</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> and <a href="#aa3896afe885ae893809f7de1b23c8d7b">shlWithNoWrap</a>.</p>

</div>
</div>

### shlWithNoWrap() {#aa3896afe885ae893809f7de1b23c8d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::shlWithNoWrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> RangeType=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a left shift with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>If the result range is disjoint, the preferred range is determined by the <span class="doxyComputerOutput"><a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a></span>.</p>


<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aac3172f238278728e355fc9a87c439dd5">llvm::OverflowingBinaryOperator::NoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aa7d34304df400cdb020e71e182ac06cb7">llvm::OverflowingBinaryOperator::NoUnsignedWrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>.</p>


<p>Referenced by <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>.</p>

</div>
</div>

### signedAddMayOverflow() {#ab1e4a3ec7de159965bcee94fae9df74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::OverflowResult ConstantRange::signedAddMayOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether signed add of the two ranges always/never overflows.</p>

<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2153 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">AlwaysOverflowsHigh</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1">AlwaysOverflowsLow</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">MayOverflow</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">NeverOverflows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>.</p>

</div>
</div>

### signedSubMayOverflow() {#ae907195afbb8c9442691836e26ac0001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::OverflowResult ConstantRange::signedSubMayOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether signed sub of the two ranges always/never overflows.</p>

<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2199 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">AlwaysOverflowsHigh</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1">AlwaysOverflowsLow</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">MayOverflow</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">NeverOverflows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b72ea7b10ac690e8f1bcdf144c7e5d4">llvm::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad682eaa6ebe25c01cdd86c1456fbeacf">llvm::SelectionDAG::computeOverflowForSignedSub</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adc129334a6d3d83eb003dd1a49540f80">llvm::CombinerHelper::matchSuboCarryOut</a>.</p>

</div>
</div>

### signExtend() {#a9c8872e25eeddcc398a41e003e7c3f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::signExtend (uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range in the specified integer type, which must be strictly larger than the current type.</p>


<p>The returned range will correspond to the possible range of values if the source range had been sign extended to BitWidth.</p>


<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a> and <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>.</p>


<p>Referenced by <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a> and <a href="#aebc1456c2e4f9d6d95aa0b089b3df535">sextOrTrunc</a>.</p>

</div>
</div>

### smax() {#ae0d25c37392410b0b31e43feae19489c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::smax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a signed maximum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1">Signed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>

</div>
</div>

### smin() {#ad14e808f6eb7296b587b22cc49919da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::smin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a signed minimum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a66d4b4c9a335549fc329921f27ac67fc">isSignWrappedSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1">Signed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a688eca8fbe6295f4b002f1e705d3e916">llvm::APIntOps::smin</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>

</div>
</div>

### smul\_fast() {#a3a4758c17c35cfcd1f67a4a119a95ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::smul_fast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return range of possible values for a signed multiplication of this and <span class="doxyComputerOutput">Other</span>.</p>


<p>However, if overflow is possible always return a full range rather than trying to determine a more precise result.</p>


<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ac155d7c568fc1aba25723e77b6888908">llvm::APInt::smul_ov</a>.</p>

</div>
</div>

### smul\_sat() {#a5c68869b0c18ead32284ec3b461bcbf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::smul_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a signed saturating multiplication of two constant ranges.</p>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1894 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a36f62de4b8b82d2f73fb4efda79954f0">llvm::APInt::smul_sat</a>.</p>


<p>Referenced by <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>.</p>

</div>
</div>

### srem() {#a51ae77be815f3771d7e0e1837204af01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::srem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a signed remainder operation of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1468 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>.</p>

</div>
</div>

### sshl\_sat() {#a36128583fce0d74508c8dc73e56ee905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::sshl_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a signed saturating left shift of this constant range by a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1924 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a90e6be77d59fee53e8585874cd1ab07c">llvm::APInt::sshl_sat</a>.</p>

</div>
</div>

### ssub\_sat() {#a993a75b630274a45cb0c20938962796f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::ssub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a signed saturating subtraction of two constant ranges.</p>

<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1876 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af888cb3cadd9a4e5f422c96e5674de88">llvm::APInt::ssub_sat</a>.</p>


<p>Referenced by <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>.</p>

</div>
</div>

### sub() {#aeb57116b101c8d1263ff5ffdaccdcad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::sub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from a subtraction of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#adc0733404e2b3c8b3bd7edb2e9021fae">binaryNot</a>, <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a> and <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>.</p>

</div>
</div>

### subtract() {#a1d29074c7a610816d4f328b7cd9b783d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::subtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract the specified constant from the endpoints of this constant range.</p>

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a> and <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a54ea77d9e8070a1a18b224d984b12c1b">llvm::TargetLoweringBase::getBitWidthForCttzElements</a>.</p>

</div>
</div>

### subWithNoWrap() {#a8e5ef756d3fd31508cb35427065209c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::subWithNoWrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> RangeType=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an subtraction with wrap type <span class="doxyComputerOutput">NoWrapKind</span> of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>


<p>If the result range is disjoint, the preferred range is determined by the <span class="doxyComputerOutput"><a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a></span>.</p>


<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>, <a href="#aeb57116b101c8d1263ff5ffdaccdcad0">sub</a> and <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a>.</p>


<p>Referenced by <a href="#a87d22942f8d1a8b5e8eb92072b6dfc8b">overflowingBinaryOp</a>.</p>

</div>
</div>

### toKnownBits() {#a47ce2e594a05222051dc71da56d75d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits ConstantRange::toKnownBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for values in this range.</p>

<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aac76bff09195240a482b319136ab6144">llvm::APInt::clearLowBits</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a01bcab155ce8678014668a750c05a7b6">llvm::APIntOps::GetMostSignificantDifferentBit</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### truncate() {#a2bc441c8fe8dfeea5471f11d2d823ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::truncate (uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range in the specified integer type, which must be strictly smaller than the current type.</p>


<p>The returned range will correspond to the possible range of values if the source range had been truncated to the specified type.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a155466c9ea0a2bd00e09c62fdce2c052">llvm::APInt::clearBit</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aeaf22e8d92fd978a5eca9ab031994399">llvm::APInt::getBitsSetFrom</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="#a0309899567234d74bf87a3899207bc15">multiply</a>, <a href="#aebc1456c2e4f9d6d95aa0b089b3df535">sextOrTrunc</a> and <a href="#a05ef50c1573b919a575fccb31cc523b4">zextOrTrunc</a>.</p>

</div>
</div>

### uadd\_sat() {#a81da9170db4b7b8f89c9d196c07a6efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::uadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform an unsigned saturating addition of two constant ranges.</p>

<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1849 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ab4c04665274d4f30d732639dc055821c">llvm::APInt::uadd_sat</a>.</p>


<p>Referenced by <a href="#abf866ac0b6eda39783bee0cd94b659ba">addWithNoWrap</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a3017b0d25a7e8961371e80a5fe4b10c7">expandUDivOrURem</a>.</p>

</div>
</div>

### udiv() {#ad41d307fed42f6776d36397336e81985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::udiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an unsigned division of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a>.</p>

</div>
</div>

### umax() {#a99d98815d214fb4c80537873777e91fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::umax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an unsigned maximum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a> and <a href="#a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc">Unsigned</a>.</p>

</div>
</div>

### umin() {#a4cabbd29371bbe4737500f0bf60774fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::umin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an unsigned minimum of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a76bca22a9253d0962fd07031c89b98e7">isWrappedSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>, <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a> and <a href="#a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc">Unsigned</a>.</p>

</div>
</div>

### umul\_sat() {#a19eb872c58979381c922e31a1344e0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::umul_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform an unsigned saturating multiplication of two constant ranges.</p>

<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1885 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#acf4d36ebf88039604b73d3527506c3ed">llvm::APInt::umul_sat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a54ea77d9e8070a1a18b224d984b12c1b">llvm::TargetLoweringBase::getBitWidthForCttzElements</a> and <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>.</p>

</div>
</div>

### unionWith() {#aa81521f99442a5c30f9061b8c6ce795e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::unionWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR, <a href="#a0e6f2069000829208cbac185a07d8082">PreferredRangeType</a> Type=<a href="#a0e6f2069000829208cbac185a07d8082a25a373cd66e09df5cb7b8cf3f443ea2b">Smallest</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the range that results from the union of this range with another range.</p>


<p>The resultant range is guaranteed to include the elements of both sets, but may contain more. For example, [3, 9) union [12,15) is [3, 15), which includes 9, 10, and 11, which were not included in either set before.</p>


<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="#aabb018856949929729145bb2488154fb">exactIntersectWith</a>, <a href="#a104cf3ac04ba840d0bd3b37685d6cdbe">exactUnionWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5193c3535375c450b9430e5671cbeb2d">llvm::getConstantRangeFromMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="#aa160a2ac0c31b48c41da949e53cc21b7">sdiv</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4af4fe6392d3860167eafedc817ed8b1">llvm::Constant::toConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#ac485f1a06d95a982f897655933212766">tryMergeRange</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a> and <a href="#aa81521f99442a5c30f9061b8c6ce795e">unionWith</a>.</p>

</div>
</div>

### unsignedAddMayOverflow() {#a2bf71829dbcdadbd24d3c22814113ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::OverflowResult ConstantRange::unsignedAddMayOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether unsigned add of the two ranges always/never overflows.</p>

<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2137 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">AlwaysOverflowsHigh</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">MayOverflow</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">NeverOverflows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fabe65a8d4b9b26a17c87317461c58">llvm::computeOverflowForUnsignedAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac8a8f784b3b05320fec4c962f5b4505b">llvm::SelectionDAG::computeOverflowForUnsignedAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>.</p>

</div>
</div>

### unsignedMulMayOverflow() {#a8ccba85d5176205f41ad55236b7d8204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::OverflowResult ConstantRange::unsignedMulMayOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether unsigned mul of the two ranges always/never overflows.</p>

<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2229 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">AlwaysOverflowsHigh</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">MayOverflow</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">NeverOverflows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a028f4d1eead63cc33499ce3459bd27c7">llvm::APInt::umul_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a62fdc50378ed0e117f3c4e829f9d68a8">llvm::computeOverflowForUnsignedMul</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bfd8086af1847cd50b68e00c568afec">llvm::SelectionDAG::computeOverflowForUnsignedMul</a>.</p>

</div>
</div>

### unsignedSubMayOverflow() {#a24a99adda34abba8c6988f8292a93815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange::OverflowResult ConstantRange::unsignedSubMayOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether unsigned sub of the two ranges always/never overflows.</p>

<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 2183 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1">AlwaysOverflowsLow</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">MayOverflow</a>, <a href="#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">NeverOverflows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0a06d2b63c0c0042fceb0e7e5bd64304">llvm::SelectionDAG::computeOverflowForUnsignedSub</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adc129334a6d3d83eb003dd1a49540f80">llvm::CombinerHelper::matchSuboCarryOut</a>.</p>

</div>
</div>

### urem() {#a336e2050c47c9d72b2cb4b13726fbba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::urem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range representing the possible values resulting from an unsigned remainder operation of a value in this range and a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#a1d705f2b7894d43bae1ff46eaf600181">getSingleElement</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>.</p>


<p>Referenced by <a href="#ae23c0a0a029dcfece9ccade74a1e1536">binaryOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a61e3236cbe0cbc94e306beb52ae1093d">canScalarizeAccess</a>.</p>

</div>
</div>

### ushl\_sat() {#a554ba11140af2b294a7e46761dfa7865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::ushl_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform an unsigned saturating left shift of this constant range by a value in <span class="doxyComputerOutput">Other</span>.</p>

<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1915 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a9458a57a572f29dd261a3be65cd8ee9f">llvm::APInt::ushl_sat</a>.</p>

</div>
</div>

### usub\_sat() {#a7a13c7e552038eb1d567e1572d91c411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::usub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform an unsigned saturating subtraction of two constant ranges.</p>

<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1867 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a059dc64e71df065315050d2270cbfba5">llvm::APInt::usub_sat</a>.</p>


<p>Referenced by <a href="#a8e5ef756d3fd31508cb35427065209c7">subWithNoWrap</a>.</p>

</div>
</div>

### zeroExtend() {#a636ddf018d314a1d73f98e2fa4efbafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::zeroExtend (uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new range in the specified integer type, which must be strictly larger than the current type.</p>


<p>The returned range will correspond to the possible range of values if the source range had been zero extended to BitWidth.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a4f6242fab5145c424cee29230fefe746">isFullSet</a>, <a href="#aa1a0c35225268e93dc3afd67e079f826">isUpperWrapped</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a> and <a href="#a05ef50c1573b919a575fccb31cc523b4">zextOrTrunc</a>.</p>

</div>
</div>

### zextOrTrunc() {#a05ef50c1573b919a575fccb31cc523b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::zextOrTrunc (uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this range have the bit width given by <span class="doxyComputerOutput">BitWidth</span>.</p>


<p>The value is zero extended, truncated, or left alone to make it that width.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a2bc441c8fe8dfeea5471f11d2d823ec1">truncate</a> and <a href="#a636ddf018d314a1d73f98e2fa4efbafb">zeroExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getEmpty() {#aa3303a9b527e663fedb07bb1a01c6414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRange::getEmpty ()</td>
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

<p>Create empty constant range with same bitwidth.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

### getFull() {#a0a065ec1c29537924087dde980463d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRange::getFull ()</td>
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

<p>Create full constant range with same bitwidth.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Lower {#a62ee547501b471ca645626351803c3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ConstantRange::Lower</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

### Upper {#ac4394049a395030d4dc367a1c81d741e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ConstantRange::Upper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### areInsensitiveToSignednessOfICmpPredicate() {#acbd3b47b716de422bfaee19a11427884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::areInsensitiveToSignednessOfICmpPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR2)</td>
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

<p>Return true iff CR1 ult CR2 is equivalent to CR1 slt CR2.</p>


<p>Does not depend on strictness/direction of the predicate.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>, <a href="#a99a9706be916441a29cd5b93b64f033b">isAllNonNegative</a> and <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>.</p>


<p>Referenced by <a href="#a1ca4520a4894a14c70f390091ee8d05d">getEquivalentPredWithFlippedSignedness</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a07a60b31e062be9b0c0b3532f41c99ad">processICmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>.</p>

</div>
</div>

### areInsensitiveToSignednessOfInvertedICmpPredicate() {#aaf85420850c216451bd6dcfe857bca32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::areInsensitiveToSignednessOfInvertedICmpPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR2)</td>
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

<p>Return true iff CR1 ult CR2 is equivalent to CR1 sge CR2.</p>


<p>Does not depend on strictness/direction of the predicate.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#a256a302a20f8f9c2c02c9ca2d41ea78e">isAllNegative</a>, <a href="#a99a9706be916441a29cd5b93b64f033b">isAllNonNegative</a> and <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>.</p>


<p>Referenced by <a href="#a1ca4520a4894a14c70f390091ee8d05d">getEquivalentPredWithFlippedSignedness</a>.</p>

</div>
</div>

### fromKnownBits() {#a211874a1535ba321cab61942cde9398f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::fromKnownBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, bool IsSigned)</td>
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

<p>Initialize a range based on a known bits constraint.</p>


<p>The IsSigned flag indicates whether the constant range should not wrap in the signed or unsigned domain.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a825476b2436eb817b735fdd34ee521c4">llvm::KnownBits::getMaxValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9b35c622a902a7a7dc93b807a9fa9265">llvm::KnownBits::getMinValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a44875c6f48f6c843cf3114a19280b5ca">llvm::KnownBits::hasConflict</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a>.</p>


<p>Referenced by <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a1f9b8b85cda6501eec16b6804b22c8c1">binaryXor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0eb8e591794bfc8e474a0a68c1135b0">llvm::computeConstantRangeIncludingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad682eaa6ebe25c01cdd86c1456fbeacf">llvm::SelectionDAG::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac8a8f784b3b05320fec4c962f5b4505b">llvm::SelectionDAG::computeOverflowForUnsignedAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62fdc50378ed0e117f3c4e829f9d68a8">llvm::computeOverflowForUnsignedMul</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bfd8086af1847cd50b68e00c568afec">llvm::SelectionDAG::computeOverflowForUnsignedMul</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0a06d2b63c0c0042fceb0e7e5bd64304">llvm::SelectionDAG::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebfb90f3ee1b2d4d5637e74d012424af">llvm::SelectionDAG::getValidShiftAmountRange</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adc129334a6d3d83eb003dd1a49540f80">llvm::CombinerHelper::matchSuboCarryOut</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>.</p>

</div>
</div>

### getEmpty() {#aff6f6c6a6df94af8be1bd5accff28a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRange::getEmpty (uint32_t BitWidth)</td>
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

<p>Create empty constant range with the given bit width.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>.</p>

</div>
</div>

### getEquivalentPredWithFlippedSignedness() {#a1ca4520a4894a14c70f390091ee8d05d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate ConstantRange::getEquivalentPredWithFlippedSignedness (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR2)</td>
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

<p>If the comparison between constant ranges this and Other is insensitive to the signedness of the comparison predicate, return a predicate equivalent to <span class="doxyComputerOutput">Pred</span>, with flipped signedness (i.e.</p>


<p>unsigned instead of signed or vice versa), and maybe inverted, otherwise returns <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">CmpInst::Predicate::BAD_ICMP_PREDICATE</a>.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#acbd3b47b716de422bfaee19a11427884">areInsensitiveToSignednessOfICmpPredicate</a>, <a href="#aaf85420850c216451bd6dcfe857bca32">areInsensitiveToSignednessOfInvertedICmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a972c176c0737e91145863040aef6cbd9">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a98ecd87b7ee2e36f02e7ea0b366fd92c">llvm::CmpInst::isRelational</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a07a60b31e062be9b0c0b3532f41c99ad">processICmp</a>.</p>

</div>
</div>

### getFull() {#a20bc7c6f540132189d07ad7f73bda1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRange::getFull (uint32_t BitWidth)</td>
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

<p>Create full constant range with the given bit width.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>.</p>

</div>
</div>

### getNonEmpty() {#acd8afecbb15ee69487d5339371f64a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRange::getNonEmpty (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Lower, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Upper)</td>
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

<p>Create non-empty constant range with the given bounds.</p>


<p>If Lower and Upper are the same, a full range is returned.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>.</p>


<p>Reference <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>.</p>


<p>Referenced by <a href="#a6c8069837b71990713a285cb590a0eb2">abs</a>, <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="#aac5f27f8d0ff473183fff55780e5796c">binaryAnd</a>, <a href="#ae3a906a72244158de8ae4a764e861d79">binaryOr</a>, <a href="#a4c3a3d6e30e1512fd3b160cae4025f26">castOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a>, <a href="#aea93f76a9c663074d87afbac598f5590">ctlz</a>, <a href="#acde7e3c58a91a9ba77071d8a84626184">ctpop</a>, <a href="#acc1e6bafefba3a5989e135575377032d">cttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a574647158b42f4d85c9f57f1a474452b">getRangeForSelectPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa69e07fa7ca7953d971574873d5ec5c2">makeExactMulNSWRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a7e7e5e776b7f30a4522e2d415efe1dfb">makeExactMulNUWRegion</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a>, <a href="#acac5641e821739845b8c56fa071f44ca">makeMaskNotEqualRange</a>, <a href="#af8daf8a07b3ab8645d4a6524caf57e7b">multiplyWithNoWrap</a>, <a href="#a54097522b509c08dd84e5ce59437c8b9">sadd_sat</a>, <a href="#a62222502f5be2dd8e300b48469aeab4f">shl</a>, <a href="#ae0d25c37392410b0b31e43feae19489c">smax</a>, <a href="#ad14e808f6eb7296b587b22cc49919da7">smin</a>, <a href="#a3a4758c17c35cfcd1f67a4a119a95ee0">smul_fast</a>, <a href="#a5c68869b0c18ead32284ec3b461bcbf7">smul_sat</a>, <a href="#a36128583fce0d74508c8dc73e56ee905">sshl_sat</a>, <a href="#a993a75b630274a45cb0c20938962796f">ssub_sat</a>, <a href="#a81da9170db4b7b8f89c9d196c07a6efb">uadd_sat</a>, <a href="#ad41d307fed42f6776d36397336e81985">udiv</a>, <a href="#a99d98815d214fb4c80537873777e91fb">umax</a>, <a href="#a4cabbd29371bbe4737500f0bf60774fd">umin</a>, <a href="#a19eb872c58979381c922e31a1344e0f0">umul_sat</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a7ddee2fbb9f51592ab6c0a93bd1b7325">unionWithMinMaxIntrinsicClamp</a>, <a href="#a336e2050c47c9d72b2cb4b13726fbba3">urem</a>, <a href="#a554ba11140af2b294a7e46761dfa7865">ushl_sat</a> and <a href="#a7a13c7e552038eb1d567e1572d91c411">usub_sat</a>.</p>

</div>
</div>

### intrinsic() {#a5959d13e50c78592ca89a8a964fb510c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::intrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; Ops)</td>
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

<p>Compute range of intrinsic result for the given operand ranges.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="#a6fb096a8dd6c61e17e87bc9f86db91ec">isIntrinsicSupported</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isIntrinsicSupported() {#a6fb096a8dd6c61e17e87bc9f86db91ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRange::isIntrinsicSupported (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID)</td>
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

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> calculations are supported for intrinsic with <span class="doxyComputerOutput">IntrinsicID</span>.</p>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>Referenced by <a href="#a5959d13e50c78592ca89a8a964fb510c">intrinsic</a>.</p>

</div>
</div>

### makeAllowedICmpRegion() {#aa0830ec6778859b4abb3e8bf0b9e0e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeAllowedICmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
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

<p>Produce the smallest range such that all values that may satisfy the given predicate with any value contained within Other is contained in the returned range.</p>


<p>Formally, this returns a superset of 'union over all y in Other . { x : icmp op x y is true }'. If the exact answer is not representable as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, the return value will be a proper superset of the above.</p>


<p>Example: Pred = ult and Other = i8 [2, 5) returns Result = [0, 4)</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ad7f81241f958a1f5917a3410942d3199">getBitWidth</a>, <a href="#a23f4339e49343721146062b10c144052">getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="#ac45b1557ea43684a07058cb74396c435">getSignedMax</a>, <a href="#a6c03477d3ea04e382431f02a0f21aa41">getSignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="#a4d69e164b5fb0f73a15a07119c4302f7">getUnsignedMin</a>, <a href="#aa1955c426e1ff66455b4bb6657ee995d">getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="#a91cf2c952ea87d701fe608fe4aaabfe4">isSingleElement</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4f30233ac0c825f0a38b55470569d7b7">isImpliedCondCommonOperandWithCR</a>, <a href="#aa89e9cec92a0b38d2f47a077bf12cc98">makeExactICmpRegion</a> and <a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">makeSatisfyingICmpRegion</a>.</p>

</div>
</div>

### makeExactICmpRegion() {#aa89e9cec92a0b38d2f47a077bf12cc98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeExactICmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Other)</td>
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

<p>Produce the exact range such that all values in the returned range satisfy the given predicate with any value contained within Other.</p>


<p>Formally, this returns the exact answer when the superset of 'union over all y in Other is exactly same as the subset of intersection over all y in Other. { x : icmp op x y is true}'.</p>


<p>Example: Pred = ult and Other = i8 3 returns [0, 3)</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a> and <a href="#a6fbc74ae7d3a1a1423c26b9ce948f34c">makeSatisfyingICmpRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#acd47afc26efebd49949d38018cfc29ce">cmpExcludesZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="#a81dc31883e0cc431912d8744c6cf9172">getEquivalentICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9298a379e311818b5244bcb6b386953b">llvm::isKnownInversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a002b7ea3a854166ae7ffe9d0e3e994d7">simplifySwitchOnSelectUsingRanges</a>.</p>

</div>
</div>

### makeExactNoWrapRegion() {#aeddb6f4f9ffcb9e893e5cb321b7a7f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeExactNoWrapRegion (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> BinOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Other, unsigned NoWrapKind)</td>
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

<p>Produce the range that contains X if and only if "X BinOp Other" does not wrap.</p>

<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#ace208c0bd1d845fe49f319be6a954764">makeGuaranteedNoWrapRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>.</p>

</div>
</div>

### makeGuaranteedNoWrapRegion() {#ace208c0bd1d845fe49f319be6a954764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeGuaranteedNoWrapRegion (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> BinOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other, unsigned NoWrapKind)</td>
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

<p>Produce the largest range containing all X such that "X BinOp Y" is guaranteed not to wrap (overflow) for <em>all</em> Y in Other.</p>


<p>However, there may be <em>some</em> Y in Other for which additional X not contained in the result also do not overflow.</p>


<p>NoWrapKind must be one of OBO::NoUnsignedWrap or OBO::NoSignedWrap.</p>


<p>Examples: typedef <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator">OverflowingBinaryOperator</a> OBO; #define MGNR makeGuaranteedNoWrapRegion MGNR(Add, [i8 1, 2), OBO::NoSignedWrap) == [-128, 127) MGNR(Add, [i8 1, 2), OBO::NoUnsignedWrap) == [0, -1) MGNR(Add, [i8 0, 1), OBO::NoUnsignedWrap) == Full Set MGNR(Add, [i8 -1, 6), OBO::NoSignedWrap) == [INT_MIN+1, INT_MAX-4) MGNR(Sub, [i8 1, 2), OBO::NoSignedWrap) == [-127, 128) MGNR(Sub, [i8 1, 2), OBO::NoUnsignedWrap) == [1, 0)</p>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#aabcad8746eb26dcbb5831974e39a3d34">ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#ab7f67c2ed8b2799c64ec64ca31d75c60">getUnsignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#ac098fe4f07549fb029fbf950dbe78fd3">intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="#a5bd6d98b4a7ecc1dcdc571e4352fcc52">isEmptySet</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a452f6ecfc69e273b9005e5bac75583a3">lshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa69e07fa7ca7953d971574873d5ec5c2">makeExactMulNSWRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a7e7e5e776b7f30a4522e2d415efe1dfb">makeExactMulNUWRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a> and <a href="#a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc">Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="#aeddb6f4f9ffcb9e893e5cb321b7a7f83">makeExactNoWrapRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a7003e88a45464bf7190910b8a8de6778">processBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a52da671999cb61370bfe5c7e9fee966f">willNotOverflow</a>.</p>

</div>
</div>

### makeMaskNotEqualRange() {#acac5641e821739845b8c56fa071f44ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeMaskNotEqualRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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

<p>Initialize a range containing all values X that satisfy <span class="doxyComputerOutput">(X &amp; Mask) != C</span>.</p>


<p>Note that the range returned may contain values where <span class="doxyComputerOutput">(X &amp; Mask) == C</span> holds, making it less precise, but still conservative.</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="#acd8afecbb15ee69487d5339371f64a76">getNonEmpty</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>.</p>

</div>
</div>

### makeSatisfyingICmpRegion() {#a6fbc74ae7d3a1a1423c26b9ce948f34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ConstantRange::makeSatisfyingICmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Other)</td>
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

<p>Produce the largest range such that all values in the returned range satisfy the given predicate with all values contained within Other.</p>


<p>Formally, this returns a subset of 'intersection over all y in Other . { x : icmp op x y is true }'. If the exact answer is not representable as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, the return value will be a proper subset of the above.</p>


<p>Example: Pred = ult and Other = i8 [2, 5) returns [0, 2)</p>


<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="#a8cbe37c4ba99ff3bc99338fcc618c618">ConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="#aaaa2f5e2c6c3122d2b484f9e50950e18">inverse</a> and <a href="#aa0830ec6778859b4abb3e8bf0b9e0e38">makeAllowedICmpRegion</a>.</p>


<p>Referenced by <a href="#aa89e9cec92a0b38d2f47a077bf12cc98">makeExactICmpRegion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">ConstantRange.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
