---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/foldingsetbucketiteratorimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FoldingSetBucketIteratorImpl` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiteratorimpl">FoldingSetBucketIteratorImpl</a> - This is the common bucket iterator support shared by all folding sets, which knows how to walk a particular bucket of a folding set hash table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FoldingSetBucketIteratorImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator">FoldingSetBucketIterator&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90952c33551c531abe5416e86b9280ba">FoldingSetBucketIteratorImpl</a> (void **Bucket)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92030bbb886c732c503b8685a56c9fbf">FoldingSetBucketIteratorImpl</a> (void **Bucket, bool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b6b40fbf1e86c83f0ecf6f1ac5a8dc">operator==</a> (const FoldingSetBucketIteratorImpl &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c0caf5877750981834be3512d4ec7e">operator!=</a> (const FoldingSetBucketIteratorImpl &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9afee6b0afc00ddc084e2b32a7a90e9">advance</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiteratorimpl">FoldingSetBucketIteratorImpl</a> - This is the common bucket iterator support shared by all folding sets, which knows how to walk a particular bucket of a folding set hash table.</p>

<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### FoldingSetBucketIteratorImpl() {#a90952c33551c531abe5416e86b9280ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSetBucketIteratorImpl::FoldingSetBucketIteratorImpl (void ** Bucket)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp/#a99f8ba1b9a42df5cb5d980ebf3748925">GetNextPtr</a> and <a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#a908ba8132ac6997c54b8596b5b7cb9de">llvm::FoldingSetBucketIterator&lt; T &gt;::FoldingSetBucketIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#a5013a4bf990cc499195989bdd445f34b">llvm::FoldingSetBucketIterator&lt; T &gt;::FoldingSetBucketIterator</a>, <a href="#a94c0caf5877750981834be3512d4ec7e">operator!=</a> and <a href="#ad9b6b40fbf1e86c83f0ecf6f1ac5a8dc">operator==</a>.</p>

</div>
</div>

### FoldingSetBucketIteratorImpl() {#a92030bbb886c732c503b8685a56c9fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FoldingSetBucketIteratorImpl::FoldingSetBucketIteratorImpl (void ** Bucket, bool)</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>Reference <a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a94c0caf5877750981834be3512d4ec7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FoldingSetBucketIteratorImpl::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiteratorimpl">FoldingSetBucketIteratorImpl</a> &amp; RHS)</td>
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



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="#a90952c33551c531abe5416e86b9280ba">FoldingSetBucketIteratorImpl</a>, <a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#ad9b6b40fbf1e86c83f0ecf6f1ac5a8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FoldingSetBucketIteratorImpl::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiteratorimpl">FoldingSetBucketIteratorImpl</a> &amp; RHS)</td>
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



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="#a90952c33551c531abe5416e86b9280ba">FoldingSetBucketIteratorImpl</a>, <a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### advance() {#ab9afee6b0afc00ddc084e2b32a7a90e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FoldingSetBucketIteratorImpl::advance ()</td>
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



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>Reference <a href="#a469c904a4f5611130d48fcde63ec1a4d">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#aefa4126544f6cf21015b11955b710205">llvm::FoldingSetBucketIterator&lt; T &gt;::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ptr {#a469c904a4f5611130d48fcde63ec1a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::FoldingSetBucketIteratorImpl::Ptr</td>
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



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>Referenced by <a href="#ab9afee6b0afc00ddc084e2b32a7a90e9">advance</a>, <a href="#a90952c33551c531abe5416e86b9280ba">FoldingSetBucketIteratorImpl</a>, <a href="#a92030bbb886c732c503b8685a56c9fbf">FoldingSetBucketIteratorImpl</a>, <a href="#a94c0caf5877750981834be3512d4ec7e">operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#abea64771792717776ce6dbdff85fb92b">llvm::FoldingSetBucketIterator&lt; T &gt;::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#a39cd1ff6275681acb651d1959c58795b">llvm::FoldingSetBucketIterator&lt; T &gt;::operator-&gt;</a> and <a href="#ad9b6b40fbf1e86c83f0ecf6f1ac5a8dc">operator==</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
