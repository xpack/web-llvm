---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/legalitypredicates
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `LegalityPredicates` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::LegalityPredicates { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/legalitypredicates/typepairandmemdesc">TypePairAndMemDesc</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4e7de391b596827b188fd62730d42a0">predNot</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff P is false. <a href="#af4e7de391b596827b188fd62730d42a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7ac7032baa62cc00002886633b9f281">all</a> (Predicate P0, Predicate P1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff P0 and P1 are true. <a href="#ad7ac7032baa62cc00002886633b9f281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28a65210b9f6b07e94db8b70271b14a8">all</a> (Predicate P0, Predicate P1, Args... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff all given predicates are true. <a href="#a28a65210b9f6b07e94db8b70271b14a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fef38ab5d0c9c582fe6cae7d8badf5f">any</a> (Predicate P0, Predicate P1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff P0 or P1 are true. <a href="#a6fef38ab5d0c9c582fe6cae7d8badf5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab923bbaa377b4c44c19e7b95ae2e98e5">any</a> (Predicate P0, Predicate P1, Args... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff any given predicates are true. <a href="#ab923bbaa377b4c44c19e7b95ae2e98e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56d6ae68f8659cfaa29fb7cb601f111">typeIs</a> (unsigned TypeIdx, LLT TypesInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given type index is the specified type. <a href="#ae56d6ae68f8659cfaa29fb7cb601f111">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b65801c5b31890a1d1cd8a0038aee87">typeInSet</a> (unsigned TypeIdx, std::initializer_list&lt; LLT &gt; TypesInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given type index is one of the specified types. <a href="#a3b65801c5b31890a1d1cd8a0038aee87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82dcf447c1a6ace035cab178a049b39">typeIsNot</a> (unsigned TypeIdx, LLT Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given type index is not the specified type. <a href="#ab82dcf447c1a6ace035cab178a049b39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6273cfdaa9c2379ffe7205c2104776">typePairInSet</a> (unsigned TypeIdx0, unsigned TypeIdx1, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; TypesInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given types for the given pair of type indexes is one of the specified type pairs. <a href="#a5d6273cfdaa9c2379ffe7205c2104776">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce928e89fb1edf609be76967c6c3084">typeTupleInSet</a> (unsigned TypeIdx0, unsigned TypeIdx1, unsigned Type2, std::initializer_list&lt; std::tuple&lt; LLT, LLT, LLT &gt; &gt; TypesInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given types for the given tuple of type indexes is one of the specified type tuple. <a href="#acce928e89fb1edf609be76967c6c3084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6ccbdc579ec9f5c1f838d091b938da">typePairAndMemDescInSet</a> (unsigned TypeIdx0, unsigned TypeIdx1, unsigned MMOIdx, std::initializer_list&lt; TypePairAndMemDesc &gt; TypesAndMemDescInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the given types for the given pair of type indexes is one of the specified type pairs. <a href="#adb6ccbdc579ec9f5c1f838d091b938da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082316e51330aeb051eaed458a9f8304">isScalar</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar. <a href="#a082316e51330aeb051eaed458a9f8304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c6d0c31153197f492410b3c0a37248">isVector</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a vector. <a href="#ab8c6d0c31153197f492410b3c0a37248">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a162108a998b12a5f51009e450d898c">isPointer</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a pointer (with any address space). <a href="#a3a162108a998b12a5f51009e450d898c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8769baa0a1461970c101c1af46f1dc">isPointer</a> (unsigned TypeIdx, unsigned AddrSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a pointer with the specified address space. <a href="#a9e8769baa0a1461970c101c1af46f1dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ec5f3bcaf89f94246b4c4784ed4d10">isPointerVector</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a vector of pointers (with any address space). <a href="#a39ec5f3bcaf89f94246b4c4784ed4d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e87df9fdd3792e1b0c27ccf85466cfe">elementTypeIs</a> (unsigned TypeIdx, LLT EltTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the type index is a vector with element type <span class="doxyComputerOutput">EltTy</span>. <a href="#a7e87df9fdd3792e1b0c27ccf85466cfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9e886f18a84258e4f794e31aad0bd9">scalarNarrowerThan</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar that's narrower than the given size. <a href="#aff9e886f18a84258e4f794e31aad0bd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80fd220e67295d05887d3f948695ab2">scalarWiderThan</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar that's wider than the given size. <a href="#af80fd220e67295d05887d3f948695ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c5e76f97f435ea42bccaa6242aba92">scalarOrEltNarrowerThan</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar or vector with an element type that's narrower than the given size. <a href="#a87c5e76f97f435ea42bccaa6242aba92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0460dde35b7517637d8ac040900d42ba">scalarOrEltWiderThan</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar or a vector with an element type that's wider than the given size. <a href="#a0460dde35b7517637d8ac040900d42ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec4750bfce575e00982f15e55ee044f">sizeNotMultipleOf</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar whose size is not a multiple of Size. <a href="#adec4750bfce575e00982f15e55ee044f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac444cce31f4cc1906cea922fc1f208e2">sizeNotPow2</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar whose size is not a power of. <a href="#ac444cce31f4cc1906cea922fc1f208e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e5ea86447c9f63597873fcdc69e631">scalarOrEltSizeNotPow2</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a scalar or vector whose element size is not a power of 2. <a href="#a56e5ea86447c9f63597873fcdc69e631">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72a80bbb62a1013bb4f43253a4bad1b">sizeIs</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the total bitwidth of the specified type index is <span class="doxyComputerOutput">Size</span> bits. <a href="#aa72a80bbb62a1013bb4f43253a4bad1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe85e30d27726cff2560b3a859f6d90">sameSize</a> (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type indices are both the same bit size. <a href="#a7fe85e30d27726cff2560b3a859f6d90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d4c5153a7d50efd2b3e8408193dfab">largerThan</a> (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the first type index has a larger total bit size than second type index. <a href="#a58d4c5153a7d50efd2b3e8408193dfab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c9d1ec6a1b46697b0363f2c8a605c5">smallerThan</a> (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the first type index has a smaller total bit size than second type index. <a href="#a45c9d1ec6a1b46697b0363f2c8a605c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1581af0215e33dd0bc26f84d67aa610a">memSizeInBytesNotPow2</a> (unsigned MMOIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified MMO index has a size (rounded to bytes) that is not a power of 2. <a href="#a1581af0215e33dd0bc26f84d67aa610a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c37e901bc47ad309a6f13c2edeecd4">memSizeNotByteSizePow2</a> (unsigned MMOIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified MMO index has a size that is not an even byte size, or that even byte size is not a power of 2. <a href="#a66c37e901bc47ad309a6f13c2edeecd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f92b98415f16ce9abea7570e4f4df0">numElementsNotPow2</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified type index is a vector whose element count is not a power of 2. <a href="#a18f92b98415f16ce9abea7570e4f4df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d17100c5b9375e90f20d666f7615c56">atomicOrderingAtLeastOrStrongerThan</a> (unsigned MMOIdx, AtomicOrdering Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff the specified MMO index has at an atomic ordering of at Ordering or stronger. <a href="#a4d17100c5b9375e90f20d666f7615c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### all() {#ad7ac7032baa62cc00002886633b9f281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::LegalityPredicates::all (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P0, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff P0 and P1 are true.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### all() {#a28a65210b9f6b07e94db8b70271b14a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::LegalityPredicates::all (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P0, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P1, Args... args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff all given predicates are true.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>.</p>

</div>
</div>

### any() {#a6fef38ab5d0c9c582fe6cae7d8badf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::LegalityPredicates::any (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P0, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff P0 or P1 are true.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="#ab923bbaa377b4c44c19e7b95ae2e98e5">any</a>.</p>

</div>
</div>

### any() {#ab923bbaa377b4c44c19e7b95ae2e98e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::LegalityPredicates::any (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P0, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P1, Args... args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff any given predicates are true.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a6fef38ab5d0c9c582fe6cae7d8badf5f">any</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>.</p>

</div>
</div>

### atomicOrderingAtLeastOrStrongerThan() {#a4d17100c5b9375e90f20d666f7615c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::atomicOrderingAtLeastOrStrongerThan (unsigned MMOIdx, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified MMO index has at an atomic ordering of at Ordering or stronger.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f04318888b610cbdd037adc9b1b17e3">llvm::isAtLeastOrStrongerThan</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### elementTypeIs() {#a7e87df9fdd3792e1b0c27ccf85466cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::elementTypeIs (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the type index is a vector with element type <span class="doxyComputerOutput">EltTy</span>.</p>

<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isPointer() {#a3a162108a998b12a5f51009e450d898c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::isPointer (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a pointer (with any address space).</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isPointer() {#a9e8769baa0a1461970c101c1af46f1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::isPointer (unsigned TypeIdx, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a pointer with the specified address space.</p>

<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>

</div>
</div>

### isPointerVector() {#a39ec5f3bcaf89f94246b4c4784ed4d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::isPointerVector (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a vector of pointers (with any address space).</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### isScalar() {#a082316e51330aeb051eaed458a9f8304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::isScalar (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar.</p>

<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isVector() {#ab8c6d0c31153197f492410b3c0a37248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::isVector (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a vector.</p>

<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### largerThan() {#a58d4c5153a7d50efd2b3e8408193dfab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::largerThan (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the first type index has a larger total bit size than second type index.</p>

<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### memSizeInBytesNotPow2() {#a1581af0215e33dd0bc26f84d67aa610a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::memSizeInBytesNotPow2 (unsigned MMOIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified MMO index has a size (rounded to bytes) that is not a power of 2.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a479d3f2cd21c2250ae84ec2b06be816f">llvm::LegalizeRuleSet::lowerIfMemSizeNotPow2</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac87cf76397c445a62260d503afd96cf6">llvm::LegalizeRuleSet::unsupportedIfMemSizeNotPow2</a>.</p>

</div>
</div>

### memSizeNotByteSizePow2() {#a66c37e901bc47ad309a6f13c2edeecd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::memSizeNotByteSizePow2 (unsigned MMOIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified MMO index has a size that is not an even byte size, or that even byte size is not a power of 2.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a8b8f5d788ec31cd57f429ce38b5e3bb7">llvm::LLT::isByteSized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a5361d650c0e9459b1dc4c3afec8251ef">llvm::LegalizeRuleSet::lowerIfMemSizeNotByteSizePow2</a>.</p>

</div>
</div>

### numElementsNotPow2() {#a18f92b98415f16ce9abea7570e4f4df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::numElementsNotPow2 (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a vector whose element count is not a power of 2.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>

</div>
</div>

### predNot() {#af4e7de391b596827b188fd62730d42a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::LegalityPredicates::predNot (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff P is false.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### sameSize() {#a7fe85e30d27726cff2560b3a859f6d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::sameSize (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type indices are both the same bit size.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### scalarNarrowerThan() {#aff9e886f18a84258e4f794e31aad0bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::scalarNarrowerThan (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar that's narrower than the given size.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### scalarOrEltNarrowerThan() {#a87c5e76f97f435ea42bccaa6242aba92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::scalarOrEltNarrowerThan (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar or vector with an element type that's narrower than the given size.</p>

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### scalarOrEltSizeNotPow2() {#a56e5ea86447c9f63597873fcdc69e631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::scalarOrEltSizeNotPow2 (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar or vector whose element size is not a power of 2.</p>

<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>

</div>
</div>

### scalarOrEltWiderThan() {#a0460dde35b7517637d8ac040900d42ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::scalarOrEltWiderThan (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar or a vector with an element type that's wider than the given size.</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### scalarWiderThan() {#af80fd220e67295d05887d3f948695ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::scalarWiderThan (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar that's wider than the given size.</p>

<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### sizeIs() {#aa72a80bbb62a1013bb4f43253a4bad1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::sizeIs (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the total bitwidth of the specified type index is <span class="doxyComputerOutput">Size</span> bits.</p>

<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### sizeNotMultipleOf() {#adec4750bfce575e00982f15e55ee044f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::sizeNotMultipleOf (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar whose size is not a multiple of Size.</p>

<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### sizeNotPow2() {#ac444cce31f4cc1906cea922fc1f208e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::sizeNotPow2 (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the specified type index is a scalar whose size is not a power of.</p>


<ol class="doxyList" type="1">
</ol>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>.</p>

</div>
</div>

### smallerThan() {#a45c9d1ec6a1b46697b0363f2c8a605c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::smallerThan (unsigned TypeIdx0, unsigned TypeIdx1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the first type index has a smaller total bit size than second type index.</p>

<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### typeInSet() {#a3b65801c5b31890a1d1cd8a0038aee87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typeInSet (unsigned TypeIdx, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; TypesInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the given type index is one of the specified types.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a6b25441e6e04451dbc324440387f0ffb">typeIsLegalBoolVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a88ce58d5c26dbb6a3a6902c4bef5ed4d">typeIsLegalIntOrFPVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#add2fb044d0bb3af5ef4e27dd3f97e062">typeIsLegalPtrVec</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### typeIs() {#ae56d6ae68f8659cfaa29fb7cb601f111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typeIs (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TypesInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the given type index is the specified type.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### typeIsNot() {#ab82dcf447c1a6ace035cab178a049b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typeIsNot (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Type)</td>
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

<p>True iff the given type index is not the specified type.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### typePairAndMemDescInSet() {#adb6ccbdc579ec9f5c1f838d091b938da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typePairAndMemDescInSet (unsigned TypeIdx0, unsigned TypeIdx1, unsigned MMOIdx, std::initializer_list&lt; <a href="/web-llvm/docs/api/structs/llvm/legalitypredicates/typepairandmemdesc">TypePairAndMemDesc</a> &gt; TypesAndMemDescInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the given types for the given pair of type indexes is one of the specified type pairs.</p>

<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#aebb3b5876088ebfd2d003d68f7fb4b07">llvm::LegalizeRuleSet::legalForTypesWithMemDesc</a>.</p>

</div>
</div>

### typePairInSet() {#a5d6273cfdaa9c2379ffe7205c2104776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typePairInSet (unsigned TypeIdx0, unsigned TypeIdx1, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; TypesInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the given types for the given pair of type indexes is one of the specified type pairs.</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### typeTupleInSet() {#acce928e89fb1edf609be76967c6c3084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate llvm::LegalityPredicates::typeTupleInSet (unsigned TypeIdx0, unsigned TypeIdx1, unsigned Type2, std::initializer_list&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; TypesInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff the given types for the given tuple of type indexes is one of the specified type tuple.</p>

<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalitypredicates-cpp">LegalityPredicates.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
