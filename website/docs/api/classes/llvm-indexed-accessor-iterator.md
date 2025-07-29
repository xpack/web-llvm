---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/indexed-accessor-iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `indexed_accessor_iterator` Class Template

<p>A utility class used to implement an iterator that contains some base object and an index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;
class llvm::indexed_accessor_iterator&lt;DerivedT, BaseT, T, PointerT, ReferenceT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base class

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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a517b1a25d134842ab53868a8312f352e">indexed_accessor_iterator</a> (BaseT base, ptrdiff_t index)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ptrdiff_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7fe270e405157ad081d72e657656532">operator-</a> (const indexed_accessor_iterator &amp;rhs) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45df816b33270e7c87b9b7bcb410d094">operator==</a> (const indexed_accessor_iterator &amp;rhs) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab176fb8a66aa224ccdd504c94e5d57d7">operator&lt;</a> (const indexed_accessor_iterator &amp;rhs) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a037880b694f48c17e8b0c2a9423914ad">operator+=</a> (ptrdiff_t offset)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8660fbbf1c280ddfcae1edcf05aa4aee">operator-=</a> (ptrdiff_t offset)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ptrdiff_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af145628903dd5d51ad54f9af5e4ab1f0">getIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current index of the iterator. <a href="#af145628903dd5d51ad54f9af5e4ab1f0">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fb9091ec48043cac0e790b606315e2f">getBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current base of the iterator. <a href="#a3fb9091ec48043cac0e790b606315e2f">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5cf0868bb937458199a97b3fd751e5d">base</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ptrdiff_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75f046f6e58f7d1484d4140eb4481fb3">index</a></td>
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

## Description {#details}

<p>A utility class used to implement an iterator that contains some base object and an index.</p>


<p>The iterator moves the index but keeps the base constant.</p>


<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### indexed\_accessor\_iterator() {#a517b1a25d134842ab53868a8312f352e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator (BaseT base, ptrdiff_t index)</td>
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



<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="#ab5cf0868bb937458199a97b3fd751e5d">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a> and <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a>.</p>


<p>Referenced by <a href="#aa7fe270e405157ad081d72e657656532">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator-</a>, <a href="#ab176fb8a66aa224ccdd504c94e5d57d7">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator&lt;</a> and <a href="#a45df816b33270e7c87b9b7bcb410d094">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#aa7fe270e405157ad081d72e657656532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ptrdiff_t llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator">indexed_accessor_iterator</a> &amp; rhs)</td>
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



<p>Definition at line 1208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab5cf0868bb937458199a97b3fd751e5d">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>, <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a> and <a href="#a517b1a25d134842ab53868a8312f352e">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator</a>.</p>

</div>
</div>

### operator-=() {#a8660fbbf1c280ddfcae1edcf05aa4aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT &amp; llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator-= (ptrdiff_t offset)</td>
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



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a>.</p>

</div>
</div>

### operator+=() {#a037880b694f48c17e8b0c2a9423914ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT &amp; llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator+= (ptrdiff_t offset)</td>
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



<p>Definition at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a>.</p>

</div>
</div>

### operator&lt;() {#ab176fb8a66aa224ccdd504c94e5d57d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator">indexed_accessor_iterator</a> &amp; rhs)</td>
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



<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab5cf0868bb937458199a97b3fd751e5d">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>, <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a> and <a href="#a517b1a25d134842ab53868a8312f352e">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator</a>.</p>

</div>
</div>

### operator==() {#a45df816b33270e7c87b9b7bcb410d094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator">indexed_accessor_iterator</a> &amp; rhs)</td>
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



<p>Definition at line 1212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab5cf0868bb937458199a97b3fd751e5d">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>, <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a> and <a href="#a517b1a25d134842ab53868a8312f352e">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBase() {#a3fb9091ec48043cac0e790b606315e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseT &amp; llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase ()</td>
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

<p>Returns the current base of the iterator.</p>

<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#ab5cf0868bb937458199a97b3fd751e5d">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</a>.</p>

</div>
</div>

### getIndex() {#af145628903dd5d51ad54f9af5e4ab1f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ptrdiff_t llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getIndex ()</td>
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

<p>Returns the current index of the iterator.</p>

<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="#a75f046f6e58f7d1484d4140eb4481fb3">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### base {#ab5cf0868bb937458199a97b3fd751e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseT llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::base</td>
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



<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Referenced by <a href="#a3fb9091ec48043cac0e790b606315e2f">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase</a>, <a href="#a517b1a25d134842ab53868a8312f352e">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator</a>, <a href="#aa7fe270e405157ad081d72e657656532">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator-</a>, <a href="#ab176fb8a66aa224ccdd504c94e5d57d7">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator&lt;</a> and <a href="#a45df816b33270e7c87b9b7bcb410d094">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator==</a>.</p>

</div>
</div>

### index {#a75f046f6e58f7d1484d4140eb4481fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ptrdiff_t llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::index</td>
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



<p>Definition at line 1240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Referenced by <a href="#af145628903dd5d51ad54f9af5e4ab1f0">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getIndex</a>, <a href="#a517b1a25d134842ab53868a8312f352e">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_iterator</a>, <a href="#a037880b694f48c17e8b0c2a9423914ad">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator+=</a>, <a href="#aa7fe270e405157ad081d72e657656532">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator-</a>, <a href="#a8660fbbf1c280ddfcae1edcf05aa4aee">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator-=</a>, <a href="#ab176fb8a66aa224ccdd504c94e5d57d7">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator&lt;</a> and <a href="#a45df816b33270e7c87b9b7bcb410d094">llvm::indexed_accessor_iterator&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::operator==</a>.</p>

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
