---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/intervalmapimpl/nodesizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NodeSizer` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValT&gt;
struct llvm::IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72b711e1d29c395d89be2e2a7a21f7a1">LeafBase</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase</a>&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8cd3b17214907efcbfe21077a4d57f05">Allocator</a> = <a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, char, <a href="#a20e25986129ca221c7471ea0d5e9a34bab4c056134ee40aa410405f64fe7364d1">AllocBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl/#aacf91952cde5989ab8c6b38b501021c1a22be8a9f335245b5ce05d2a3d35a9221">CacheLineBytes</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a8cd3b17214907efcbfe21077a4d57f05">Allocator</a> - The recycling allocator used for both branch and leaf nodes. <a href="#a8cd3b17214907efcbfe21077a4d57f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a266a2537ceada49bc161274684e88698">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a20e25986129ca221c7471ea0d5e9a34b">...</a> }</td>
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


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Allocator {#a8cd3b17214907efcbfe21077a4d57f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMapImpl::NodeSizer&lt; KeyT, ValT &gt;::Allocator = 
      RecyclingAllocator&lt;BumpPtrAllocator, char, AllocBytes, CacheLineBytes&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a8cd3b17214907efcbfe21077a4d57f05">Allocator</a> - The recycling allocator used for both branch and leaf nodes.</p>


<p>This typedef is very likely to be identical for all IntervalMaps with reasonably sized entries, so the same allocator can be shared among different kinds of maps.</p>


<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### LeafBase {#a72b711e1d29c395d89be2e2a7a21f7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMapImpl::NodeSizer&lt; KeyT, ValT &gt;::LeafBase =  NodeBase&lt;std::pair&lt;KeyT, KeyT&gt;, ValT, LeafSize&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a266a2537ceada49bc161274684e88698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">DesiredLeafSize<a id="a266a2537ceada49bc161274684e88698a4b7f7a78f45c7857075a626ec568aaf2"></a></td>
<td class="doxyEnumItemDescription">
 (= DesiredNodeBytes /
      static_cast&lt;unsigned&gt;(2*sizeof(KeyT)+sizeof(ValT)))
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MinLeafSize<a id="a266a2537ceada49bc161274684e88698a564c0636d62bb13206f747e41d196b0c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### anonymous enum  {#a20e25986129ca221c7471ea0d5e9a34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">AllocBytes<a id="a20e25986129ca221c7471ea0d5e9a34bab4c056134ee40aa410405f64fe7364d1"></a></td>
<td class="doxyEnumItemDescription"> (= (sizeof(LeafBase) + CacheLineBytes-1) &amp; ~(CacheLineBytes-1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchSize<a id="a20e25986129ca221c7471ea0d5e9a34ba79ed6f627e6df1b1833064f6ead08c97"></a></td>
<td class="doxyEnumItemDescription">
 (= AllocBytes /
      static_cast&lt;unsigned&gt;(sizeof(KeyT) + sizeof(void*)))
</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
