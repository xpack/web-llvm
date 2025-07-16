---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smalldensemap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SmallDenseMap` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;
class llvm::SmallDenseMap&lt;KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemapbase">DenseMapBase&lt;DerivedT, KeyT, ValueT, KeyInfoT, BucketT&gt;</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f08c2efa14610db50ff04ecbf8d8317">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemapbase">DenseMapBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>, KeyT, ValueT, KeyInfoT, BucketT &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac241c799f56a44594de5ce439d9c49be">DenseMapBase&lt; SmallDenseMap, KeyT, ValueT, KeyInfoT, BucketT &gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a64f107245b11e2918c3b5b7a9f7c8a6f">SmallDenseMap</a> (unsigned NumInitBuckets=0)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa988072d87544b16c3ebbfca14f57856">SmallDenseMap</a> (const SmallDenseMap &amp;other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a80cdbd0237ed5fc99eb7c9c44f0a9f36">SmallDenseMap</a> (SmallDenseMap &amp;&amp;other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InputIt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1514ee2d9a9a97a82c2880199bce977c">SmallDenseMap</a> (const InputIt &amp;I, const InputIt &amp;E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7114f0ad92f7b9d93661f0d78f858ea6">SmallDenseMap</a> (std::initializer_list&lt; typename BaseT::value_type &gt; Vals)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad1927967908660cbfa4a3b11963ca71a">~SmallDenseMap</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e7285b7376078e9c92c8caac40d77be">operator=</a> (const SmallDenseMap &amp;other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3071185bfe66e810a887924981593bd8">operator=</a> (SmallDenseMap &amp;&amp;other)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18123b9d53e5b40db36764d6d55c1fbe">swap</a> (SmallDenseMap &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab55ba787f43a50be2620fab61f6e7a1">copyFrom</a> (const SmallDenseMap &amp;other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b6b9b96500679d120ffcd367f58208e">init</a> (unsigned InitBuckets)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a035d1a4041d77c310aeb7e7ff4653f3a">grow</a> (unsigned AtLeast)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1fb19692a65ccb8fbbc98a39ccf73a5">shrink_and_clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af39a22626f2ebdc876465bc4543b4b33">getNumEntries</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9555518560af5334e27ccc9cda4ff950">setNumEntries</a> (unsigned Num)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e155d7dcca7f73d397b0c381209d8d8">getNumTombstones</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21ddec92351cd5cf8359b1afd935ce19">setNumTombstones</a> (unsigned Num)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BucketT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed177a48a0f756dd515d445301454336">getInlineBuckets</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BucketT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c268cc5a1afdccd19d08d7509feb1a1">getInlineBuckets</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LargeRep *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a578b992a731699a3f50f5b8d4650ee46">getLargeRep</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LargeRep *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ca351e3f10a8afc9689fffba55da3dc">getLargeRep</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BucketT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5d997aa8490c650b6b829ce790788c9">getBuckets</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BucketT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb1994c86fe55a560112d7a0fd816fdd">getBuckets</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29517da168297d4127fc48c1419a9086">getNumBuckets</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab95da94cf6224293451886ec52383f8d">deallocateBuckets</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LargeRep</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea70661e4509226c49369e9364bce11f">allocateBuckets</a> (unsigned Num)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add5bf20b632ce7eb776fb7804d2a8840">Small</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25c91ef16b028d09803731b90d92acee">NumEntries</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a979a01de81f9536e036bc2de7dfe4c31">NumTombstones</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/alignedchararrayunion">AlignedCharArrayUnion</a>&lt; BucketT[InlineBuckets], LargeRep &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a576add97f408ad453eec4aa17caf7129">storage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A "union" of an inline bucket array and the struct representing a large bucket. <a href="#a576add97f408ad453eec4aa17caf7129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a7f08c2efa14610db50ff04ecbf8d8317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::BaseT =  DenseMapBase&lt;SmallDenseMap, KeyT, ValueT, KeyInfoT, BucketT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapBase&lt; SmallDenseMap, KeyT, ValueT, KeyInfoT, BucketT &gt; {#ac241c799f56a44594de5ce439d9c49be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/densemapbase">DenseMapBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>, KeyT, ValueT, KeyInfoT, BucketT &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SmallDenseMap() {#a64f107245b11e2918c3b5b7a9f7c8a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::SmallDenseMap (unsigned NumInitBuckets=0)</td>
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



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### SmallDenseMap() {#aa988072d87544b16c3ebbfca14f57856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::SmallDenseMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp; other)</td>
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



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### SmallDenseMap() {#a80cdbd0237ed5fc99eb7c9c44f0a9f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::SmallDenseMap (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp;&amp; other)</td>
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



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### SmallDenseMap() {#a1514ee2d9a9a97a82c2880199bce977c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InputIt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::SmallDenseMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InputIt &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InputIt &amp; E)</td>
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



<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### SmallDenseMap() {#a7114f0ad92f7b9d93661f0d78f858ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::SmallDenseMap (std::initializer_list&lt; typename <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#ab3749c7aa991a9067aa4d209d0f9191f">BaseT::value_type</a> &gt; Vals)</td>
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



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SmallDenseMap() {#ad1927967908660cbfa4a3b11963ca71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::~SmallDenseMap ()</td>
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



<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a3e7285b7376078e9c92c8caac40d77be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap &amp; llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp; other)</td>
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



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### operator=() {#a3071185bfe66e810a887924981593bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap &amp; llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp;&amp; other)</td>
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



<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyFrom() {#aab55ba787f43a50be2620fab61f6e7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::copyFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp; other)</td>
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



<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### grow() {#a035d1a4041d77c310aeb7e7ff4653f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::grow (unsigned AtLeast)</td>
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



<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### init() {#a1b6b9b96500679d120ffcd367f58208e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::init (unsigned InitBuckets)</td>
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



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### shrink\_and\_clear() {#ae1fb19692a65ccb8fbbc98a39ccf73a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::shrink_and_clear ()</td>
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



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### swap() {#a18123b9d53e5b40db36764d6d55c1fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::swap (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a> &amp; RHS)</td>
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



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateBuckets() {#aea70661e4509226c49369e9364bce11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LargeRep llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::allocateBuckets (unsigned Num)</td>
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



<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### deallocateBuckets() {#ab95da94cf6224293451886ec52383f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::deallocateBuckets ()</td>
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



<p>Definition at line 1168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getBuckets() {#ab5d997aa8490c650b6b829ce790788c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BucketT * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getBuckets ()</td>
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



<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getBuckets() {#afb1994c86fe55a560112d7a0fd816fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BucketT * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getBuckets ()</td>
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



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getInlineBuckets() {#aed177a48a0f756dd515d445301454336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BucketT * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getInlineBuckets ()</td>
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



<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getInlineBuckets() {#a3c268cc5a1afdccd19d08d7509feb1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BucketT * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getInlineBuckets ()</td>
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



<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getLargeRep() {#a578b992a731699a3f50f5b8d4650ee46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LargeRep * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getLargeRep ()</td>
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



<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getLargeRep() {#a1ca351e3f10a8afc9689fffba55da3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LargeRep * llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getLargeRep ()</td>
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



<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getNumBuckets() {#a29517da168297d4127fc48c1419a9086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getNumBuckets ()</td>
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



<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getNumEntries() {#af39a22626f2ebdc876465bc4543b4b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getNumEntries ()</td>
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



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### getNumTombstones() {#a8e155d7dcca7f73d397b0c381209d8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::getNumTombstones ()</td>
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



<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### setNumEntries() {#a9555518560af5334e27ccc9cda4ff950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::setNumEntries (unsigned Num)</td>
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



<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### setNumTombstones() {#a21ddec92351cd5cf8359b1afd935ce19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::setNumTombstones (unsigned Num)</td>
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



<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumEntries {#a25c91ef16b028d09803731b90d92acee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::NumEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### NumTombstones {#a979a01de81f9536e036bc2de7dfe4c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::NumTombstones</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### Small {#add5bf20b632ce7eb776fb7804d2a8840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::Small</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

### storage {#a576add97f408ad453eec4aa17caf7129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, unsigned InlineBuckets = 4, typename KeyInfoT = DenseMapInfo&lt;KeyT&gt;, typename BucketT = llvm::detail::DenseMapPair&lt;KeyT, ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignedCharArrayUnion&lt;BucketT[InlineBuckets], LargeRep&gt; llvm::SmallDenseMap&lt; KeyT, ValueT, InlineBuckets, KeyInfoT, BucketT &gt;::storage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A "union" of an inline bucket array and the struct representing a large bucket.</p>


<p>This union will be discriminated by the 'Small' bit.</p>


<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">DenseMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
