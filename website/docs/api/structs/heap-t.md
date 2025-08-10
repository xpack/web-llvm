---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/heap-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `heap_t` Struct



## Declaration

<div class="doxyDeclaration">
struct heap_t { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a436e67271364d132c12f2f5f0d4c79ef">owner_thread</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owning thread ID. <a href="#a436e67271364d132c12f2f5f0d4c79ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-size-class-t">heap_size_class_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f9a96b9071ccb6642894f5a7f56432">size_class</a>[SIZE_CLASS_COUNT]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free lists for each size class. <a href="#a70f9a96b9071ccb6642894f5a7f56432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">atomicptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354c0beb35fd982bc4dbd3783b2dd1ff">span_free_deferred</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of deferred free spans (single linked list) <a href="#a354c0beb35fd982bc4dbd3783b2dd1ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa789c3cdf7e70df144c248d18c5f4c">full_span_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of full spans. <a href="#a6aa789c3cdf7e70df144c248d18c5f4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa549da79e540bdd3e963e294a39f64cf">span_reserve</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapped but unused spans. <a href="#aa549da79e540bdd3e963e294a39f64cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6719c6b21d6c30ce96e404a63cc4bae">span_reserve_master</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Master span for mapped but unused spans. <a href="#aa6719c6b21d6c30ce96e404a63cc4bae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5b27011e1ab5140090f90a75584329">spans_reserved</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of mapped but unused spans. <a href="#a8d5b27011e1ab5140090f90a75584329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">atomic32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fb66e831ef1e0d56d826b1851576eb">child_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Child count. <a href="#a59fb66e831ef1e0d56d826b1851576eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b47a0eacf313fe421d32379a2b942c">next_heap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next heap in id list. <a href="#a74b47a0eacf313fe421d32379a2b942c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e83453c93d1e6de70f6a45044e510d">next_orphan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next heap in orphan list. <a href="#a87e83453c93d1e6de70f6a45044e510d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2342224142317f85fca91614fc973131">id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Heap ID. <a href="#a2342224142317f85fca91614fc973131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ccab5430ace95c471aacf1fab0fcd6">finalize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalization state flag. <a href="#a13ccab5430ace95c471aacf1fab0fcd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348c1835d21f0af4a3776f96bdba64fb">master_heap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Master heap owning the memory pages. <a href="#a348c1835d21f0af4a3776f96bdba64fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### child\_count {#a59fb66e831ef1e0d56d826b1851576eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomic32_t heap_t::child_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Child count.</p>

<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>.</p>

</div>
</div>

### finalize {#a13ccab5430ace95c471aacf1fab0fcd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int heap_t::finalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalization state flag.</p>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### full\_span\_count {#a6aa789c3cdf7e70df144c248d18c5f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t heap_t::full_span_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of full spans.</p>

<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### id {#a2342224142317f85fca91614fc973131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t heap_t::id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Heap ID.</p>

<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>.</p>

</div>
</div>

### master\_heap {#a348c1835d21f0af4a3776f96bdba64fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* heap_t::master_heap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Master heap owning the memory pages.</p>

<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>.</p>

</div>
</div>

### next\_heap {#a74b47a0eacf313fe421d32379a2b942c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* heap_t::next_heap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next heap in id list.</p>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### next\_orphan {#a87e83453c93d1e6de70f6a45044e510d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* heap_t::next_orphan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next heap in orphan list.</p>

<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acef9b939687a94621d82016836da1c91">_rpmalloc_heap_extract_orphan</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a>.</p>

</div>
</div>

### owner\_thread {#a436e67271364d132c12f2f5f0d4c79ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t heap_t::owner_thread</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owning thread ID.</p>

<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>

</div>
</div>

### size\_class {#a70f9a96b9071ccb6642894f5a7f56432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_size_class_t heap_t::size_class[SIZE_CLASS_COUNT]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free lists for each size class.</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### span\_free\_deferred {#a354c0beb35fd982bc4dbd3783b2dd1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomicptr_t heap_t::span_free_deferred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of deferred free spans (single linked list)</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### span\_reserve {#aa549da79e540bdd3e963e294a39f64cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* heap_t::span_reserve</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapped but unused spans.</p>

<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>.</p>

</div>
</div>

### span\_reserve\_master {#aa6719c6b21d6c30ce96e404a63cc4bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* heap_t::span_reserve_master</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Master span for mapped but unused spans.</p>

<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>.</p>

</div>
</div>

### spans\_reserved {#a8d5b27011e1ab5140090f90a75584329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t heap_t::spans_reserved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of mapped but unused spans.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9beacd6369e4fdac1b24268d2515a858">_rpmalloc_heap_reserved_extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
