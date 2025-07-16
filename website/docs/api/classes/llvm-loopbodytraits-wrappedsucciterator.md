---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopbodytraits/wrappedsucciterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WrappedSuccIterator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LoopBodyTraits::WrappedSuccIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">llvm/Analysis/LoopIterator.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e05f71722a9adbb283f8b9626fdeab1">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base">iterator_adaptor_base</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loopbodytraits/wrappedsucciterator">WrappedSuccIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc56362e89d398a34b5da66ddedb5448">succ_iterator</a>, typename std::iterator_traits&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#acc56362e89d398a34b5da66ddedb5448">succ_iterator</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#a0fb41b5becfd488c52fb8c77d13fbcbc">::iterator_category</a>, <a href="/web-llvm/docs/api/structs/llvm/loopbodytraits/#a5c86e3f900a9e7558505112644e82fa0">NodeRef</a>, std::ptrdiff_t, <a href="/web-llvm/docs/api/structs/llvm/loopbodytraits/#a5c86e3f900a9e7558505112644e82fa0">NodeRef</a> *, <a href="/web-llvm/docs/api/structs/llvm/loopbodytraits/#a5c86e3f900a9e7558505112644e82fa0">NodeRef</a> &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8332d94c59f4e9e972df3144b8c12d36">WrappedSuccIterator</a> (succ_iterator Begin, const Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopbodytraits/#a5c86e3f900a9e7558505112644e82fa0">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f1a63f4d68f2af8421ae85d660d244">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ca7a9b1b44bd3c976d7214245f00d5">L</a></td>
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


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a9e05f71722a9adbb283f8b9626fdeab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopBodyTraits::WrappedSuccIterator::BaseT =  iterator_adaptor_base&lt;
        WrappedSuccIterator, succ_iterator,
        typename std::iterator_traits&lt;succ_iterator&gt;::iterator_category,
        NodeRef, std::ptrdiff_t, NodeRef *, NodeRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WrappedSuccIterator() {#a8332d94c59f4e9e972df3144b8c12d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopBodyTraits::WrappedSuccIterator::WrappedSuccIterator (<a href="/web-llvm/docs/api/namespaces/llvm/#acc56362e89d398a34b5da66ddedb5448">succ_iterator</a> Begin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#a12f1a63f4d68f2af8421ae85d660d244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::LoopBodyTraits::WrappedSuccIterator::operator* ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a563ec95255977c34566292cbdce193b3">llvm::iterator_adaptor_base&lt; WrappedSuccIterator, succ_iterator, std::iterator_traits&lt; succ_iterator &gt;::iterator_category, NodeRef, std::ptrdiff_t, NodeRef *, NodeRef &gt;::I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### L {#a50ca7a9b1b44bd3c976d7214245f00d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* llvm::LoopBodyTraits::WrappedSuccIterator::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">LoopIterator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
