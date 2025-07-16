---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/heap-size-class-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `heap_size_class_t` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct heap_size_class_t { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac411b0f198d4e31569fc30ca2c174f65">free_list</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free list of active span. <a href="#ac411b0f198d4e31569fc30ca2c174f65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af829c49d9fc4d933c14113ba0d694e7c">partial_span</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Double linked list of partially used spans with free blocks. <a href="#af829c49d9fc4d933c14113ba0d694e7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cb3beffa763418cb7c8e89ff257b8e">cache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Early level cache of fully free spans. <a href="#a72cb3beffa763418cb7c8e89ff257b8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### cache {#a72cb3beffa763418cb7c8e89ff257b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* heap_size_class_t::cache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Early level cache of fully free spans.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### free\_list {#ac411b0f198d4e31569fc30ca2c174f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* heap_size_class_t::free_list</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free list of active span.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### partial\_span {#af829c49d9fc4d933c14113ba0d694e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* heap_size_class_t::partial_span</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Double linked list of partially used spans with free blocks.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
