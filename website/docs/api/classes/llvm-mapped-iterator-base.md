---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mapped-iterator-base
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `mapped_iterator_base` Class Template

<p>A base type of mapped iterator, that is useful for building derived iterators that do not need/want to store the map function (as in <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;
class llvm::mapped_iterator_base&lt;DerivedT, ItTy, ReferenceTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base">iterator_adaptor_base&lt;DerivedT, WrappedIteratorT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class for adapting an iterator to a different type. <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63942b906430ad3b1999b9263e697388">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator-base">mapped_iterator_base</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a68fffcef509e785b53f8457b091e4e00">mapped_iterator_base</a> (ItTy U)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ReferenceTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada59708f4073c2c48d52d78b2148007b">operator*</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ItTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a101d05213262dc94366b1b0827145474">getCurrent</a> ()</td>
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

<p>A base type of mapped iterator, that is useful for building derived iterators that do not need/want to store the map function (as in <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>).</p>


<p>These iterators must simply provide a <span class="doxyComputerOutput">mapElement</span> method that defines how to map a value of the iterator to the provided reference type.</p>


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BaseT {#a63942b906430ad3b1999b9263e697388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::BaseT =  mapped_iterator_base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### mapped\_iterator\_base() {#a68fffcef509e785b53f8457b091e4e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::mapped_iterator_base (ItTy U)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a8170d24cedaf5c2a22d8fc0c986529aa">llvm::iterator_adaptor_base&lt; DerivedT, ItTy, std::iterator_traits&lt; ItTy &gt;::iterator_category, std::remove_reference_t&lt; ReferenceTy &gt;, std::iterator_traits&lt; ItTy &gt;::difference_type, std::remove_reference_t&lt; ReferenceTy &gt; *, ReferenceTy &gt;::iterator_adaptor_base</a>, <a href="#a68fffcef509e785b53f8457b091e4e00">llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::mapped_iterator_base</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a68fffcef509e785b53f8457b091e4e00">llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::mapped_iterator_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#ada59708f4073c2c48d52d78b2148007b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceTy llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::operator* ()</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCurrent() {#a101d05213262dc94366b1b0827145474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename ItTy, typename ReferenceTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItTy llvm::mapped_iterator_base&lt; DerivedT, ItTy, ReferenceTy &gt;::getCurrent ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

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
