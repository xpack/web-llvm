---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/branchprobability
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BranchProbability` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BranchProbability { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cced3fc387efabab37f57c72dff55bb">BranchProbability</a> (uint32_t Numerator, uint32_t Denominator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fa4d22f4f3987e48e6983f4d801896">BranchProbability</a> (uint32_t n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e1a82b39c103faeced84dc3de736f6">operator+=</a> (BranchProbability RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1463e0c8643f481d2c8158c0ace96cdf">operator-=</a> (BranchProbability RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8bee392d69abd18bac99867a570e8b">operator*=</a> (BranchProbability RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60ef7cf50b201231701c122be931c67">operator*=</a> (uint32_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418a83ffa9c17348865fbefa264f88d4">operator/=</a> (BranchProbability RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e5a3c5d18658a1e4397593678a2ec6">operator/=</a> (uint32_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ce378239ac7fd9f63685f17cf52b82">operator+</a> (BranchProbability RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0886e38c8a6690d5a2de6f159343852d">operator-</a> (BranchProbability RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c947fb78e9cb68aa336687539c59693">operator*</a> (BranchProbability RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f7013d2799166f50f8b18b50513620">operator*</a> (uint32_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788cb824f3e8b80d54f2a4a97a5c4df9">operator/</a> (BranchProbability RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0d93a6bf572d467c79e3c4d26a63af">operator/</a> (uint32_t RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307ce06b3e2e77cdb2698675c80ffd77">operator==</a> (BranchProbability RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208ee14727510bf3bcf09f73a076e645">operator!=</a> (BranchProbability RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b580f734210a95178613b943f9bcc74">operator&lt;</a> (BranchProbability RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff558ac09c0ee9ad718ed7c1a36313f6">operator&gt;</a> (BranchProbability RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5620d1179145f77dd486d2609af6f2ad">operator&lt;=</a> (BranchProbability RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c3b4bb3fde0dfd53746e0ba3ec665a">operator&gt;=</a> (BranchProbability RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6abbd0248d2ceaacdc70448659c0c2f4">isZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f41716b68c197b7cd7582d7a66201a3">isUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be5759bf75c903d1695fa97eca6f139">getNumerator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee6034264d5d0782e5d1489360730d9">getCompl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573e850da9a3c2a2ee7ef1224ad717c2">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00519c57242e5e3b84f82ffc21c7f75a">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ccfc22b308af94572ad6843ecc21055">scale</a> (uint64_t Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale a large integer. <a href="#a9ccfc22b308af94572ad6843ecc21055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654bfa34e440912fecad8a6bd989d992">scaleByInverse</a> (uint64_t Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale a large integer by the inverse. <a href="#a654bfa34e440912fecad8a6bd989d992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82943aa9ae45e4dcb2202981308ce77f">N</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd00958cba7080048a84cccfcef55d71">getZero</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e1b2d1999aadf4c513caee1ce5275b">getOne</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e4454abb329dee28e8f525ddd1a210">getUnknown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286629cb3167717b736d06f88c8f4817">getRaw</a> (uint32_t N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0333345669e75a54c7de3d5fe0f6e746">getBranchProbability</a> (uint64_t Numerator, uint64_t Denominator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ProbabilityIter&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afff2bab6bb7f206bbacad5dd589a6186">normalizeProbabilities</a> (ProbabilityIter Begin, ProbabilityIter End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c752227e02f7cb26fb47fdb36dc349">getDenominator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cfdb77d4fc24f5bf2d57b11c7e74ea6">D</a> = 1u &lt;&lt; 31</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d4f9d353b924678590dcda2cb0e2ab">UnknownN</a> = UINT32_MAX</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BranchProbability() {#a9f95570835c021da093ddad5204192ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbability::BranchProbability ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Referenced by <a href="#a0333345669e75a54c7de3d5fe0f6e746">getBranchProbability</a>, <a href="#aaee6034264d5d0782e5d1489360730d9">getCompl</a>, <a href="#a56e1b2d1999aadf4c513caee1ce5275b">getOne</a>, <a href="#a286629cb3167717b736d06f88c8f4817">getRaw</a>, <a href="#a76e4454abb329dee28e8f525ddd1a210">getUnknown</a> and <a href="#afd00958cba7080048a84cccfcef55d71">getZero</a>.</p>

</div>
</div>

### BranchProbability() {#a8cced3fc387efabab37f57c72dff55bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability::BranchProbability (uint32_t Numerator, uint32_t Denominator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BranchProbability() {#ab0fa4d22f4f3987e48e6983f4d801896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbability::BranchProbability (uint32_t n)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#a0886e38c8a6690d5a2de6f159343852d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator- (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator-=() {#a1463e0c8643f481d2c8158c0ace96cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator-= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#a208ee14727510bf3bcf09f73a076e645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator!= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#a6c947fb78e9cb68aa336687539c59693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator* (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#aa5f7013d2799166f50f8b18b50513620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator* (uint32_t RHS)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*=() {#a5f8bee392d69abd18bac99867a570e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator*= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*=() {#aa60ef7cf50b201231701c122be931c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator*= (uint32_t RHS)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/() {#a788cb824f3e8b80d54f2a4a97a5c4df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator/ (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/() {#a3b0d93a6bf572d467c79e3c4d26a63af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator/ (uint32_t RHS)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/=() {#a418a83ffa9c17348865fbefa264f88d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator/= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/=() {#ae7e5a3c5d18658a1e4397593678a2ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator/= (uint32_t RHS)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+() {#aa0ce378239ac7fd9f63685f17cf52b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::operator+ (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+=() {#ab6e1a82b39c103faeced84dc3de736f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability &amp; llvm::BranchProbability::operator+= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a1b580f734210a95178613b943f9bcc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#a5620d1179145f77dd486d2609af6f2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator&lt;= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a307ce06b3e2e77cdb2698675c80ffd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator== (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#aff558ac09c0ee9ad718ed7c1a36313f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator&gt; (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#aa2c3b4bb3fde0dfd53746e0ba3ec665a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::operator&gt;= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RHS)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a00519c57242e5e3b84f82ffc21c7f75a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void BranchProbability::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a573e850da9a3c2a2ee7ef1224ad717c2">print</a>.</p>

</div>
</div>

### getCompl() {#aaee6034264d5d0782e5d1489360730d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::getCompl ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a4e4a47209688ad8c4359d4bf0f020f14">llvm::BranchProbabilityInfo::getBranchProbStackProtector</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b272a39b33a4e8ab2ac4acb2e64d583">llvm::ARMBaseInstrInfo::isProfitableToIfCvt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>.</p>

</div>
</div>

### getNumerator() {#a7be5759bf75c903d1695fa97eca6f139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BranchProbability::getNumerator ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a0a894de03271c0ccc991e40f4cdd2623">getAdjustedProbability</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1618f47bea0cb600291c8fb627eede51">llvm::getWeightFromBranchProb</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>.</p>

</div>
</div>

### isUnknown() {#a7f41716b68c197b7cd7582d7a66201a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::isUnknown ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Referenced by <a href="#afff2bab6bb7f206bbacad5dd589a6186">normalizeProbabilities</a>, <a href="#a573e850da9a3c2a2ee7ef1224ad717c2">print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6171d209616c58347dea44a49d7675c0">llvm::MachineBasicBlock::setSuccProbability</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### isZero() {#a6abbd0248d2ceaacdc70448659c0c2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchProbability::isZero ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>

</div>
</div>

### print() {#a573e850da9a3c2a2ee7ef1224ad717c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; BranchProbability::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a7f41716b68c197b7cd7582d7a66201a3">isUnknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faadaaee4b22041c27198d410c68d952c9">llvm::Percent</a>.</p>


<p>Referenced by <a href="#a00519c57242e5e3b84f82ffc21c7f75a">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa0b471b69b1f762e87641ee38dd57da6">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### scale() {#a9ccfc22b308af94572ad6843ecc21055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t BranchProbability::scale (uint64_t Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scale a large integer.</p>


<p>Scales <span class="doxyComputerOutput">Num</span>. Guarantees full precision. Returns the floor of the result.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Num</span> times <span class="doxyComputerOutput">this</span>.</p></dd>
</dl>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b272a39b33a4e8ab2ac4acb2e64d583">llvm::ARMBaseInstrInfo::isProfitableToIfCvt</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#af3d21db88053efddb1fab40325f88fe3">llvm::BlockFrequency::operator*=</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a>.</p>

</div>
</div>

### scaleByInverse() {#a654bfa34e440912fecad8a6bd989d992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t BranchProbability::scaleByInverse (uint64_t Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scale a large integer by the inverse.</p>


<p>Scales <span class="doxyComputerOutput">Num</span> by the inverse of <span class="doxyComputerOutput">this</span>. Guarantees full precision. Returns the floor of the result.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Num</span> divided by <span class="doxyComputerOutput">this</span>.</p></dd>
</dl>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#af724ffc512f3dc4374e71297186cf191">llvm::BlockFrequency::operator/=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### N {#a82943aa9ae45e4dcb2202981308ce77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BranchProbability::N</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBranchProbability() {#a0333345669e75a54c7de3d5fe0f6e746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability BranchProbability::getBranchProbability (uint64_t Numerator, uint64_t Denominator)</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aa5755510005963e0d33f000914c5489d">anonymous{HotColdSplitting.cpp}::analyzeProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#afb9349865f6045be3029d7d171f23f4e">extractBranchProbabilities</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#ae1d4736e8dfc615fad673c393a757127">getCHRBiasThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a1c78d4d6544b97f0fb4219ec8a99c54b">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a4bde686b6506cc9e63919272711713f4">isFormingBranchFromSelectProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a08cd264874d8deee9a2bdda9b9461e29">isProfitableToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/misexpect/#a8677c5d2618fcf52eda43f5530decb6b">llvm::misexpect::verifyMisExpect</a>.</p>

</div>
</div>

### getDenominator() {#a19c752227e02f7cb26fb47fdb36dc349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BranchProbability::getDenominator ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getEdgeAttributes</a>, <a href="#afff2bab6bb7f206bbacad5dd589a6186">normalizeProbabilities</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a145edc209aa2f628c73c9cf860eeeb5c">llvm::BranchProbabilityInfo::setEdgeProbability</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6f0fb45670739e2756c1e41ce22c457b">llvm::MachineBasicBlock::validateSuccProbs</a>.</p>

</div>
</div>

### getOne() {#a56e1b2d1999aadf4c513caee1ce5275b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::getOne ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a0a894de03271c0ccc991e40f4cdd2623">getAdjustedProbability</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a>.</p>

</div>
</div>

### getRaw() {#a286629cb3167717b736d06f88c8f4817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::getRaw (uint32_t N)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#afff2bab6bb7f206bbacad5dd589a6186">normalizeProbabilities</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ace3ad3f99a9b90046e398bc0c09d372b">anonymous{MIParser.cpp}::MIParser::parseBasicBlockSuccessors</a>.</p>

</div>
</div>

### getUnknown() {#a76e4454abb329dee28e8f525ddd1a210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::getUnknown ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/sdagswitchlowering/#ae0cd053e514114e2e727249dd983d61c">llvm::SelectionDAGBuilder::SDAGSwitchLowering::addSuccessorWithProb</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ab4222a54657e712a02c19875dd7e0d60">llvm::SwitchCG::SwitchLowering::addSuccessorWithProb</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#afb1a861a3ca73c38d41341e5630d7206">llvm::SwitchCG::CaseBlock::CaseBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a6ab842e01d79a0e6b95068c03625ae61">llvm::SwitchCG::CaseBlock::CaseBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4b43b969b3db9fc943b664738f62ca76">llvm::MachineBasicBlock::splitSuccessor</a>.</p>

</div>
</div>

### getZero() {#afd00958cba7080048a84cccfcef55d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbability::getZero ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>Reference <a href="#a9f95570835c021da093ddad5204192ca">BranchProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreemitpeephole-cpp-/branchweightcostmodel/#aa842d0e2dfc3a19e513d9098c7e4d00e">anonymous{SIPreEmitPeephole.cpp}::BranchWeightCostModel::BranchWeightCostModel</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a8b76388f3768d895c2c1029d3356481a">llvm::BranchProbabilityInfo::getEdgeProbability</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a34b15764a81fb89e68d85d5aae76f20f">llvm::MachineBasicBlock::getSuccProbability</a>, <a href="#afff2bab6bb7f206bbacad5dd589a6186">normalizeProbabilities</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a64747c8e3007c455b9b9a66a50a176e3">scaleCaseProbality</a>.</p>

</div>
</div>

### normalizeProbabilities() {#afff2bab6bb7f206bbacad5dd589a6186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ProbabilityIter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BranchProbability::normalizeProbabilities (ProbabilityIter Begin, ProbabilityIter End)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>


<p>References <a href="#a19c752227e02f7cb26fb47fdb36dc349">getDenominator</a>, <a href="#a286629cb3167717b736d06f88c8f4817">getRaw</a>, <a href="#afd00958cba7080048a84cccfcef55d71">getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7f41716b68c197b7cd7582d7a66201a3">isUnknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### D {#a0cfdb77d4fc24f5bf2d57b11c7e74ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t BranchProbability::D = 1u &lt;&lt; 31</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>

</div>
</div>

### UnknownN {#a89d4f9d353b924678590dcda2cb0e2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BranchProbability::UnknownN = UINT32_MAX</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">BranchProbability.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp">BranchProbability.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
