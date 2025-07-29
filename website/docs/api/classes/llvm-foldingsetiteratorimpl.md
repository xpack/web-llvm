---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/foldingsetiteratorimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FoldingSetIteratorImpl` Class

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl">FoldingSetIteratorImpl</a> - This is the common iterator support shared by all folding sets, which knows how to walk the folding set hash table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FoldingSetIteratorImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator">FoldingSetIterator&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator">FoldingSetIterator&lt;T&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3297d4b587880e46293a51d51fe09db7">FoldingSetIteratorImpl</a> (void **Bucket)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975a54dd5c527154b2f2e40ff9bb1d7e">operator==</a> (const FoldingSetIteratorImpl &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f4cdad48ea77692b80fc45b9c38de7">operator!=</a> (const FoldingSetIteratorImpl &amp;RHS) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6151b8ecc444658e152761887bab9a">advance</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a368e3de8ea854f34bc97c21a64d6a164">FoldingSetNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0c28cde5b57b7e9dd171f65ca40fcb">NodePtr</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl">FoldingSetIteratorImpl</a> - This is the common iterator support shared by all folding sets, which knows how to walk the folding set hash table.</p>

<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### FoldingSetIteratorImpl() {#a3297d4b587880e46293a51d51fe09db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSetIteratorImpl::FoldingSetIteratorImpl (void ** Bucket)</td>
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



<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp/#a99f8ba1b9a42df5cb5d980ebf3748925">GetNextPtr</a> and <a href="#a0e0c28cde5b57b7e9dd171f65ca40fcb">NodePtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator/#a4257797a820989cc094562382919a504">llvm::FoldingSetIterator&lt; const T &gt;::FoldingSetIterator</a>, <a href="#ae2f4cdad48ea77692b80fc45b9c38de7">operator!=</a> and <a href="#a975a54dd5c527154b2f2e40ff9bb1d7e">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ae2f4cdad48ea77692b80fc45b9c38de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FoldingSetIteratorImpl::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl">FoldingSetIteratorImpl</a> &amp; RHS)</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="#a3297d4b587880e46293a51d51fe09db7">FoldingSetIteratorImpl</a>, <a href="#a0e0c28cde5b57b7e9dd171f65ca40fcb">NodePtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a975a54dd5c527154b2f2e40ff9bb1d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FoldingSetIteratorImpl::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl">FoldingSetIteratorImpl</a> &amp; RHS)</td>
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



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="#a3297d4b587880e46293a51d51fe09db7">FoldingSetIteratorImpl</a>, <a href="#a0e0c28cde5b57b7e9dd171f65ca40fcb">NodePtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### advance() {#acb6151b8ecc444658e152761887bab9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FoldingSetIteratorImpl::advance ()</td>
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



<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp/#a353da8c5013043b9425e9cc07012bd3e">GetBucketPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp/#a99f8ba1b9a42df5cb5d980ebf3748925">GetNextPtr</a> and <a href="#a0e0c28cde5b57b7e9dd171f65ca40fcb">NodePtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator/#af0e9506c023c4bfd56ea09bd731f37fb">llvm::FoldingSetIterator&lt; const T &gt;::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### NodePtr {#a0e0c28cde5b57b7e9dd171f65ca40fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSetNode* llvm::FoldingSetIteratorImpl::NodePtr</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>Referenced by <a href="#acb6151b8ecc444658e152761887bab9a">advance</a>, <a href="#a3297d4b587880e46293a51d51fe09db7">FoldingSetIteratorImpl</a>, <a href="#ae2f4cdad48ea77692b80fc45b9c38de7">operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator/#a3128649b968bb0b8c0da82737a7b368d">llvm::FoldingSetIterator&lt; const T &gt;::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetiterator/#a04535716e8d09ad6405f3abd03f4ed51">llvm::FoldingSetIterator&lt; const T &gt;::operator-&gt;</a> and <a href="#a975a54dd5c527154b2f2e40ff9bb1d7e">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
