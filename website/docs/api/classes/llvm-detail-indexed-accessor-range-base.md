---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/indexed-accessor-range-base
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `indexed_accessor_range_base` Class Template

<p>The class represents the base of a range of indexed_accessor_iterators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;
class llvm::detail::indexed_accessor_range_base&lt;DerivedT, BaseT, T, PointerT, ReferenceT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ab2ac0d5feda0152c6a76354af941fd">RangeBaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base</a></td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acf0f3d80cf8d7bc25c8b106554e68904">indexed_accessor_range_base</a> (iterator begin, iterator end)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afc6db16d311357f328376ef54e752fa4">indexed_accessor_range_base</a> (const iterator_range&lt; iterator &gt; &amp;range)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aabf39629746016ff419fb504de4f9f67">indexed_accessor_range_base</a> (BaseT base, ptrdiff_t count)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa84d686e929b12380109ba54bd7e2227">indexed_accessor_range_base</a> (const indexed_accessor_range_base &amp;)=default</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acdbc436cd3fae8e08f03188575a97213">indexed_accessor_range_base</a> (indexed_accessor_range_base &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ReferenceT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a550c6625510bfffcf3203397356131f4">operator[]</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0f336ee8b507b611acf4e4ed68f38d53">operator RangeT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow conversion to any type accepting an <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>. <a href="#a0f336ee8b507b611acf4e4ed68f38d53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a365baa51c027435cb1d23b262ae80e19">operator=</a> (const indexed_accessor_range_base &amp;)=default</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a945303f55a3bae971dbb7e6412e5d093">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5996ae4346dc4a72183fbea0871c9d71">end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ReferenceT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0eb48a212d6513eb931a922855e1a845">front</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ReferenceT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef2794d6164d365741a48cf4602e7140">back</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e0e5c9708abfc6a7794430d7d1115f9">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of this range. <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a265d781e6e01703afe6d7916691d332d">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the range is empty. <a href="#a265d781e6e01703afe6d7916691d332d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11452cc3e5b0cc2e34f69f82cddd54ea">slice</a> (size_t n, size_t m) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the first N elements, and keep M elements. <a href="#a11452cc3e5b0cc2e34f69f82cddd54ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73bdc7b7fc1c42d5577a5ab8830c2dec">drop_front</a> (size_t n=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the first n elements. <a href="#a73bdc7b7fc1c42d5577a5ab8830c2dec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a645fed22968e5a7e1fbfc59401ffacff">drop_back</a> (size_t n=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the last n elements. <a href="#a645fed22968e5a7e1fbfc59401ffacff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f2eed5e7ca8bb0418c027ddc2c2b559">take_front</a> (size_t n=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the first n elements. <a href="#a4f2eed5e7ca8bb0418c027ddc2c2b559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73b84291eebc52a02fe862f829357bc6">take_back</a> (size_t n=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the last n elements. <a href="#a73b84291eebc52a02fe862f829357bc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affd926eaa6a4ecda1b7e71f78e7281a0">getBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base of this range. <a href="#affd926eaa6a4ecda1b7e71f78e7281a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BaseT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb143d573a4e41d3a8cac8ea071cf1cd">base</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base that owns the provided range of values. <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ptrdiff_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9433a1702cda5c69423a7dc08171ab8">count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size from the owning range. <a href="#af9433a1702cda5c69423a7dc08171ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static BaseT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9ee4dc15b01cdacc2f6c5040683b7ae">offset_base</a> (const BaseT &amp;base, size_t n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset the given base by the given amount. <a href="#ae9ee4dc15b01cdacc2f6c5040683b7ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The class represents the base of a range of indexed_accessor_iterators.</p>


<p>It provides support for many different range functionalities, e.g. drop_front/slice/etc.. Derived range classes must implement the following static methods:</p>


<ul class="doxyList ">
<li>ReferenceT dereference_iterator(const BaseT &amp;base, ptrdiff_t index)

<ul class="doxyList ">
<li>Dereference an iterator pointing to the base object at the given index.</li>
</ul></li>
<li>BaseT offset_base(const BaseT &amp;base, ptrdiff_t index)

<ul class="doxyList ">
<li>Return a new base that is offset from the provide base by 'index' elements.</li>
</ul></li>
</ul>

<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RangeBaseT {#a6ab2ac0d5feda0152c6a76354af941fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::RangeBaseT =  indexed_accessor_range_base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### indexed\_accessor\_range\_base() {#acf0f3d80cf8d7bc25c8b106554e68904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base (<a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/iterator">iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/iterator">iterator</a> end)</td>
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



<p>Definition at line 1278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>, <a href="#a945303f55a3bae971dbb7e6412e5d093">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::begin</a>, <a href="#af9433a1702cda5c69423a7dc08171ab8">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::count</a>, <a href="#a5996ae4346dc4a72183fbea0871c9d71">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::end</a> and <a href="#affd926eaa6a4ecda1b7e71f78e7281a0">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase</a>.</p>


<p>Referenced by <a href="#aa84d686e929b12380109ba54bd7e2227">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>, <a href="#afc6db16d311357f328376ef54e752fa4">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>, <a href="#acdbc436cd3fae8e08f03188575a97213">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a> and <a href="#a365baa51c027435cb1d23b262ae80e19">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator=</a>.</p>

</div>
</div>

### indexed\_accessor\_range\_base() {#afc6db16d311357f328376ef54e752fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/iterator">iterator</a> &gt; &amp; range)</td>
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



<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#a945303f55a3bae971dbb7e6412e5d093">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::begin</a>, <a href="#a5996ae4346dc4a72183fbea0871c9d71">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::end</a> and <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

### indexed\_accessor\_range\_base() {#aabf39629746016ff419fb504de4f9f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base (BaseT base, ptrdiff_t count)</td>
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



<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#af9433a1702cda5c69423a7dc08171ab8">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::count</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### indexed\_accessor\_range\_base() {#aa84d686e929b12380109ba54bd7e2227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

### indexed\_accessor\_range\_base() {#acdbc436cd3fae8e08f03188575a97213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base (<a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator RangeT() {#a0f336ee8b507b611acf4e4ed68f38d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT, typename = std::enable_if_t&lt;std::is_constructible&lt;                                 RangeT, iterator_range&lt;iterator&gt;&gt;::value&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator RangeT ()</td>
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

<p>Allow conversion to any type accepting an <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>.</p>

<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### operator\[\]() {#a550c6625510bfffcf3203397356131f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator[] (size_t Index)</td>
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



<p>Definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a365baa51c027435cb1d23b262ae80e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">indexed_accessor_range_base &amp; llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#aef2794d6164d365741a48cf4602e7140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::back ()</td>
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



<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a265d781e6e01703afe6d7916691d332d">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::empty</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>

</div>
</div>

### begin() {#a945303f55a3bae971dbb7e6412e5d093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::begin ()</td>
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



<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>.</p>


<p>Referenced by <a href="#afc6db16d311357f328376ef54e752fa4">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a> and <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

### drop\_back() {#a645fed22968e5a7e1fbfc59401ffacff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_back (size_t n=1)</td>
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

<p>Drop the last n elements.</p>

<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>


<p>Referenced by <a href="#a4f2eed5e7ca8bb0418c027ddc2c2b559">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_front</a>.</p>

</div>
</div>

### drop\_front() {#a73bdc7b7fc1c42d5577a5ab8830c2dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_front (size_t n=1)</td>
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

<p>Drop the first n elements.</p>

<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a> and <a href="#a11452cc3e5b0cc2e34f69f82cddd54ea">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::slice</a>.</p>


<p>Referenced by <a href="#a73b84291eebc52a02fe862f829357bc6">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_back</a>.</p>

</div>
</div>

### empty() {#a265d781e6e01703afe6d7916691d332d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::empty ()</td>
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

<p>Return if the range is empty.</p>

<p>Definition at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>


<p>Referenced by <a href="#aef2794d6164d365741a48cf4602e7140">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::back</a> and <a href="#a0eb48a212d6513eb931a922855e1a845">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::front</a>.</p>

</div>
</div>

### end() {#a5996ae4346dc4a72183fbea0871c9d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::end ()</td>
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



<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#af9433a1702cda5c69423a7dc08171ab8">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::count</a>.</p>


<p>Referenced by <a href="#afc6db16d311357f328376ef54e752fa4">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a> and <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

### front() {#a0eb48a212d6513eb931a922855e1a845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::front ()</td>
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



<p>Definition at line 1292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a265d781e6e01703afe6d7916691d332d">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::empty</a>.</p>

</div>
</div>

### getBase() {#affd926eaa6a4ecda1b7e71f78e7281a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseT &amp; llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase ()</td>
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

<p>Returns the base of this range.</p>

<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>.</p>


<p>Referenced by <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>.</p>

</div>
</div>

### size() {#a1e0e5c9708abfc6a7794430d7d1115f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size ()</td>
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

<p>Return the size of this range.</p>

<p>Definition at line 1302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#af9433a1702cda5c69423a7dc08171ab8">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::count</a>.</p>


<p>Referenced by <a href="#aef2794d6164d365741a48cf4602e7140">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::back</a>, <a href="#a645fed22968e5a7e1fbfc59401ffacff">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_back</a>, <a href="#a73bdc7b7fc1c42d5577a5ab8830c2dec">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_front</a>, <a href="#a265d781e6e01703afe6d7916691d332d">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::empty</a>, <a href="#a550c6625510bfffcf3203397356131f4">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator[]</a>, <a href="#a11452cc3e5b0cc2e34f69f82cddd54ea">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::slice</a>, <a href="#a73b84291eebc52a02fe862f829357bc6">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_back</a> and <a href="#a4f2eed5e7ca8bb0418c027ddc2c2b559">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_front</a>.</p>

</div>
</div>

### slice() {#a11452cc3e5b0cc2e34f69f82cddd54ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::slice (size_t n, size_t m)</td>
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

<p>Drop the first N elements, and keep M elements.</p>

<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>


<p>Referenced by <a href="#a73bdc7b7fc1c42d5577a5ab8830c2dec">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_front</a>.</p>

</div>
</div>

### take\_back() {#a73b84291eebc52a02fe862f829357bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_back (size_t n=1)</td>
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

<p>Take the last n elements.</p>

<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#a73bdc7b7fc1c42d5577a5ab8830c2dec">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_front</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>

</div>
</div>

### take\_front() {#a4f2eed5e7ca8bb0418c027ddc2c2b559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::take_front (size_t n=1)</td>
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

<p>Take the first n elements.</p>

<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#a645fed22968e5a7e1fbfc59401ffacff">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_back</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### base {#afb143d573a4e41d3a8cac8ea071cf1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The base that owns the provided range of values.</p>

<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Referenced by <a href="#a945303f55a3bae971dbb7e6412e5d093">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::begin</a>, <a href="#a645fed22968e5a7e1fbfc59401ffacff">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::drop_back</a>, <a href="#a5996ae4346dc4a72183fbea0871c9d71">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::end</a>, <a href="#affd926eaa6a4ecda1b7e71f78e7281a0">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase</a>, <a href="#aabf39629746016ff419fb504de4f9f67">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>, <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>, <a href="#a550c6625510bfffcf3203397356131f4">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator[]</a> and <a href="#a11452cc3e5b0cc2e34f69f82cddd54ea">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::slice</a>.</p>

</div>
</div>

### count {#af9433a1702cda5c69423a7dc08171ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ptrdiff_t llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::count</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size from the owning range.</p>

<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Referenced by <a href="#a5996ae4346dc4a72183fbea0871c9d71">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::end</a>, <a href="#aabf39629746016ff419fb504de4f9f67">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a>, <a href="#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range_base</a> and <a href="#a1e0e5c9708abfc6a7794430d7d1115f9">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### offset\_base() {#ae9ee4dc15b01cdacc2f6c5040683b7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::offset_base (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseT &amp; base, size_t n)</td>
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

<p>Offset the given base by the given amount.</p>

<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
