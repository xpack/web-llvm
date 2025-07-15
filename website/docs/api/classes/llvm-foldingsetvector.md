---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/foldingsetvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FoldingSetVector` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetvector">FoldingSetVector</a> - This template class combines a <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> and a vector to provide the interface of <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> but with deterministic iteration order based on the insertion order. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;
class llvm::FoldingSetVector&lt;T, VectorT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa66424d10ca761f0b58aa065572ddb64">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; typename VectorT::iterator &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa1c91f420927e79019ab5c928b8cdb20">const_iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; typename VectorT::const_iterator &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad32230ee6b90ad3fac2d91a77b92979b">FoldingSetVector</a> (unsigned Log2InitSize=6)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa66424d10ca761f0b58aa065572ddb64">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00d59558d21aac5b0ce9771d976d5f69">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa66424d10ca761f0b58aa065572ddb64">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0556825383a064ddb0b917d3651563f4">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa1c91f420927e79019ab5c928b8cdb20">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af83466d43905687f2864cf1d70d43afa">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa1c91f420927e79019ab5c928b8cdb20">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a343dfe063144e63828e1246b9f3286">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7faffd79c0debbc3093fa5bee2ec473">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Remove all nodes from the folding set. <a href="#aa7faffd79c0debbc3093fa5bee2ec473">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8be7737b2b63e63c29750b3db01856e8">FindNodeOrInsertPos</a> (const FoldingSetNodeID &amp;ID, void *&amp;InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindNodeOrInsertPos - Look up the node specified by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a8be7737b2b63e63c29750b3db01856e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1af63f402c97ccdf0d2d3709c3c86f1c">GetOrInsertNode</a> (T *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetOrInsertNode - If there is an existing simple <a href="/web-llvm/docs/api/classes/node">Node</a> exactly equal to the specified node, return it. <a href="#a1af63f402c97ccdf0d2d3709c3c86f1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4ea13f6943a665055f541c7abda81b9">InsertNode</a> (T *N, void *InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertNode - Insert the specified node into the folding set, knowing that it is not already in the folding set. <a href="#af4ea13f6943a665055f541c7abda81b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c5a4127393e04cb5eb5c17fe83a3a0b">InsertNode</a> (T *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertNode - Insert the specified node into the folding set, knowing that it is not already in the folding set. <a href="#a7c5a4127393e04cb5eb5c17fe83a3a0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91b6fe3aff6d9e204d9a7cf7a708821a">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Returns the number of nodes in the folding set. <a href="#a91b6fe3aff6d9e204d9a7cf7a708821a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba05916ea38a4fbd696cf502f41fbbcf">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - Returns true if there are no nodes in the folding set. <a href="#aba05916ea38a4fbd696cf502f41fbbcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; T &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b9814a604596b9ff9c40267ccd719c1">Set</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VectorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af95f1eb7e65da21475a31a08fc7e7700">Vector</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetvector">FoldingSetVector</a> - This template class combines a <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> and a vector to provide the interface of <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> but with deterministic iteration order based on the insertion order.</p>


<p>T must be a subclass of <a href="/web-llvm/docs/api/namespaces/llvm/#a368e3de8ea854f34bc97c21a64d6a164">FoldingSetNode</a> and implement a Profile function.</p>


<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aa1c91f420927e79019ab5c928b8cdb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FoldingSetVector&lt; T, VectorT &gt;::const_iterator =  pointee_iterator&lt;typename VectorT::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### iterator {#aa66424d10ca761f0b58aa065572ddb64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FoldingSetVector&lt; T, VectorT &gt;::iterator =  pointee_iterator&lt;typename VectorT::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FoldingSetVector() {#ad32230ee6b90ad3fac2d91a77b92979b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FoldingSetVector&lt; T, VectorT &gt;::FoldingSetVector (unsigned Log2InitSize=6)</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a00d59558d21aac5b0ce9771d976d5f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::FoldingSetVector&lt; T, VectorT &gt;::begin ()</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### begin() {#af83466d43905687f2864cf1d70d43afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::FoldingSetVector&lt; T, VectorT &gt;::begin ()</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### clear() {#aa7faffd79c0debbc3093fa5bee2ec473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FoldingSetVector&lt; T, VectorT &gt;::clear ()</td>
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

<p>clear - Remove all nodes from the folding set.</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### empty() {#aba05916ea38a4fbd696cf502f41fbbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FoldingSetVector&lt; T, VectorT &gt;::empty ()</td>
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

<p>empty - Returns true if there are no nodes in the folding set.</p>

<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### end() {#a0556825383a064ddb0b917d3651563f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::FoldingSetVector&lt; T, VectorT &gt;::end ()</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### end() {#a5a343dfe063144e63828e1246b9f3286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::FoldingSetVector&lt; T, VectorT &gt;::end ()</td>
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



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### FindNodeOrInsertPos() {#a8be7737b2b63e63c29750b3db01856e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::FoldingSetVector&lt; T, VectorT &gt;::FindNodeOrInsertPos (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, void *&amp; InsertPos)</td>
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

<p>FindNodeOrInsertPos - Look up the node specified by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>If it exists, return it. If not, return the insertion token that will make insertion faster.</p>


<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### GetOrInsertNode() {#a1af63f402c97ccdf0d2d3709c3c86f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::FoldingSetVector&lt; T, VectorT &gt;::GetOrInsertNode (T * N)</td>
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

<p>GetOrInsertNode - If there is an existing simple <a href="/web-llvm/docs/api/classes/node">Node</a> exactly equal to the specified node, return it.</p>


<p>Otherwise, insert 'N' and return it instead.</p>


<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### InsertNode() {#af4ea13f6943a665055f541c7abda81b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FoldingSetVector&lt; T, VectorT &gt;::InsertNode (T * N, void * InsertPos)</td>
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

<p>InsertNode - Insert the specified node into the folding set, knowing that it is not already in the folding set.</p>


<p>InsertPos must be obtained from FindNodeOrInsertPos.</p>


<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### InsertNode() {#a7c5a4127393e04cb5eb5c17fe83a3a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FoldingSetVector&lt; T, VectorT &gt;::InsertNode (T * N)</td>
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

<p>InsertNode - Insert the specified node into the folding set, knowing that it is not already in the folding set.</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### size() {#a91b6fe3aff6d9e204d9a7cf7a708821a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FoldingSetVector&lt; T, VectorT &gt;::size ()</td>
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

<p>size - Returns the number of nodes in the folding set.</p>

<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Set {#a0b9814a604596b9ff9c40267ccd719c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;T&gt; llvm::FoldingSetVector&lt; T, VectorT &gt;::Set</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### Vector {#af95f1eb7e65da21475a31a08fc7e7700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class VectorT = SmallVector&lt;T*, 8&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorT llvm::FoldingSetVector&lt; T, VectorT &gt;::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
