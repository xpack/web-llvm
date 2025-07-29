---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallsetiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SmallSetIterator` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> - This class implements a <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">const_iterator</a> for <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> by delegating to the underlying <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> or Set iterators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, unsigned N, typename C&gt;
class llvm::SmallSetIterator&lt;T, N, C&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a305d33d1e3aed51a21c0583d6efd68a0">SetIterTy</a> = typename std::set&lt; T, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a685b83e8d9c6a651d54e31c51b6f861b">VecIterTy</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac74b70e68e69831dcba409e2339dcc23">SelfTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a>&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a907370df85ecd68f1cc83c121e192557">SmallSetIterator</a> (SetIterTy SetIter)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad90691b19097c1ecda1672715a0fdee9">SmallSetIterator</a> (VecIterTy VecIter)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aaf28161e9ef1de0dae654eff107388d3">SmallSetIterator</a> (const SmallSetIterator &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae0fb6c9159f05b70f26289590949ed57">SmallSetIterator</a> (SmallSetIterator &amp;&amp;Other)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ace72f5ecbaaf2a945de3baf9c0ddfed8">~SmallSetIterator</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94924161b0063ff3f6c1ebed541decf3">operator=</a> (const SmallSetIterator &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ed5c236d864efe097586a9ef9a01daa">operator=</a> (SmallSetIterator &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a73fd247d33df715b6ae0cd733607ae">operator==</a> (const SmallSetIterator &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e6d5c1ad80230988fa739425cac7f8a">operator++</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd07bc46d991e12648e0effefcaddf95">operator*</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetIterTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">SetIter</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VecIterTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">VecIter</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">llvm::SmallSetIterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28187311a0d0948fd878ad7e5ed5ff44"></a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterators to the parts of the <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> containing the data. <a href="#a28187311a0d0948fd878ad7e5ed5ff44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N, typename C&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab855c1b16ec2f0e82ac636fc4beeca1b">IsSmall</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> - This class implements a <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">const_iterator</a> for <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> by delegating to the underlying <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> or Set iterators.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SelfTy {#ac74b70e68e69831dcba409e2339dcc23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSetIterator&lt; T, N, C &gt;::SelfTy =  SmallSetIterator&lt;T, N, C&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### SetIterTy {#a305d33d1e3aed51a21c0583d6efd68a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSetIterator&lt; T, N, C &gt;::SetIterTy =  typename std::set&lt;T, C&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### VecIterTy {#a685b83e8d9c6a651d54e31c51b6f861b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallSetIterator&lt; T, N, C &gt;::VecIterTy =  typename SmallVector&lt;T, N&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SmallSetIterator() {#a907370df85ecd68f1cc83c121e192557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator (SetIterTy SetIter)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Reference <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>.</p>


<p>Referenced by <a href="#a2e6d5c1ad80230988fa739425cac7f8a">llvm::SmallSetIterator&lt; T, N, C &gt;::operator++</a>, <a href="#a94924161b0063ff3f6c1ebed541decf3">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a1ed5c236d864efe097586a9ef9a01daa">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a3a73fd247d33df715b6ae0cd733607ae">llvm::SmallSetIterator&lt; T, N, C &gt;::operator==</a>, <a href="#aaf28161e9ef1de0dae654eff107388d3">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ae0fb6c9159f05b70f26289590949ed57">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>.</p>

</div>
</div>

### SmallSetIterator() {#ad90691b19097c1ecda1672715a0fdee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator (VecIterTy VecIter)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### SmallSetIterator() {#aaf28161e9ef1de0dae654eff107388d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp; Other)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### SmallSetIterator() {#ae0fb6c9159f05b70f26289590949ed57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator (<a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp;&amp; Other)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SmallSetIterator() {#ace72f5ecbaaf2a945de3baf9c0ddfed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallSetIterator&lt; T, N, C &gt;::~SmallSetIterator ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#abd07bc46d991e12648e0effefcaddf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::SmallSetIterator&lt; T, N, C &gt;::operator* ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### operator++() {#a2e6d5c1ad80230988fa739425cac7f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetIterator &amp; llvm::SmallSetIterator&lt; T, N, C &gt;::operator++ ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### operator=() {#a94924161b0063ff3f6c1ebed541decf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetIterator &amp; llvm::SmallSetIterator&lt; T, N, C &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp; Other)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### operator=() {#a1ed5c236d864efe097586a9ef9a01daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetIterator &amp; llvm::SmallSetIterator&lt; T, N, C &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp;&amp; Other)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

### operator==() {#a3a73fd247d33df715b6ae0cd733607ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSetIterator&lt; T, N, C &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator">SmallSetIterator</a> &amp; RHS)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a6e4a073fdb4f11d6bffb296bebffcbbb">llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ac6b7bab1529ad66f58af13d6c8e1aebd">llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SetIter {#a6e4a073fdb4f11d6bffb296bebffcbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetIterTy llvm::SmallSetIterator&lt; T, N, C &gt;::SetIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="#abd07bc46d991e12648e0effefcaddf95">llvm::SmallSetIterator&lt; T, N, C &gt;::operator*</a>, <a href="#a2e6d5c1ad80230988fa739425cac7f8a">llvm::SmallSetIterator&lt; T, N, C &gt;::operator++</a>, <a href="#a94924161b0063ff3f6c1ebed541decf3">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a1ed5c236d864efe097586a9ef9a01daa">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a3a73fd247d33df715b6ae0cd733607ae">llvm::SmallSetIterator&lt; T, N, C &gt;::operator==</a>, <a href="#aaf28161e9ef1de0dae654eff107388d3">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>, <a href="#a907370df85ecd68f1cc83c121e192557">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>, <a href="#ae0fb6c9159f05b70f26289590949ed57">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ace72f5ecbaaf2a945de3baf9c0ddfed8">llvm::SmallSetIterator&lt; T, N, C &gt;::~SmallSetIterator</a>.</p>

</div>
</div>

### VecIter {#ac6b7bab1529ad66f58af13d6c8e1aebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VecIterTy llvm::SmallSetIterator&lt; T, N, C &gt;::VecIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>


<p>Referenced by <a href="#abd07bc46d991e12648e0effefcaddf95">llvm::SmallSetIterator&lt; T, N, C &gt;::operator*</a>, <a href="#a2e6d5c1ad80230988fa739425cac7f8a">llvm::SmallSetIterator&lt; T, N, C &gt;::operator++</a>, <a href="#a94924161b0063ff3f6c1ebed541decf3">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a1ed5c236d864efe097586a9ef9a01daa">llvm::SmallSetIterator&lt; T, N, C &gt;::operator=</a>, <a href="#a3a73fd247d33df715b6ae0cd733607ae">llvm::SmallSetIterator&lt; T, N, C &gt;::operator==</a>, <a href="#aaf28161e9ef1de0dae654eff107388d3">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>, <a href="#ae0fb6c9159f05b70f26289590949ed57">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>, <a href="#ad90691b19097c1ecda1672715a0fdee9">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a> and <a href="#ace72f5ecbaaf2a945de3baf9c0ddfed8">llvm::SmallSetIterator&lt; T, N, C &gt;::~SmallSetIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a28187311a0d0948fd878ad7e5ed5ff44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SmallSetIterator llvm::SmallSetIterator&lt; T, N, C &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterators to the parts of the <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a> containing the data.</p>


<p>They are set depending on isSmall.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

### IsSmall {#ab855c1b16ec2f0e82ac636fc4beeca1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N, typename C&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallSetIterator&lt; T, N, C &gt;::IsSmall</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">SmallSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
