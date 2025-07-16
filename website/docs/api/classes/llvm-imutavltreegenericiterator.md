---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/imutavltreegenericiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImutAVLTreeGenericIterator` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename ImutInfo&gt;
class llvm::ImutAVLTreeGenericIterator&lt;ImutInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">llvm/ADT/ImmutableSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fed3a782fa293558d16a6e73ce20969">iterator_category</a> = std::bidirectional_iterator_tag</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4437ba0e5465ebf6e9432ee0ed7499d1">value_type</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a583da721f7a5a172ecdd7e17114813">difference_type</a> = std::ptrdiff_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2dd635524e77808e8343456a6258fafb">pointer</a> = <a href="#a4437ba0e5465ebf6e9432ee0ed7499d1">value_type</a> *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae96c8417f8901cf3cd117e27af6b1c9c">reference</a> = <a href="#a4437ba0e5465ebf6e9432ee0ed7499d1">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7d22e678cfa88dd42ece039aa75befa">TreeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">VisitFlag { <a href="#ac7c944de94b3b915203290c0660ab74d">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1694985b790314fbae49b0e97c76daa9">ImutAVLTreeGenericIterator</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa5ab9554a60d6db8efbc7745500aa9a8">ImutAVLTreeGenericIterator</a> (const TreeTy *Root)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab7d22e678cfa88dd42ece039aa75befa">TreeTy</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adee0eed5344f18b3cd9222b79d33e1c6">operator*</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab7d22e678cfa88dd42ece039aa75befa">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adef5abdab3b9de163a68433d17499870">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5eaad849b977c1dcb82d1578f67f3bff">operator==</a> (const ImutAVLTreeGenericIterator &amp;x) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af970d2048e852f82a71cc468fb939e72">operator!=</a> (const ImutAVLTreeGenericIterator &amp;x) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltreegenericiterator">ImutAVLTreeGenericIterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe6b2bdcce6ec1b3952d4fab3a45c440">operator++</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltreegenericiterator">ImutAVLTreeGenericIterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac348449f0da371caaaab8b29076a4bf0">operator--</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af02e88e7b24681761d9e407019e68045">getVisitState</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab040d92d8cae59375137a32b06fe7e91">atEnd</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6176161d405b503e7bb0ef572ab243a">atBeginning</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46b083af091f14850716b2d42dec4ff2">skipToParent</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uintptr_t, 20 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac03173304f4e8bf0f2bfc4b2ac4b5ca">stack</a></td>
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


<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### difference\_type {#a5a583da721f7a5a172ecdd7e17114813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::difference_type =  std::ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### iterator\_category {#a6fed3a782fa293558d16a6e73ce20969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::iterator_category =  std::bidirectional_iterator_tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### pointer {#a2dd635524e77808e8343456a6258fafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::pointer =  value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### reference {#ae96c8417f8901cf3cd117e27af6b1c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::reference =  value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### TreeTy {#ab7d22e678cfa88dd42ece039aa75befa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::TreeTy =  ImutAVLTree&lt;ImutInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type {#a4437ba0e5465ebf6e9432ee0ed7499d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::value_type =  ImutAVLTree&lt;ImutInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### VisitFlag {#ac7c944de94b3b915203290c0660ab74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ImutAVLTreeGenericIterator::VisitFlag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VisitedNone<a id="ac7c944de94b3b915203290c0660ab74da6e52e64f41fdf005955b9bc70bbd9b98"></a></td>
<td class="doxyEnumItemDescription"> (=0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VisitedLeft<a id="ac7c944de94b3b915203290c0660ab74dad67afe37f3183875821b43d8157e0d81"></a></td>
<td class="doxyEnumItemDescription"> (=0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VisitedRight<a id="ac7c944de94b3b915203290c0660ab74da1aa019b1493a573cf32ec5b369932dcd"></a></td>
<td class="doxyEnumItemDescription"> (=0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Flags<a id="ac7c944de94b3b915203290c0660ab74da9236fddb1a6fc722ba31037c7e3cd06b"></a></td>
<td class="doxyEnumItemDescription"> (=0x3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImutAVLTreeGenericIterator() {#a1694985b790314fbae49b0e97c76daa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator ()</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Referenced by <a href="#af970d2048e852f82a71cc468fb939e72">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator!=</a>, <a href="#afe6b2bdcce6ec1b3952d4fab3a45c440">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator++</a>, <a href="#ac348449f0da371caaaab8b29076a4bf0">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator--</a> and <a href="#a5eaad849b977c1dcb82d1578f67f3bff">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator==</a>.</p>

</div>
</div>

### ImutAVLTreeGenericIterator() {#aa5ab9554a60d6db8efbc7745500aa9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab7d22e678cfa88dd42ece039aa75befa">TreeTy</a> * Root)</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#ac348449f0da371caaaab8b29076a4bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImutAVLTreeGenericIterator &amp; llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator-- ()</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac7c944de94b3b915203290c0660ab74da9236fddb1a6fc722ba31037c7e3cd06b">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#ab14acafb70df3766a8938116c87d7032">llvm::ImutAVLTree&lt; ImutInfo &gt;::getLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#acb12f840f94c2a37afb309dc6ebec48b">llvm::ImutAVLTree&lt; ImutInfo &gt;::getRight</a>, <a href="#af02e88e7b24681761d9e407019e68045">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::getVisitState</a>, <a href="#a1694985b790314fbae49b0e97c76daa9">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ac7c944de94b3b915203290c0660ab74dad67afe37f3183875821b43d8157e0d81">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedLeft</a>, <a href="#ac7c944de94b3b915203290c0660ab74da6e52e64f41fdf005955b9bc70bbd9b98">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedNone</a> and <a href="#ac7c944de94b3b915203290c0660ab74da1aa019b1493a573cf32ec5b369932dcd">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedRight</a>.</p>

</div>
</div>

### operator-&gt;() {#adef5abdab3b9de163a68433d17499870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator-&gt; ()</td>
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



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### operator!=() {#af970d2048e852f82a71cc468fb939e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/imutavltreegenericiterator">ImutAVLTreeGenericIterator</a> &amp; x)</td>
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



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#a1694985b790314fbae49b0e97c76daa9">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator</a>.</p>

</div>
</div>

### operator\*() {#adee0eed5344f18b3cd9222b79d33e1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy &amp; llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator* ()</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac7c944de94b3b915203290c0660ab74da9236fddb1a6fc722ba31037c7e3cd06b">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::Flags</a>.</p>

</div>
</div>

### operator++() {#afe6b2bdcce6ec1b3952d4fab3a45c440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImutAVLTreeGenericIterator &amp; llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator++ ()</td>
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



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac7c944de94b3b915203290c0660ab74da9236fddb1a6fc722ba31037c7e3cd06b">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#ab14acafb70df3766a8938116c87d7032">llvm::ImutAVLTree&lt; ImutInfo &gt;::getLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#acb12f840f94c2a37afb309dc6ebec48b">llvm::ImutAVLTree&lt; ImutInfo &gt;::getRight</a>, <a href="#af02e88e7b24681761d9e407019e68045">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::getVisitState</a>, <a href="#a1694985b790314fbae49b0e97c76daa9">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46b083af091f14850716b2d42dec4ff2">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::skipToParent</a>, <a href="#ac7c944de94b3b915203290c0660ab74dad67afe37f3183875821b43d8157e0d81">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedLeft</a>, <a href="#ac7c944de94b3b915203290c0660ab74da6e52e64f41fdf005955b9bc70bbd9b98">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedNone</a> and <a href="#ac7c944de94b3b915203290c0660ab74da1aa019b1493a573cf32ec5b369932dcd">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedRight</a>.</p>

</div>
</div>

### operator==() {#a5eaad849b977c1dcb82d1578f67f3bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/imutavltreegenericiterator">ImutAVLTreeGenericIterator</a> &amp; x)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#a1694985b790314fbae49b0e97c76daa9">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::ImutAVLTreeGenericIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### atBeginning() {#af6176161d405b503e7bb0ef572ab243a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::atBeginning ()</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#af02e88e7b24681761d9e407019e68045">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::getVisitState</a> and <a href="#ac7c944de94b3b915203290c0660ab74da6e52e64f41fdf005955b9bc70bbd9b98">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedNone</a>.</p>

</div>
</div>

### atEnd() {#ab040d92d8cae59375137a32b06fe7e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::atEnd ()</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### getVisitState() {#af02e88e7b24681761d9e407019e68045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::getVisitState ()</td>
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



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac7c944de94b3b915203290c0660ab74da9236fddb1a6fc722ba31037c7e3cd06b">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::Flags</a>.</p>


<p>Referenced by <a href="#af6176161d405b503e7bb0ef572ab243a">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::atBeginning</a>, <a href="#afe6b2bdcce6ec1b3952d4fab3a45c440">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator++</a>, <a href="#ac348449f0da371caaaab8b29076a4bf0">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator--</a> and <a href="#a46b083af091f14850716b2d42dec4ff2">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::skipToParent</a>.</p>

</div>
</div>

### skipToParent() {#a46b083af091f14850716b2d42dec4ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::skipToParent ()</td>
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



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af02e88e7b24681761d9e407019e68045">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::getVisitState</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ac7c944de94b3b915203290c0660ab74dad67afe37f3183875821b43d8157e0d81">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedLeft</a>, <a href="#ac7c944de94b3b915203290c0660ab74da6e52e64f41fdf005955b9bc70bbd9b98">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedNone</a> and <a href="#ac7c944de94b3b915203290c0660ab74da1aa019b1493a573cf32ec5b369932dcd">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::VisitedRight</a>.</p>


<p>Referenced by <a href="#afe6b2bdcce6ec1b3952d4fab3a45c440">llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### stack {#aac03173304f4e8bf0f2bfc4b2ac4b5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uintptr_t,20&gt; llvm::ImutAVLTreeGenericIterator&lt; ImutInfo &gt;::stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
