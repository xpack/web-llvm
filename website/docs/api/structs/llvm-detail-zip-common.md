---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/zip-common
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `zip_common` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;
struct llvm::detail::zip_common&lt;ZipType, ReferenceTupleType, Iters&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base">iterator_facade_base&lt;DerivedT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class which implements the entire standard iterator facade in terms of a minimal subset of the interface. <a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01dd8174fcfba98b30761986e4af5771">Base</a> = <a href="/web-llvm/docs/api/namespaces/llvm/detail/#aa648cc5d245e2a6b2b8bbd94d1cb725c">zip_traits</a>&lt; ZipType, ReferenceTupleType, Iters... &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16929cb6ff133abbe335e9948b082b6a">IndexSequence</a> = std::index_sequence_for&lt; Iters... &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa340fc7810908d1d79d4c17809e3f59c">value_type</a> = typename <a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#a36fb299f78c975d65ffcef4baa31b7f6">Base::value_type</a></td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a47b5930119e3f6f4d67972cd255367b4">zip_common</a> (Iters &amp;&amp;... ts)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa340fc7810908d1d79d4c17809e3f59c">value_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75ce1e8033d83dc019606125c948eed6">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ZipType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73745accb84d608cc72821742d877aad">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ZipType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adaa7d73992845e625860b0b21dea3213">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acef42c40aa88a41a3c4872f4e01668f5">all_equals</a> (zip_common &amp;other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all the iterator are matching <span class="doxyComputerOutput">other</span>'s iterators. <a href="#acef42c40aa88a41a3c4872f4e01668f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa340fc7810908d1d79d4c17809e3f59c">value_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae6e457813e946c4e7eb0fe7fe77970f0">deref</a> (std::index_sequence&lt; Ns... &gt;) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ec599e6f3171e99655171d20fb634fe">tup_inc</a> (std::index_sequence&lt; Ns... &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adebd0ac73d2985d64eabecefc2a2f9aa">tup_dec</a> (std::index_sequence&lt; Ns... &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5dc4407c8231b886984f09407524b2b4">test_all_equals</a> (const zip_common &amp;other, std::index_sequence&lt; Ns... &gt;) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::tuple&lt; Iters... &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fc64436ed7f0c3434c241b4228ff16a">iterators</a></td>
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


<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#a01dd8174fcfba98b30761986e4af5771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::Base =  zip_traits&lt;ZipType, ReferenceTupleType, Iters...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### IndexSequence {#a16929cb6ff133abbe335e9948b082b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::IndexSequence =  std::index_sequence_for&lt;Iters...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### value\_type {#aa340fc7810908d1d79d4c17809e3f59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::value_type =  typename Base::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### zip\_common() {#a47b5930119e3f6f4d67972cd255367b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::zip_common (Iters &amp;&amp;... ts)</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</a>.</p>


<p>Referenced by <a href="#acef42c40aa88a41a3c4872f4e01668f5">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::all_equals</a> and <a href="#a5dc4407c8231b886984f09407524b2b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::test_all_equals</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#adaa7d73992845e625860b0b21dea3213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ZipType &amp; llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator-- ()</td>
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



<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#ad879b56a6ea95b7da949bfa63d03dde4a4e1f229fa73b6b5c2f25734ab347c51f">llvm::iterator_facade_base&lt; DerivedT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT &gt;::IsBidirectional</a> and <a href="#adebd0ac73d2985d64eabecefc2a2f9aa">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_dec</a>.</p>

</div>
</div>

### operator\*() {#a75ce1e8033d83dc019606125c948eed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator* ()</td>
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



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#ae6e457813e946c4e7eb0fe7fe77970f0">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::deref</a>.</p>

</div>
</div>

### operator++() {#a73745accb84d608cc72821742d877aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ZipType &amp; llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator++ ()</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a2ec599e6f3171e99655171d20fb634fe">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_inc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### all\_equals() {#acef42c40aa88a41a3c4872f4e01668f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::all_equals (<a href="/web-llvm/docs/api/structs/llvm/detail/zip-common">zip_common</a> &amp; other)</td>
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

<p>Return true if all the iterator are matching <span class="doxyComputerOutput">other</span>'s iterators.</p>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#a5dc4407c8231b886984f09407524b2b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::test_all_equals</a> and <a href="#a47b5930119e3f6f4d67972cd255367b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::zip_common</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### deref() {#ae6e457813e946c4e7eb0fe7fe77970f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::deref (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</a>.</p>


<p>Referenced by <a href="#a75ce1e8033d83dc019606125c948eed6">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator*</a>.</p>

</div>
</div>

### test\_all\_equals() {#a5dc4407c8231b886984f09407524b2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::test_all_equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/zip-common">zip_common</a> &amp; other, std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</a> and <a href="#a47b5930119e3f6f4d67972cd255367b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::zip_common</a>.</p>


<p>Referenced by <a href="#acef42c40aa88a41a3c4872f4e01668f5">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::all_equals</a>.</p>

</div>
</div>

### tup\_dec() {#adebd0ac73d2985d64eabecefc2a2f9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_dec (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</a>.</p>


<p>Referenced by <a href="#adaa7d73992845e625860b0b21dea3213">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator--</a>.</p>

</div>
</div>

### tup\_inc() {#a2ec599e6f3171e99655171d20fb634fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_inc (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</a>.</p>


<p>Referenced by <a href="#a73745accb84d608cc72821742d877aad">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### iterators {#a6fc64436ed7f0c3434c241b4228ff16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ZipType, typename ReferenceTupleType, typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt;Iters...&gt; llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::iterators</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Referenced by <a href="#ae6e457813e946c4e7eb0fe7fe77970f0">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::deref</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/zip-first/#a9ada7b85e52dbc0c0f90dcaeaf6d015d">llvm::detail::zip_first&lt; Iters &gt;::operator==</a>, <a href="#a5dc4407c8231b886984f09407524b2b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::test_all_equals</a>, <a href="#adebd0ac73d2985d64eabecefc2a2f9aa">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_dec</a>, <a href="#a2ec599e6f3171e99655171d20fb634fe">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::tup_inc</a> and <a href="#a47b5930119e3f6f4d67972cd255367b4">llvm::detail::zip_common&lt; ZipType, ReferenceTupleType, Iters &gt;::zip_common</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
