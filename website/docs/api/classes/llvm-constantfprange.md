---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantfprange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantFPRange` Class

<p>This class represents a range of floating-point values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantFPRange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">llvm/IR/ConstantFPRange.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e299dcf509675f0c5d61821c81341f">ConstantFPRange</a> (const APFloat &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range to hold the single specified value. <a href="#a82e299dcf509675f0c5d61821c81341f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7b8a013caf003e5249f15aeff08d02">ConstantFPRange</a> (APFloat LowerVal, APFloat UpperVal, bool MayBeQNaN, bool MayBeSNaN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a range of values explicitly. <a href="#a0b7b8a013caf003e5249f15aeff08d02">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad054180e33ab1432f5a4038696e912f9">ConstantFPRange</a> (const fltSemantics &amp;Sem, bool IsFullSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a full or empty set for the specified semantics. <a href="#ad054180e33ab1432f5a4038696e912f9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e320a920bce1bfd68f629dc199b5645">operator==</a> (const ConstantFPRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this range is equal to another range. <a href="#a4e320a920bce1bfd68f629dc199b5645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa358c3b1545898d0e7365f44e194963e">operator!=</a> (const ConstantFPRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this range is not equal to another range. <a href="#aa358c3b1545898d0e7365f44e194963e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc14102cffa124e404d220c3daafda35">fcmp</a> (FCmpInst::Predicate Pred, const ConstantFPRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the predicate <span class="doxyComputerOutput">Pred</span> hold between ranges this and <span class="doxyComputerOutput">Other</span>? <a href="#adc14102cffa124e404d220c3daafda35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf00eeae75d39bfd560934ea6657ce3">getLower</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the lower value for this range. <a href="#aecf00eeae75d39bfd560934ea6657ce3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1ef69f315dc2f8249e020780192e3d">getUpper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the upper value for this range. <a href="#aeb1ef69f315dc2f8249e020780192e3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9d74b728e4f62b126c17c6970957f4">containsNaN</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1280f3ee32c39f4732e88d94f62ba72d">containsQNaN</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c822545e0122b707c5953be7c06fef3">containsSNaN</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879a23c24f4a6ccd5e55e9fae566fd8b">isNaNOnly</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the semantics of this <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a>. <a href="#afda37fe68e3091ce813c4f9ab507a04d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f44a4da225767b6a2e09a0540acfc6">isFullSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains all of the elements possible for this data-type. <a href="#a08f44a4da225767b6a2e09a0540acfc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac2cfff79a0f2642ae873f066481281">isEmptySet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains no members. <a href="#a8ac2cfff79a0f2642ae873f066481281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc453b2dc648e45c35ae756cbe300cb8">contains</a> (const APFloat &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified value is in the set. <a href="#adc453b2dc648e45c35ae756cbe300cb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28af69a643d5ba066a7492b98e71c6bb">contains</a> (const ConstantFPRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the other range is a subset of this one. <a href="#a28af69a643d5ba066a7492b98e71c6bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c44f70a31ae4f69f7676b9499ba117b">getSingleElement</a> (bool ExcludesNaN=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this set contains a single element, return it, otherwise return null. <a href="#a4c44f70a31ae4f69f7676b9499ba117b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a320a2d76c93e6aa347f2456a7a394">isSingleElement</a> (bool ExcludesNaN=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set contains exactly one member. <a href="#a87a320a2d76c93e6aa347f2456a7a394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ffec8482d416f58cf0eb8bcb9d0b25">getSignBit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the sign bit of all values in this range is 1. <a href="#a82ffec8482d416f58cf0eb8bcb9d0b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde325f79b260d886caf545f2bd5c0f3">classify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> which will return true for the value. <a href="#acde325f79b260d886caf545f2bd5c0f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951fd858f0a01fc10c5556ac31075162">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out the bounds to a stream. <a href="#a951fd858f0a01fc10c5556ac31075162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf29fcc870f2cd3f5a5d8242ffc4d92">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow printing from a debugger easily. <a href="#abcf29fcc870f2cd3f5a5d8242ffc4d92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980922d17596d03dcc175b9fa44c44ad">intersectWith</a> (const ConstantFPRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range that results from the intersection of this range with another range. <a href="#a980922d17596d03dcc175b9fa44c44ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636a963e6815f27f903783209eddc2ac">unionWith</a> (const ConstantFPRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the smallest range that results from the union of this range with another range. <a href="#a636a963e6815f27f903783209eddc2ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a88452fb18822e942fc807578c55020">getEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create empty constant range with same semantics. <a href="#a5a88452fb18822e942fc807578c55020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbd9bc3ef606edbbf6c89c9fd6ff51b">getFull</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create full constant range with same semantics. <a href="#a6fbd9bc3ef606edbbf6c89c9fd6ff51b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d51200ee058dd3bc42ca21a0af858ba">makeEmpty</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6c3728027829fcbbf6679acbf861bc">makeFull</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0700a7b8ea680f70903f1ad4d4737d97">Lower</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2178d8caece076517d38dac1694b0544">Upper</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d40fb0a09b68fb5390b799b778b872">MayBeQNaN</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f90f4814ed38011115f2383348bbdfe">MayBeSNaN</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1dd0b6088a193eaccbb62d776d60587">getEmpty</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create empty constant range with the given semantics. <a href="#ad1dd0b6088a193eaccbb62d776d60587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106ff7aa37fa465de3aa36d5887b2ee5">getFull</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create full constant range with the given semantics. <a href="#a106ff7aa37fa465de3aa36d5887b2ee5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90400068a35c0781d02ecabdb296ddef">getFinite</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for (-inf, inf) to represent all finite values. <a href="#a90400068a35c0781d02ecabdb296ddef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340071757f3e0c6524e70a873212adee">getNonNaN</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for [-inf, inf] to represent all non-NaN values. <a href="#a340071757f3e0c6524e70a873212adee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36feb2aab4770cccf5b75fe7955d3c9">getNonNaN</a> (APFloat LowerVal, APFloat UpperVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a range which doesn't contain NaNs. <a href="#ad36feb2aab4770cccf5b75fe7955d3c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06367647f909e8107f3a1bc01dddf344">getMayBeNaN</a> (APFloat LowerVal, APFloat UpperVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a range which may contain NaNs. <a href="#a06367647f909e8107f3a1bc01dddf344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf82053f21c501b073d99bb18e73541">getNaNOnly</a> (const fltSemantics &amp;Sem, bool MayBeQNaN, bool MayBeSNaN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a range which only contains NaNs. <a href="#a5cf82053f21c501b073d99bb18e73541">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ec432d02febd1b518e9453b1a0eba9">makeAllowedFCmpRegion</a> (FCmpInst::Predicate Pred, const ConstantFPRange &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the smallest range such that all values that may satisfy the given predicate with any value contained within Other is contained in the returned range. <a href="#a84ec432d02febd1b518e9453b1a0eba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">makeSatisfyingFCmpRegion</a> (FCmpInst::Predicate Pred, const ConstantFPRange &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the largest range such that all values in the returned range satisfy the given predicate with all values contained within Other. <a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af161596390e6f77e1b0a90f42b938d98">makeExactFCmpRegion</a> (FCmpInst::Predicate Pred, const APFloat &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the exact range such that all values in the returned range satisfy the given predicate with any value contained within Other. <a href="#af161596390e6f77e1b0a90f42b938d98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents a range of floating-point values.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConstantFPRange() {#a82e299dcf509675f0c5d61821c81341f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange::ConstantFPRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Value)</td>
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

<p>Initialize a range to hold the single specified value.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a>.</p>

</div>
</div>

### ConstantFPRange() {#a0b7b8a013caf003e5249f15aeff08d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange::ConstantFPRange (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> LowerVal, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> UpperVal, bool MayBeQNaN, bool MayBeSNaN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a range of values explicitly.</p>


<p>Note: If <span class="doxyComputerOutput">LowerVal</span> is greater than <span class="doxyComputerOutput">UpperVal</span>, please use the canonical form [Inf, -Inf].</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#ae5f56c6dbd79483472793e618ad64f8a">isNonCanonicalEmptySet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantFPRange() {#ad054180e33ab1432f5a4038696e912f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange::ConstantFPRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool IsFullSet)</td>
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

<p>Initialize a full or empty set for the specified semantics.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aa358c3b1545898d0e7365f44e194963e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR)</td>
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

<p>Return true if this range is not equal to another range.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a>.</p>

</div>
</div>

### operator==() {#a4e320a920bce1bfd68f629dc199b5645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this range is equal to another range.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### classify() {#acde325f79b260d886caf545f2bd5c0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest ConstantFPRange::classify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> which will return true for the value.</p>

<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a> and <a href="#a879a23c24f4a6ccd5e55e9fae566fd8b">isNaNOnly</a>.</p>

</div>
</div>

### contains() {#adc453b2dc648e45c35ae756cbe300cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified value is in the set.</p>

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a833f6b183e2adebde0fb463e6a6297fe">llvm::APFloat::isSignaling</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a095c6a1883dc33dfe9e5ffba9613a3ec">strictCompare</a>.</p>


<p>Referenced by <a href="#adc14102cffa124e404d220c3daafda35">fcmp</a>.</p>

</div>
</div>

### contains() {#a28af69a643d5ba066a7492b98e71c6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the other range is a subset of this one.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a095c6a1883dc33dfe9e5ffba9613a3ec">strictCompare</a>.</p>

</div>
</div>

### containsNaN() {#a6f9d74b728e4f62b126c17c6970957f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::containsNaN ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### containsQNaN() {#a1280f3ee32c39f4732e88d94f62ba72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::containsQNaN ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>.</p>

</div>
</div>

### containsSNaN() {#a3c822545e0122b707c5953be7c06fef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::containsSNaN ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>.</p>

</div>
</div>

### dump() {#abcf29fcc870f2cd3f5a5d8242ffc4d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ConstantFPRange::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow printing from a debugger easily.</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a951fd858f0a01fc10c5556ac31075162">print</a>.</p>

</div>
</div>

### fcmp() {#adc14102cffa124e404d220c3daafda35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::fcmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">FCmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the predicate <span class="doxyComputerOutput">Pred</span> hold between ranges this and <span class="doxyComputerOutput">Other</span>?</p>


<p>NOTE: false does not mean that inverse predicate holds!</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="#adc453b2dc648e45c35ae756cbe300cb8">contains</a>, <a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">makeSatisfyingFCmpRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### getLower() {#aecf00eeae75d39bfd560934ea6657ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat &amp; llvm::ConstantFPRange::getLower ()</td>
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

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#affe0a2d80588accff7111123a015df68">setNaNField</a>.</p>

</div>
</div>

### getSemantics() {#afda37fe68e3091ce813c4f9ab507a04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::ConstantFPRange::getSemantics ()</td>
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

<p>Get the semantics of this <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a>.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Referenced by <a href="#a82e299dcf509675f0c5d61821c81341f">ConstantFPRange</a>, <a href="#adc453b2dc648e45c35ae756cbe300cb8">contains</a>, <a href="#a28af69a643d5ba066a7492b98e71c6bb">contains</a>, <a href="#a980922d17596d03dcc175b9fa44c44ad">intersectWith</a> and <a href="#a636a963e6815f27f903783209eddc2ac">unionWith</a>.</p>

</div>
</div>

### getSignBit() {#a82ffec8482d416f58cf0eb8bcb9d0b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; ConstantFPRange::getSignBit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the sign bit of all values in this range is 1.</p>


<p>Return false if the sign bit of all values in this range is 0. Otherwise, return std::nullopt.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>

</div>
</div>

### getSingleElement() {#a4c44f70a31ae4f69f7676b9499ba117b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat * ConstantFPRange::getSingleElement (bool ExcludesNaN=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this set contains a single element, return it, otherwise return null.</p>


<p>If <span class="doxyComputerOutput">ExcludesNaN</span> is true, return the non-NaN single element.</p>


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a28cbb0780286695406353e6a295e12c8">llvm::APFloat::bitwiseIsEqual</a>.</p>


<p>Referenced by <a href="#a87a320a2d76c93e6aa347f2456a7a394">isSingleElement</a>.</p>

</div>
</div>

### getUpper() {#aeb1ef69f315dc2f8249e020780192e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat &amp; llvm::ConstantFPRange::getUpper ()</td>
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

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#affe0a2d80588accff7111123a015df68">setNaNField</a>.</p>

</div>
</div>

### intersectWith() {#a980922d17596d03dcc175b9fa44c44ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::intersectWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the range that results from the intersection of this range with another range.</p>

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6e7cbf32894b4feb398e5ff39919ca1">canonicalizeRange</a>, <a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a636de400e4dd2bc090b729329a99e75b">llvm::maxnum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa656aa475d13ec6a900414eadabe86b0">llvm::minnum</a>.</p>

</div>
</div>

### isEmptySet() {#a8ac2cfff79a0f2642ae873f066481281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::isEmptySet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set contains no members.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Referenced by <a href="#a951fd858f0a01fc10c5556ac31075162">print</a>.</p>

</div>
</div>

### isFullSet() {#a08f44a4da225767b6a2e09a0540acfc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::isFullSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set contains all of the elements possible for this data-type.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Referenced by <a href="#a951fd858f0a01fc10c5556ac31075162">print</a>.</p>

</div>
</div>

### isNaNOnly() {#a879a23c24f4a6ccd5e55e9fae566fd8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantFPRange::isNaNOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Referenced by <a href="#acde325f79b260d886caf545f2bd5c0f3">classify</a> and <a href="#a951fd858f0a01fc10c5556ac31075162">print</a>.</p>

</div>
</div>

### isSingleElement() {#a87a320a2d76c93e6aa347f2456a7a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::isSingleElement (bool ExcludesNaN=false)</td>
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


<p>If <span class="doxyComputerOutput">ExcludesNaN</span> is true, return true if this set contains exactly one non-NaN member.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>


<p>Reference <a href="#a4c44f70a31ae4f69f7676b9499ba117b">getSingleElement</a>.</p>

</div>
</div>

### print() {#a951fd858f0a01fc10c5556ac31075162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantFPRange::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out the bounds to a stream.</p>

<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="#a8ac2cfff79a0f2642ae873f066481281">isEmptySet</a>, <a href="#a08f44a4da225767b6a2e09a0540acfc6">isFullSet</a> and <a href="#a879a23c24f4a6ccd5e55e9fae566fd8b">isNaNOnly</a>.</p>


<p>Referenced by <a href="#abcf29fcc870f2cd3f5a5d8242ffc4d92">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59a8a9e4861e3384ff4e3cc12e45ff60">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### unionWith() {#a636a963e6815f27f903783209eddc2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::unionWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the smallest range that results from the union of this range with another range.</p>


<p>The resultant range is guaranteed to include the elements of both sets, but may contain more.</p>


<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afda37fe68e3091ce813c4f9ab507a04d">getSemantics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a636de400e4dd2bc090b729329a99e75b">llvm::maxnum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa656aa475d13ec6a900414eadabe86b0">llvm::minnum</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getEmpty() {#a5a88452fb18822e942fc807578c55020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getEmpty ()</td>
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

<p>Create empty constant range with same semantics.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### getFull() {#a6fbd9bc3ef606edbbf6c89c9fd6ff51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getFull ()</td>
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

<p>Create full constant range with same semantics.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### makeEmpty() {#a1d51200ee058dd3bc42ca21a0af858ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantFPRange::makeEmpty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>

</div>
</div>

### makeFull() {#afc6c3728027829fcbbf6679acbf861bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantFPRange::makeFull ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Lower {#a0700a7b8ea680f70903f1ad4d4737d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::ConstantFPRange::Lower</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### MayBeQNaN {#a92d40fb0a09b68fb5390b799b778b872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::MayBeQNaN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### MayBeSNaN {#a1f90f4814ed38011115f2383348bbdfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantFPRange::MayBeSNaN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### Upper {#a2178d8caece076517d38dac1694b0544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::ConstantFPRange::Upper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmpty() {#ad1dd0b6088a193eaccbb62d776d60587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getEmpty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Create empty constant range with the given semantics.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### getFinite() {#a90400068a35c0781d02ecabdb296ddef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::getFinite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Helper for (-inf, inf) to represent all finite values.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aaa67fe0741c2b3712630ae636f8c2c20">llvm::APFloat::getLargest</a>.</p>

</div>
</div>

### getFull() {#a106ff7aa37fa465de3aa36d5887b2ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getFull (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Create full constant range with the given semantics.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### getMayBeNaN() {#a06367647f909e8107f3a1bc01dddf344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getMayBeNaN (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> LowerVal, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> UpperVal)</td>
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

<p>Create a range which may contain NaNs.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### getNaNOnly() {#a5cf82053f21c501b073d99bb18e73541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::getNaNOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool MayBeQNaN, bool MayBeSNaN)</td>
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

<p>Create a range which only contains NaNs.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>.</p>


<p>Referenced by <a href="#a84ec432d02febd1b518e9453b1a0eba9">makeAllowedFCmpRegion</a> and <a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### getNonNaN() {#a340071757f3e0c6524e70a873212adee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::getNonNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Helper for [-inf, inf] to represent all non-NaN values.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>.</p>


<p>Referenced by <a href="#a84ec432d02febd1b518e9453b1a0eba9">makeAllowedFCmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a> and <a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### getNonNaN() {#ad36feb2aab4770cccf5b75fe7955d3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange llvm::ConstantFPRange::getNonNaN (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> LowerVal, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> UpperVal)</td>
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

<p>Create a range which doesn't contain NaNs.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>.</p>

</div>
</div>

### makeAllowedFCmpRegion() {#a84ec432d02febd1b518e9453b1a0eba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::makeAllowedFCmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">FCmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; Other)</td>
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


<p>Formally, this returns a superset of 'union over all y in Other . { x : fcmp op x y is true }'. If the exact answer is not representable as a <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a>, the return value will be a proper superset of the above.</p>


<p>Example: Pred = ole and Other = float [2, 5] returns Result = [-inf, 5]</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aaa67fe0741c2b3712630ae636f8c2c20">llvm::APFloat::getLargest</a>, <a href="#a5cf82053f21c501b073d99bb18e73541">getNaNOnly</a>, <a href="#a340071757f3e0c6524e70a873212adee">getNonNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad91c80980a394e9c81f04e8988261224">llvm::CmpInst::isOrdered</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#affe0a2d80588accff7111123a015df68">setNaNField</a>.</p>

</div>
</div>

### makeExactFCmpRegion() {#af161596390e6f77e1b0a90f42b938d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantFPRange &gt; ConstantFPRange::makeExactFCmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">FCmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Other)</td>
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


<p>Formally, this returns { x : fcmp op x Other is true }.</p>


<p>Example: Pred = olt and Other = float 3 returns [-inf, 3) If the exact answer is not representable as a <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a>, returns std::nullopt.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">makeSatisfyingFCmpRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### makeSatisfyingFCmpRegion() {#a4c7a26e0bf4a7880f0ba8c3aa2d74a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange ConstantFPRange::makeSatisfyingFCmpRegion (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">FCmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; Other)</td>
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


<p>Formally, this returns a subset of 'intersection over all y in Other . { x : fcmp op x y is true }'. If the exact answer is not representable as a <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a>, the return value will be a proper subset of the above.</p>


<p>Example: Pred = ole and Other = float [2, 5] returns [-inf, 2]</p>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab6ede72b2b2219068b9bb89732d24e2f">llvm::fcZero</a>, <a href="#a5cf82053f21c501b073d99bb18e73541">getNaNOnly</a>, <a href="#a340071757f3e0c6524e70a873212adee">getNonNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad91c80980a394e9c81f04e8988261224">llvm::CmpInst::isOrdered</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#affe0a2d80588accff7111123a015df68">setNaNField</a>.</p>


<p>Referenced by <a href="#adc14102cffa124e404d220c3daafda35">fcmp</a> and <a href="#af161596390e6f77e1b0a90f42b938d98">makeExactFCmpRegion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">ConstantFPRange.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
