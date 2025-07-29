---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pagedvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PagedVector` Class Template

<p>A vector that allocates memory in pages. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;
class llvm::PagedVector&lt;T, PageSize&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">llvm/ADT/PagedVector.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf970444c92dc8b818d421f62a175ce8">value_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8d0d4219201ac3a28aa03fde24f19651">PagedVector</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a8d0d4219201ac3a28aa03fde24f19651">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a109b0b303de1667f3caebc8e2452b192">PagedVector</a> (BumpPtrAllocator *A)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a88305bcd1ac1e94ddc8b9a1378e5296b">PagedVector</a> (const PagedVector &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ace137743164c650abe6140575d21f4c0">PagedVector</a> (PagedVector &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5a3013afefe003311f35dc59ba71eef6">~PagedVector</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a179fd4f598894d58ef90b5ce535c35d4">operator=</a> (const PagedVector &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f857b4da79647992f8332c17853eb19">operator=</a> (PagedVector &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63e3ad7aaf150227878cef2db7eb45df">operator[]</a> (size_t Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up an element at position <span class="doxyComputerOutput">Index</span>. <a href="#a63e3ad7aaf150227878cef2db7eb45df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae352f14abff61be868ca4a4f2246dcd4">capacity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the capacity of the vector. <a href="#ae352f14abff61be868ca4a4f2246dcd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2184ad1cb218226d0837ffa1c1abf4a3">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the vector. <a href="#a2184ad1cb218226d0837ffa1c1abf4a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a84c9c19fca5d62dc0c891cdc7153ae15">resize</a> (size_t NewSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resize the vector. <a href="#a84c9c19fca5d62dc0c891cdc7153ae15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15e89fa9933cfb26cb2644112b0f6d7d">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af58646d64130955cca8107daeebdb8d8">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the vector, i.e. <a href="#af58646d64130955cca8107daeebdb8d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pagedvector/materializediterator">MaterializedIterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a08262e5983c976ef07d9b9dbe139c1">materialized_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterators over the materialized elements of the vector. <a href="#a7a08262e5983c976ef07d9b9dbe139c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pagedvector/materializediterator">MaterializedIterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c1044d785d4724b99dfb762a68009ca">materialized_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad593ff492a93b297b8196ec339d78867">materialized</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pagedvector/materializediterator">MaterializedIterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8e12595752d313217ae091be44ca41e">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual number of elements in the vector which can be accessed. <a href="#ac8e12595752d313217ae091be44ca41e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T *, 0 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b0cb6a80c7244984f7d127d8c4f3ec8">PageToDataPtrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The position of the initial element of the page in the Data vector. <a href="#a2b0cb6a80c7244984f7d127d8c4f3ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> *, 1, bool &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55514676a6e47c76dbe522633ce84d27">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Actual page data. <a href="#a55514676a6e47c76dbe522633ce84d27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A vector that allocates memory in pages.</p>


<p>Order is kept, but memory is allocated only when one element of the page is accessed. This introduces a level of indirection, but it is useful when you have a sparsely initialised vector where the full size is allocated upfront.</p>


<p>As a side effect the elements are initialised later than in a normal vector. On the first access to one of the elements of a given page, all the elements of the page are initialised. This also means that the elements of the page are initialised beyond the size of the vector.</p>


<p>Similarly on destruction the elements are destroyed only when the page is not needed anymore, delaying invoking the destructor of the elements.</p>


<p>Notice that this has iterators only on materialized elements. This is deliberately done under the assumption you would dereference the elements while iterating, therefore materialising them and losing the gains in terms of memory usage this container provides. If you have such a use case, you probably want to use a normal std::vector or a <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### value\_type {#aaf970444c92dc8b818d421f62a175ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PagedVector&lt; T, PageSize &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PagedVector() {#a8d0d4219201ac3a28aa03fde24f19651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector ()</td>
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

<p>Default constructor.</p>


<p>We build our own allocator and mark it as such with <span class="doxyComputerOutput">true</span> in the second pair element.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pagedvector/materializediterator/#ad4775618f78009529c1512a353a8e156">llvm::PagedVector&lt; T, PageSize &gt;::MaterializedIterator::MaterializedIterator</a>, <a href="#a179fd4f598894d58ef90b5ce535c35d4">llvm::PagedVector&lt; T, PageSize &gt;::operator=</a>, <a href="#a3f857b4da79647992f8332c17853eb19">llvm::PagedVector&lt; T, PageSize &gt;::operator=</a>, <a href="#a88305bcd1ac1e94ddc8b9a1378e5296b">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a> and <a href="#ace137743164c650abe6140575d21f4c0">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>.</p>

</div>
</div>

### PagedVector() {#a109b0b303de1667f3caebc8e2452b192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> * A)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### PagedVector() {#a88305bcd1ac1e94ddc8b9a1378e5296b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="#a8d0d4219201ac3a28aa03fde24f19651">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>.</p>

</div>
</div>

### PagedVector() {#ace137743164c650abe6140575d21f4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector (<a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="#a8d0d4219201ac3a28aa03fde24f19651">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PagedVector() {#a5a3013afefe003311f35dc59ba71eef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PagedVector&lt; T, PageSize &gt;::~PagedVector ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="#af58646d64130955cca8107daeebdb8d8">llvm::PagedVector&lt; T, PageSize &gt;::clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a63e3ad7aaf150227878cef2db7eb45df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::PagedVector&lt; T, PageSize &gt;::operator[] (size_t Index)</td>
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

<p>Look up an element at position <span class="doxyComputerOutput">Index</span>.</p>


<p>If the associated page is not filled, it will be filled with default constructed elements.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### operator=() {#a179fd4f598894d58ef90b5ce535c35d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PagedVector &amp; llvm::PagedVector&lt; T, PageSize &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="#a8d0d4219201ac3a28aa03fde24f19651">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>.</p>

</div>
</div>

### operator=() {#a3f857b4da79647992f8332c17853eb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PagedVector &amp; llvm::PagedVector&lt; T, PageSize &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/pagedvector">PagedVector</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="#a8d0d4219201ac3a28aa03fde24f19651">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### capacity() {#ae352f14abff61be868ca4a4f2246dcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::PagedVector&lt; T, PageSize &gt;::capacity ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the capacity of the vector.</p>


<p>I.e. the maximum size it can be expanded to with the resize method without allocating more pages.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>.</p>

</div>
</div>

### clear() {#af58646d64130955cca8107daeebdb8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PagedVector&lt; T, PageSize &gt;::clear ()</td>
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

<p>Clear the vector, i.e.</p>


<p>clear the allocated pages, the whole page lookup index and reset the size.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a84c9c19fca5d62dc0c891cdc7153ae15">llvm::PagedVector&lt; T, PageSize &gt;::resize</a> and <a href="#a5a3013afefe003311f35dc59ba71eef6">llvm::PagedVector&lt; T, PageSize &gt;::~PagedVector</a>.</p>

</div>
</div>

### empty() {#a15e89fa9933cfb26cb2644112b0f6d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PagedVector&lt; T, PageSize &gt;::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

### materialized() {#ad593ff492a93b297b8196ec339d78867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::iterator_range&lt; MaterializedIterator &gt; llvm::PagedVector&lt; T, PageSize &gt;::materialized ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>References <a href="#a7a08262e5983c976ef07d9b9dbe139c1">llvm::PagedVector&lt; T, PageSize &gt;::materialized_begin</a> and <a href="#a0c1044d785d4724b99dfb762a68009ca">llvm::PagedVector&lt; T, PageSize &gt;::materialized_end</a>.</p>

</div>
</div>

### materialized\_begin() {#a7a08262e5983c976ef07d9b9dbe139c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializedIterator llvm::PagedVector&lt; T, PageSize &gt;::materialized_begin ()</td>
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

<p>Iterators over the materialized elements of the vector.</p>


<p>This includes all the elements belonging to allocated pages, even if they have not been accessed yet. It's enough to access one element of a page to materialize all the elements of the page.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>.</p>


<p>Referenced by <a href="#ad593ff492a93b297b8196ec339d78867">llvm::PagedVector&lt; T, PageSize &gt;::materialized</a>.</p>

</div>
</div>

### materialized\_end() {#a0c1044d785d4724b99dfb762a68009ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializedIterator llvm::PagedVector&lt; T, PageSize &gt;::materialized_end ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>Referenced by <a href="#ad593ff492a93b297b8196ec339d78867">llvm::PagedVector&lt; T, PageSize &gt;::materialized</a>.</p>

</div>
</div>

### resize() {#a84c9c19fca5d62dc0c891cdc7153ae15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PagedVector&lt; T, PageSize &gt;::resize (size_t NewSize)</td>
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

<p>Resize the vector.</p>


<p>Notice that the constructor of the elements will not be invoked until an element of a given page is accessed, at which point all the elements of the page will be constructed.</p>


<p>If the new size is smaller than the current size, the elements of the pages that are not needed anymore will be destroyed, however, elements of the last page will not be destroyed.</p>


<p>For these reason the usage of this vector is discouraged if you rely on the construction / destructor of the elements to be invoked.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>


<p>References <a href="#af58646d64130955cca8107daeebdb8d8">llvm::PagedVector&lt; T, PageSize &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### size() {#a2184ad1cb218226d0837ffa1c1abf4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::PagedVector&lt; T, PageSize &gt;::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size of the vector.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a55514676a6e47c76dbe522633ce84d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;BumpPtrAllocator *, 1, bool&gt; llvm::PagedVector&lt; T, PageSize &gt;::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Actual page data.</p>


<p>All the page elements are allocated on the first access of any of the elements of the page. Elements are default constructed and elements of the page are stored contiguously.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

### PageToDataPtrs {#a2b0cb6a80c7244984f7d127d8c4f3ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;T *, 0&gt; llvm::PagedVector&lt; T, PageSize &gt;::PageToDataPtrs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The position of the initial element of the page in the Data vector.</p>


<p>Pages are allocated contiguously in the Data vector.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

### Size {#ac8e12595752d313217ae091be44ca41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t PageSize = 1024 / sizeof(T)&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::PagedVector&lt; T, PageSize &gt;::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual number of elements in the vector which can be accessed.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pagedvector-h">PagedVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
