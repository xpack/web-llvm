---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/span-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `span_t` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct span_t { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85527ad364915bcb39b7d421524d0bd6">free_list</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free list. <a href="#a85527ad364915bcb39b7d421524d0bd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee7892ce3c5d8342af193f1824a5098">block_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total block count of size class. <a href="#a7ee7892ce3c5d8342af193f1824a5098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a977febdd2e9ae15bcf66f83d0cf817">size_class</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size class. <a href="#a5a977febdd2e9ae15bcf66f83d0cf817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af093d9cb1719d72c20f96a9b467590f5">free_list_limit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of last block initialized in free list. <a href="#af093d9cb1719d72c20f96a9b467590f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4fa6f8f0e7baff0d6a7a96df58bcca">used_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of used blocks remaining when in partial state. <a href="#abf4fa6f8f0e7baff0d6a7a96df58bcca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">atomicptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b0340927d02f0c7c4486f01c31358e">free_list_deferred</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deferred free list. <a href="#a22b0340927d02f0c7c4486f01c31358e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad842dbc76a30fb5beee77a2d773a3e91">list_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of deferred free list, or list of spans when part of a cache list. <a href="#ad842dbc76a30fb5beee77a2d773a3e91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97df83853dc6ddf7e0114691b15edb49">block_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of a block. <a href="#a97df83853dc6ddf7e0114691b15edb49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de89d484559557bb639a2703c750b17">flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags and counters. <a href="#a4de89d484559557bb639a2703c750b17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans. <a href="#ae77d9a2cdd2a2fd46e3b27739d6c88cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32dc4254a995d8ba3ab99376c9ad4d0">total_spans</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total span counter for master spans. <a href="#af32dc4254a995d8ba3ab99376c9ad4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d2ba73260e7e5dbe98c76436888c5f">offset_from_master</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset from master span for subspans. <a href="#a07d2ba73260e7e5dbe98c76436888c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">atomic32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aecbd1cbb36425fddd53125ea1a84c7">remaining_spans</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remaining span counter, for master spans. <a href="#a4aecbd1cbb36425fddd53125ea1a84c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13753de75bc52a5b8a1a9532083c9ba4">align_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Alignment offset. <a href="#a13753de75bc52a5b8a1a9532083c9ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345270ce5d1e5e112b45cfde43f37da0">heap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owning heap. <a href="#a345270ce5d1e5e112b45cfde43f37da0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62e0e77eb38ebff4443eb5db3ccd45c">next</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next span. <a href="#ac62e0e77eb38ebff4443eb5db3ccd45c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386f776cc556d33534161ece5083e4de">prev</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Previous span. <a href="#a386f776cc556d33534161ece5083e4de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### align\_offset {#a13753de75bc52a5b8a1a9532083c9ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::align_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Alignment offset.</p>

<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### block\_count {#a7ee7892ce3c5d8342af193f1824a5098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::block_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total block count of size class.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a>.</p>

</div>
</div>

### block\_size {#a97df83853dc6ddf7e0114691b15edb49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::block_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of a block.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>.</p>

</div>
</div>

### flags {#a4de89d484559557bb639a2703c750b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags and counters.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### free\_list {#a85527ad364915bcb39b7d421524d0bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* span_t::free_list</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free list.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### free\_list\_deferred {#a22b0340927d02f0c7c4486f01c31358e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomicptr_t span_t::free_list_deferred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deferred free list.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### free\_list\_limit {#af093d9cb1719d72c20f96a9b467590f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::free_list_limit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of last block initialized in free list.</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### heap {#a345270ce5d1e5e112b45cfde43f37da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* span_t::heap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owning heap.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### list\_size {#ad842dbc76a30fb5beee77a2d773a3e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::list_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of deferred free list, or list of spans when part of a cache list.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### next {#ac62e0e77eb38ebff4443eb5db3ccd45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* span_t::next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next span.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a49d22808308e599742e41ef2d4671cfa">_rpmalloc_span_double_link_list_pop_head</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### offset\_from\_master {#a07d2ba73260e7e5dbe98c76436888c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::offset_from_master</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset from master span for subspans.</p>

<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### prev {#a386f776cc556d33534161ece5083e4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* span_t::prev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Previous span.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>.</p>

</div>
</div>

### remaining\_spans {#a4aecbd1cbb36425fddd53125ea1a84c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomic32_t span_t::remaining_spans</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remaining span counter, for master spans.</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### size\_class {#a5a977febdd2e9ae15bcf66f83d0cf817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::size_class</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size class.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### span\_count {#ae77d9a2cdd2a2fd46e3b27739d6c88cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::span_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### total\_spans {#af32dc4254a995d8ba3ab99376c9ad4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::total_spans</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total span counter for master spans.</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### used\_count {#abf4fa6f8f0e7baff0d6a7a96df58bcca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t span_t::used_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of used blocks remaining when in partial state.</p>

<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

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
