---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache/blockcacheentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockCacheEntry` Struct Reference

<p>This is all of the cached information for one basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::BlockCacheEntry { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae402f564c89c2bc040f147cbb765ef9c">LatticeElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb76289fadcee12011c7344c252cc5b">OverDefined</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-lazyvalueinfo-cpp-/#a02e7f45327831f3330e6b7cba99a0bfb">NonNullPointerSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b08ea757464142ce6256067ade7835">NonNullPointers</a></td>
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

<p>This is all of the cached information for one basic block.</p>


<p>It contains the per-value lattice elements, as well as a separate set for overdefined values to reduce memory usage. Additionally pointers dereferenced in the block are cached for nullability queries.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### LatticeElements {#ae402f564c89c2bc040f147cbb765ef9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;AssertingVH&lt;Value&gt;, ValueLatticeElement, 4&gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::BlockCacheEntry::LatticeElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### NonNullPointers {#a75b08ea757464142ce6256067ade7835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;NonNullPointerSet&gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::BlockCacheEntry::NonNullPointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### OverDefined {#a8eb76289fadcee12011c7344c252cc5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;AssertingVH&lt;Value&gt;, 4&gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::BlockCacheEntry::OverDefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
