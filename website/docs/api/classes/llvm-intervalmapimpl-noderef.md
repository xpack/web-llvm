---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmapimpl/noderef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NodeRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::IntervalMapImpl::NodeRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74777684e6ef499e76e6824c24802eb">NodeRef</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> - Create a null ref. <a href="#af74777684e6ef499e76e6824c24802eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a916193f0e3cec258fe66c65c439de083">NodeRef</a> (NodeT *p, unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> - Create a reference to the node p with n elements. <a href="#a916193f0e3cec258fe66c65c439de083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2571e40a5386bf0740715a98c9e79868">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>operator bool - Detect a null ref. <a href="#a2571e40a5386bf0740715a98c9e79868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70531e13330905277a44ee65201fd843">operator==</a> (const NodeRef &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3597605c11930bfae19ef9528ae06a08">operator!=</a> (const NodeRef &amp;RHS) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a489c9ec9744fa38c9e3d295e87e55">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Return the number of elements in the referenced node. <a href="#a24a489c9ec9744fa38c9e3d295e87e55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681d9ddb7d9204b40a7c425a600a3233">setSize</a> (unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setSize - Update the node size. <a href="#a681d9ddb7d9204b40a7c425a600a3233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56a61be137a6adfe4327233a4e492f9">subtree</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>subtree - Access the i'th subtree reference in a branch node. <a href="#ad56a61be137a6adfe4327233a4e492f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72f4d80e311bbd788942cedb25e0ff4e">get</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get - Dereference as a NodeT reference. <a href="#a72f4d80e311bbd788942cedb25e0ff4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; void *, <a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl/#aacf91952cde5989ab8c6b38b501021c1a4b980c1f20e48e79647774737cf4f1ce">Log2CacheLine</a>, unsigned, CacheAlignedPointerTraits &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab235c175cfaef818c67faaaf6012fd00">pip</a></td>
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


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NodeRef() {#af74777684e6ef499e76e6824c24802eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMapImpl::NodeRef::NodeRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> - Create a null ref.</p>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a3597605c11930bfae19ef9528ae06a08">operator!=</a>, <a href="#a70531e13330905277a44ee65201fd843">operator==</a> and <a href="#ad56a61be137a6adfe4327233a4e492f9">subtree</a>.</p>

</div>
</div>

### NodeRef() {#a916193f0e3cec258fe66c65c439de083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMapImpl::NodeRef::NodeRef (NodeT * p, unsigned n)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> - Create a reference to the node p with n elements.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a2571e40a5386bf0740715a98c9e79868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMapImpl::NodeRef::operator bool ()</td>
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

<p>operator bool - Detect a null ref.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### operator!=() {#a3597605c11930bfae19ef9528ae06a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapImpl::NodeRef::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> &amp; RHS)</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#af74777684e6ef499e76e6824c24802eb">NodeRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a70531e13330905277a44ee65201fd843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapImpl::NodeRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> &amp; RHS)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af74777684e6ef499e76e6824c24802eb">NodeRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a72f4d80e311bbd788942cedb25e0ff4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT &amp; llvm::IntervalMapImpl::NodeRef::get ()</td>
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

<p>get - Dereference as a NodeT reference.</p>

<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator/#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a>.</p>

</div>
</div>

### setSize() {#a681d9ddb7d9204b40a7c425a600a3233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeRef::setSize (unsigned n)</td>
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

<p>setSize - Update the node size.</p>

<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### size() {#a24a489c9ec9744fa38c9e3d295e87e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::NodeRef::size ()</td>
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

<p>size - Return the number of elements in the referenced node.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#a1c13157576c73d4ad7c0c849a2e44115">llvm::IntervalMapImpl::Path::getLeftSibling</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#ae878a804adbd190aad9c23df62b0f352">llvm::IntervalMapImpl::Path::moveLeft</a>.</p>

</div>
</div>

### subtree() {#ad56a61be137a6adfe4327233a4e492f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef &amp; llvm::IntervalMapImpl::NodeRef::subtree (unsigned i)</td>
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

<p>subtree - Access the i'th subtree reference in a branch node.</p>


<p>This depends on branch nodes storing the <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> array as their first member.</p>


<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#af74777684e6ef499e76e6824c24802eb">NodeRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#a1c13157576c73d4ad7c0c849a2e44115">llvm::IntervalMapImpl::Path::getLeftSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#aa06e158d1edb782965a6507afab5ae47">llvm::IntervalMapImpl::Path::getRightSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#ae878a804adbd190aad9c23df62b0f352">llvm::IntervalMapImpl::Path::moveLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#a8186267aca496ea543bd8d2ec77660f7">llvm::IntervalMapImpl::Path::moveRight</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator/#a3187b02e986777ccb9953b73ac6fda6b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::pathFillFind</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#af6b9bc0a599f8d7071efbe343ffb5c06">llvm::IntervalMapImpl::Path::subtree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### pip {#ab235c175cfaef818c67faaaf6012fd00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;void*, Log2CacheLine, unsigned, CacheAlignedPointerTraits&gt; llvm::IntervalMapImpl::NodeRef::pip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
