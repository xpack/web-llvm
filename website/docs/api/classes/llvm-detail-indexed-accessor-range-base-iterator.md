---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/indexed-accessor-range-base/iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `iterator` Class

<p>An iterator element of this range. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::detail::indexed_accessor_range_base::iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator">indexed_accessor_iterator&lt;DerivedT, BaseT, T, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility class used to implement an iterator that contains some base object and an index. <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9f78d566add8b4eae348726ab39964">iterator</a> (BaseT owner, ptrdiff_t curIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ReferenceT</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99228bfc9e448e6fce8a3dad00f050e8">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22b41adce2fd92538b983f3ecbe4f8a">indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow access to the constructor. <a href="#ac22b41adce2fd92538b983f3ecbe4f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An iterator element of this range.</p>

<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### iterator() {#a5d9f78d566add8b4eae348726ab39964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::iterator::iterator (BaseT owner, ptrdiff_t curIndex)</td>
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



<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#a99228bfc9e448e6fce8a3dad00f050e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceT llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::iterator::operator* ()</td>
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



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator/#a3fb9091ec48043cac0e790b606315e2f">llvm::indexed_accessor_iterator&lt; iterator, BaseT, T, PointerT, ReferenceT &gt;::getBase</a> and <a href="/web-llvm/docs/api/classes/llvm/indexed-accessor-iterator/#af145628903dd5d51ad54f9af5e4ab1f0">llvm::indexed_accessor_iterator&lt; iterator, BaseT, T, PointerT, ReferenceT &gt;::getIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### indexed\_accessor\_range\_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt; {#ac22b41adce2fd92538b983f3ecbe4f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::detail::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::iterator::indexed_accessor_range_base&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow access to the constructor.</p>

<p>Definition at line 1274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

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
