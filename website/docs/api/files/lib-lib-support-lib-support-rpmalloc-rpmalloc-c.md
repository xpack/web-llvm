---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `rpmalloc.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>"
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;time.h&gt;
#include &lt;unistd.h&gt;
#include &lt;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errno-h">errno.h</a>&gt;
#include &lt;stdint.h&gt;
#include &lt;string.h&gt;
#include &lt;stdatomic.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-t">span_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-cache-t">span_cache_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/span-large-cache-t">span_large_cache_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-size-class-t">heap_size_class_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/heap-t">heap_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/size-class-t">size_class_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/global-cache-t">global_cache_t</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">volatile <a href="#a472f0bf448a2dc3f31c0b79acd70d829">_Atomic</a>(int32_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Atomic access abstraction (since MSVC does not do C11 yet) <a href="#a472f0bf448a2dc3f31c0b79acd70d829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct heap_t <a href="#a75c19bcef00dee4542c1ddab212e29a8">heap_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data types. <a href="#a75c19bcef00dee4542c1ddab212e29a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct span_t <a href="#aa34fdcc23a2d119e7436a33e05ddb665">span_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Span of memory pages. <a href="#aa34fdcc23a2d119e7436a33e05ddb665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="#af2f2ee0936896aa297771a26dec63027">span_list_t</a> <a href="#af2f2ee0936896aa297771a26dec63027">span_list_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Span list. <a href="#af2f2ee0936896aa297771a26dec63027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="#af801d58362e979c2a31744800624dcf9">span_active_t</a> <a href="#af801d58362e979c2a31744800624dcf9">span_active_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Span active data. <a href="#af801d58362e979c2a31744800624dcf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct size_class_t <a href="#a58b8a67689d7a172819769e39f933e66">size_class_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size class definition. <a href="#a58b8a67689d7a172819769e39f933e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct global_cache_t <a href="#abb5df2e5e21b2980d57f68200c97da21">global_cache_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global cache. <a href="#abb5df2e5e21b2980d57f68200c97da21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct span_cache_t <a href="#aece665fc81eaec031382485a4a2ea5b7">span_cache_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct span_large_cache_t <a href="#a8e7b9e9139e15a9faa403425e19b0c13">span_large_cache_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct heap_size_class_t <a href="#a10712f237da38c0bbb00bf9693dd9f6d">heap_size_class_t</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a> (atomic32_t *dst, int32_t val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe9c932f58e2baffed3ea33fd299691">atomic_incr32</a> (atomic32_t *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a> (atomic32_t *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af327588f7260778f453d9a212396e0e0">atomic_add32</a> (atomic32_t *val, int32_t add)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a> (atomic32_t *dst, int32_t val, int32_t ref)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a> (atomic32_t *dst, int32_t val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a> (atomic64_t *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481f7733c3d6469b66e9a746e0afb0e9">atomic_add64</a> (atomic64_t *val, int64_t add)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a> (atomicptr_t *src)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae261e72f93968b03a76ada7a6b150965">atomic_store_ptr</a> (atomicptr_t *dst, void *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a> (atomicptr_t *dst, void *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a> (atomicptr_t *dst, void *val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303f700546874a81e694eda44cc3174d">atomic_cas_ptr</a> (atomicptr_t *dst, void *val, void *ref)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current thread heap. <a href="#afb9f599f45127d8ba79cf413ad35d90c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fast thread ID. <a href="#a84e326ca88dee0bd7ca995727bb52381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a> (heap_t *heap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current thread heap. <a href="#a4a224c6ef987eb60f3e3be98239109ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53adc7f95e9b3fa3e62ba8f50add0ce9">rpmalloc_set_main_thread</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set main thread ID. <a href="#a53adc7f95e9b3fa3e62ba8f50add0ce9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a> (void *address, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Low level memory map/unmap. <a href="#a66c4be5ac967e1374b25eb8ac80f68d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a> (size_t size, size_t *offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map more virtual memory. <a href="#afb297c8e6c20ce017a62ea42b70be194">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a> (void *address, size_t size, size_t offset, size_t release)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmap virtual memory. <a href="#abfbbb8e2f9b086d466fe2898a283c98d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a> (size_t size, size_t *offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default implementation to map new pages to virtual memory. <a href="#a833da3799d95ff35eae22f00833538b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a> (void *address, size_t size, size_t offset, size_t release)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default implementation to unmap pages from virtual memory. <a href="#a693c463bae081b54b0b799e97bf84fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> (span_t *master, span_t *subspan, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declare the span to be a subspan and store distance from master span and span count. <a href="#a91bf3ee061b188b8a650fbac9babef4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a> (size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Use global reserved spans to fulfill a memory map request (reserve size must be checked by caller) <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a> (span_t *master, span_t *reserve, size_t reserve_span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store the given spans as global reserve (must only be called from within new heap allocation, not thread safe) <a href="#aa6d37b325f0f3c68f89cdf681681a09f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a> (span_t **head, span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Span linked list management. <a href="#ac32a750ddf4072d46c28f52b9f3ee018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d22808308e599742e41ef2d4671cfa">_rpmalloc_span_double_link_list_pop_head</a> (span_t **head, span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop head span from double linked list. <a href="#a49d22808308e599742e41ef2d4671cfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a> (span_t **head, span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a span from double linked list. <a href="#aec7913670102d551e3fd60509cd381a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a> (heap_t *heap, span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Span control. <a href="#abdbbc20ab63d76c1709722f3f2305610">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> (heap_t *heap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a> (heap_t *heap, span_t *master, span_t *reserve, size_t reserve_span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store the given spans as reserve in the given heap. <a href="#ae4a00ccf859d64a7519ae121563a56e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a> (heap_t *heap, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Use reserved spans to fulfill a memory map request (reserve size must be checked by caller) <a href="#afaa0ba431359c9bab42909cfc9248b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6780f79fe39d5c99886e27fccaf4133c">_rpmalloc_span_align_count</a> (size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the aligned number of spans to map in based on wanted count, configured mapping granularity and the page size. <a href="#a6780f79fe39d5c99886e27fccaf4133c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a> (span_t *span, size_t total_span_count, size_t span_count, size_t align_offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup a newly mapped span. <a href="#ad5eb163989618d4ea0eff254cdbdd596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a> (span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmap memory pages for the given number of spans (or mark as unused if no partial unmappings) <a href="#a1b31ff8fa0abcdb205dadd8afc026014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> (heap_t *heap, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map an aligned set of spans, taking configured mapping granularity and the page size into account. <a href="#a2a4e560819e42925aaa4494511aae43d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> (heap_t *heap, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map in memory pages for the given number of spans (or use previously reserved pages) <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a> (heap_t *heap, span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the span (used for small or medium allocations) to the heap thread cache. <a href="#a62b31eca2760e37676716c54c5b64947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a> (void **list, void **first_block, void *page_start, void *block_start, uint32_t block_count, uint32_t block_size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a (partial) free list up to next system memory page, while reserving the first block as allocated, returning number of blocks in list. <a href="#addf543f30c5eefc1dded60025c78a816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a> (heap_t *heap, heap_size_class_t *heap_size_class, span_t *span, uint32_t class_idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize an unused span (from cache or mapped) to be new active span, putting the initial free list in heap class free list. <a href="#a64debeb0ce94e6048da7c8fad19b1d31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a> (span_t *span)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a> (span_t *span)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a> (heap_t *heap, size_t iclass, span_t *span, span_t **list_head)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a> (span_t *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global cache. <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a> (heap_t *heap, span_t **single_span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adopt the deferred span cache list, optionally extracting the first single span for immediate re-use. <a href="#af44e92f7ed42c434bd33a0ae98210a3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a> (heap_t *heap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a> (heap_t *heap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f1ac00b9740730f851945218be4d6a">_rpmalloc_heap_thread_cache_extract</a> (heap_t *heap, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the given number of spans from the different cache levels. <a href="#ab3f1ac00b9740730f851945218be4d6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b7049fa43f5ff960119426a26c81fc">_rpmalloc_heap_thread_cache_deferred_extract</a> (heap_t *heap, size_t span_count)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9beacd6369e4fdac1b24268d2515a858">_rpmalloc_heap_reserved_extract</a> (heap_t *heap, size_t span_count)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a> (heap_t *heap, size_t span_count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a span from the global cache. <a href="#abeb50100f90c725f1e16944cd67e9f00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56211c3481cd02195d9bac3c1475cdfb">_rpmalloc_inc_span_statistics</a> (heap_t *heap, size_t span_count, uint32_t class_idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a> (heap_t *heap, heap_size_class_t *heap_size_class, size_t span_count, uint32_t class_idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a span from one of the cache levels (thread cache, reserved, global cache) or fallback to mapping more memory. <a href="#acf65e6242a6d42e38959bac148c7aadc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a> (heap_t *heap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a> (heap_t *heap, int first_class)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a new heap from newly mapped memory pages. <a href="#a648de3a42660a0567102d78aa59ceded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef9b939687a94621d82016836da1c91">_rpmalloc_heap_extract_orphan</a> (heap_t **heap_list)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a> (int first_class)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a new heap, potentially reusing a previously orphaned heap. <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a> (void *heapptr, int first_class, int release_cache)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa378f245dd9ff587c375db42472ac954">_rpmalloc_heap_release_raw</a> (void *heapptr, int release_cache)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375befcec19545c40cb27c22512501bb">_rpmalloc_heap_release_raw_fc</a> (void *heapptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8dde7c610d47213bd49d710016f9476">free_list_pop</a> (void **list)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocation entry points. <a href="#ac8dde7c610d47213bd49d710016f9476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a> (heap_t *heap, heap_size_class_t *heap_size_class, uint32_t class_idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a small/medium sized memory block from the given heap. <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a> (heap_t *heap, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a small sized memory block from the given heap. <a href="#a3dd2306a260dcdc3e852a2898914cbc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> (heap_t *heap, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a medium sized memory block from the given heap. <a href="#ac615e23f8046310bb788e678b486b20a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a> (heap_t *heap, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a large sized memory block from the given heap. <a href="#a8bdabec99c6c3fe43d727ccd713ac112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a> (heap_t *heap, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a huge block by mapping memory pages directly. <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a> (heap_t *heap, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a block of the given size. <a href="#a3bef7e16a625f1968110eaf331332eb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a> (heap_t *heap, size_t alignment, size_t size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a> (span_t *span, void *block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocation entry points. <a href="#a6c1102ef8a3812f1098cad573ea7794e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a> (heap_t *heap, span_t *span)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a> (span_t *span, void *block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Put the block in the deferred free list of the owning span. <a href="#a6cc5147be3d12c47a533a9cd14e36801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a> (span_t *span, void *p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a> (span_t *span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate the given large memory block to the current heap. <a href="#a573fc7baab7be24c6bac115b7f62192f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a> (void *p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate the given block. <a href="#ae324fa158db468143544693dfe539800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> (void *p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocation entry points. <a href="#adc5743a6b15192da5b7e023f85360208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a> (heap_t *heap, void *p, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocate the given block to the given size. <a href="#a9942f9f958830d9f83ecf67b85de3ea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> (heap_t *heap, void *ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a> (size_t iclass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust and optimize the size class properties for the given class. <a href="#a223c890fd871bff9081258f6520fc8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the allocator and setup global data. <a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> (const rpmalloc_config_t *config)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize allocator with given configuration. <a href="#a2ae01990651a75a352409fb1fbf85d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the allocator. <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize thread, assign heap. <a href="#a85a64540090a42380ee6d969ec1897c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a> (int release_caches)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize thread, orphan heap. <a href="#a6e5fc3857f84254caa88503e02bf163c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f18b8696daac522d93e448aadd7cd4b">rpmalloc_is_thread_initialized</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query if allocator is initialized for calling thread. <a href="#a6f18b8696daac522d93e448aadd7cd4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c11aa4589298b607afc250133440e4">rpmalloc_config</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get allocator configuration. <a href="#a43c11aa4589298b607afc250133440e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2727f400656ed5d5857d7a6e1e05b61b">rpmalloc</a> (size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size. <a href="#a2727f400656ed5d5857d7a6e1e05b61b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19186eb24d08ef02b924951abb865b51">rpfree</a> (void *ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free the given memory block. <a href="#a19186eb24d08ef02b924951abb865b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a> (size_t num, size_t size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9643796f1e94fcc804c5c97a7985e9">rprealloc</a> (void *ptr, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocate the given block to at least the given size. <a href="#a8f9643796f1e94fcc804c5c97a7985e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a> (void *ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocate the given block to at least the given size and alignment,. <a href="#a4f191e772a1cda4fb5de7300bac4ea37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a> (size_t alignment, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#a76c23d646a743db9d2576b599b3d01fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae572e25a23de1a9793b4e5b1ec0550b1">rpaligned_calloc</a> (size_t alignment, size_t num, size_t size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61de67ff29b3d0e5d130ac9a7d0d2538">rpmemalign</a> (size_t alignment, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#a61de67ff29b3d0e5d130ac9a7d0d2538">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f35022f9384e2a22ed2b96c00995b2">rpposix_memalign</a> (void **memptr, size_t alignment, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#ae6f35022f9384e2a22ed2b96c00995b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9f597c853963de259b40e985d81113">rpmalloc_usable_size</a> (void *ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the usable size of the given memory block (from given pointer to the end of block) <a href="#a7a9f597c853963de259b40e985d81113">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db2d5852bc3af5ee8bbbfae2db30997">rpmalloc_thread_collect</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform deferred deallocations pending for the calling thread heap. <a href="#a6db2d5852bc3af5ee8bbbfae2db30997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a> (rpmalloc_thread_statistics_t *stats)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get per-thread statistics. <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> (rpmalloc_global_statistics_t *stats)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get global statistics. <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> (void *file)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump all statistics in human readable format to file (should be a FILE*) <a href="#a759e72612fab78b1159ab7129a7f7e86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d0f00495eb8c073a81cd0119fa8429">rpmalloc_linker_reference</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dummy empty function for forcing linker symbol inclusion. <a href="#a70d0f00495eb8c073a81cd0119fa8429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialized flag. <a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc7bcb924cab5e38c3fe65c5d0b4ab0">_rpmalloc_main_thread_id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main thread ID. <a href="#aacc7bcb924cab5e38c3fe65c5d0b4ab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Configuration. <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memory page size. <a href="#a3667b745f7290a10ff5c5a71575533d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shift to divide by page size. <a href="#a9d7ec974d864302bb4f8516859c4b212">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e29d8d18139babda354d5d92d46ca02">_memory_map_granularity</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Granularity at which memory pages are mapped by OS. <a href="#a1e29d8d18139babda354d5d92d46ca02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">_memory_span_map_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans to map in each map call. <a href="#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans to keep reserved in each heap. <a href="#ada12637cd22672d5ad52ceba482b7f5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/size-class-t">size_class_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>[SIZE_CLASS_COUNT]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global size classes. <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9641beb0030ad56b2df025775823b2af">_memory_medium_size_limit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run-time size limit of medium blocks. <a href="#a9641beb0030ad56b2df025775823b2af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static atomic32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42cdefbf9addf1c268ba19e63c60f29">_memory_heap_id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Heap ID counter. <a href="#af42cdefbf9addf1c268ba19e63c60f29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cdf64413eaa3e80f8a1dfe158bd2525">_memory_huge_pages</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Huge page support. <a href="#a4cdf64413eaa3e80f8a1dfe158bd2525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global reserved spans. <a href="#a411d5d6c063a099c1a08fa853851b764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global reserved count. <a href="#a19d785146ca5053c2da69ad1ec4de94c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/span-t">span_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global reserved master. <a href="#a1d5126b78d2bb31fe3476abcd07dd801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>[HEAP_ARRAY_SIZE]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All heaps. <a href="#a3e39052a111a2e243645494f1d6ca439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static atomic32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to restrict access to mapping memory for huge pages. <a href="#a1cb428169705ddd63fb35383132dbc40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a524405e2a853229e95546df284be2">_memory_orphan_heaps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Orphaned heaps. <a href="#ae3a524405e2a853229e95546df284be2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static _Thread_local <a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> *_memory_thread_heap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1964ae1d59012d78e56e6eedb86c58c">TLS_MODEL</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3f7c39ed647332bed5de139441f45fd">__has_builtin</a>(b)&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build time configurable limits. <a href="#ac3f7c39ed647332bed5de139441f45fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8458c6b330ad96112bceb468802e8eb4">_rpmalloc_memcpy_const</a>(x, y, s)&nbsp;&nbsp;&nbsp;memcpy(x, y, s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab88f2b93229da2f2dfdc12f60bcec450">_rpmalloc_memset_const</a>(x, y, s)&nbsp;&nbsp;&nbsp;memset(x, y, s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194bc284667af78821354e7e3c45049e">rpmalloc_assume</a>(cond)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>&nbsp;&nbsp;&nbsp;47</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of heap hashmap. <a href="#ac7e4a352a230ef04d4372db43a454b7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69503d4619673c88e0882f291eb6d86f">ENABLE_THREAD_CACHE</a>&nbsp;&nbsp;&nbsp;1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable per-thread cache. <a href="#a69503d4619673c88e0882f291eb6d86f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fd01af4bfcf583a5039c34d23e2bb9">ENABLE_GLOBAL_CACHE</a>&nbsp;&nbsp;&nbsp;1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable global cache shared between all threads, requires thread cache. <a href="#a39fd01af4bfcf583a5039c34d23e2bb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53baabd23f5ba123eb9a9d6121faed9f">ENABLE_VALIDATE_ARGS</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable validation of args to public entry points. <a href="#a53baabd23f5ba123eb9a9d6121faed9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab186ebd3fdc6562bb8aadad4ccce3ed">ENABLE_STATISTICS</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable statistics collection. <a href="#aab186ebd3fdc6562bb8aadad4ccce3ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad616b76a55f585c9f7f75af50575911a">ENABLE_ASSERTS</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable asserts. <a href="#ad616b76a55f585c9f7f75af50575911a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f574bcf90e64a0529171141caef930">ENABLE_OVERRIDE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override standard library malloc/free and new/delete entry points. <a href="#ac2f574bcf90e64a0529171141caef930">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7896aa9035235aefac2ab04a90c9d10">ENABLE_PRELOAD</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support preloading. <a href="#ae7896aa9035235aefac2ab04a90c9d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae777722890578ce47ae32f908b4005b0">DISABLE_UNMAP</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable unmapping memory pages (also enables unlimited cache) <a href="#ae777722890578ce47ae32f908b4005b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6937f23f518f51f693f7d034100f9c">ENABLE_UNLIMITED_CACHE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable unlimited global cache (no unmapping until finalization) <a href="#afc6937f23f518f51f693f7d034100f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74abd212deb430c20e3bbf5cadbe075c">ENABLE_ADAPTIVE_THREAD_CACHE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable adaptive thread cache size based on use heuristics. <a href="#a74abd212deb430c20e3bbf5cadbe075c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8803f4eab133ac4c823104577553d78">DEFAULT_SPAN_MAP_COUNT</a>&nbsp;&nbsp;&nbsp;64</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default number of spans to map in call to map more virtual memory (default values yield 4MiB here) <a href="#af8803f4eab133ac4c823104577553d78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9c1ea6434b5703d7b6e01cfffd1261">GLOBAL_CACHE_MULTIPLIER</a>&nbsp;&nbsp;&nbsp;8</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplier for global cache. <a href="#aec9c1ea6434b5703d7b6e01cfffd1261">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6937f23f518f51f693f7d034100f9c">ENABLE_UNLIMITED_CACHE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable unlimited global cache (no unmapping until finalization) <a href="#afc6937f23f518f51f693f7d034100f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74abd212deb430c20e3bbf5cadbe075c">ENABLE_ADAPTIVE_THREAD_CACHE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable adaptive thread cache size based on use heuristics. <a href="#a74abd212deb430c20e3bbf5cadbe075c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20cd3c4775f1897fb5658d2dc61382c3">PLATFORM_WINDOWS</a>&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0092e018a32f308bad3efeaa795c92b">PLATFORM_POSIX</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> __attribute__((__always_inline__))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Platform and arch specifics. <a href="#a724fb9f82013c782db5c3c12ea36aac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>(truth, message)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>(x)&nbsp;&nbsp;&nbsp;__builtin_expect((x), 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f864d9fe0055b43dc8034fe9060630">UNEXPECTED</a>(x)&nbsp;&nbsp;&nbsp;__builtin_expect((x), 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>(counter)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Statistics related functions (evaluate to nothing when statistics not enabled) <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab22b36fb2408434cc731fb9fe6a5cec">_rpmalloc_stat_dec</a>(counter)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>(counter, value)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>(counter, value)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599c57201987cc23a9787a745296e575">_rpmalloc_stat_add_peak</a>(counter, value, peak)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829d3a1ca51d0ba687990a8111940c42">_rpmalloc_stat_sub</a>(counter, value)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4c41e806e09b0468b6db0ae56ed461">_rpmalloc_stat_inc_alloc</a>(heap, class_idx)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3168e56cb172bc471c410e9daaf7ca1">_rpmalloc_stat_inc_free</a>(heap, class_idx)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a>&nbsp;&nbsp;&nbsp;16</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Preconfigured limits and sizes. <a href="#a000afcda168a6fd19a9435e049508463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66893939b9053e9bf8a97a5f50bc773a">SMALL_GRANULARITY_SHIFT</a>&nbsp;&nbsp;&nbsp;4</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Small granularity shift count. <a href="#a66893939b9053e9bf8a97a5f50bc773a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a>&nbsp;&nbsp;&nbsp;65</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of small block size classes. <a href="#afef7a20458b75404cdbba364a751694a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a>&nbsp;&nbsp;&nbsp;(<a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a> * (<a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> - 1))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum size of a small block. <a href="#aecf578949f89fb109c5f6f527a2dc49d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cbe158c682e307dc9372ee5a0b5167a">MEDIUM_GRANULARITY</a>&nbsp;&nbsp;&nbsp;512</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Granularity of a medium allocation block. <a href="#a0cbe158c682e307dc9372ee5a0b5167a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95449a66565995789e144cfc3f538261">MEDIUM_GRANULARITY_SHIFT</a>&nbsp;&nbsp;&nbsp;9</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Medium granularity shift count. <a href="#a95449a66565995789e144cfc3f538261">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>&nbsp;&nbsp;&nbsp;61</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of medium block size classes. <a href="#a554df4bc024ffaa8328e6ef37cec5c77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>&nbsp;&nbsp;&nbsp;(<a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> + <a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of small + medium size classes. <a href="#aa74d427b2b9955ff2d9719693d9fc80e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>&nbsp;&nbsp;&nbsp;63</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of large block size classes. <a href="#a04406da3f5ff4e24f155c97591678ed9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb085054ab2d682b41748925519c084">MEDIUM_SIZE_LIMIT</a>&nbsp;&nbsp;&nbsp;  (<a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a> + (<a href="#a0cbe158c682e307dc9372ee5a0b5167a">MEDIUM_GRANULARITY</a> * <a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum size of a medium block. <a href="#aecb085054ab2d682b41748925519c084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6866e2b7c1e8f60d6c74ea8fba6be44d">LARGE_SIZE_LIMIT</a>&nbsp;&nbsp;&nbsp;  ((<a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a> * <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>) - <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum size of a large block. <a href="#a6866e2b7c1e8f60d6c74ea8fba6be44d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>&nbsp;&nbsp;&nbsp;128</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of a span header (must be a multiple of SMALL_GRANULARITY and a power of two) <a href="#a645356809d937167848705edabde7d44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbd8639c3b627f526bd557e065f1c00">MAX_THREAD_SPAN_CACHE</a>&nbsp;&nbsp;&nbsp;400</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans in thread cache. <a href="#aebbd8639c3b627f526bd557e065f1c00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ad9380461f94f601227da3fe3676da">THREAD_SPAN_CACHE_TRANSFER</a>&nbsp;&nbsp;&nbsp;64</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans to transfer between thread and global cache. <a href="#a24ad9380461f94f601227da3fe3676da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b78975d481805f29847ad91c77d6ad">MAX_THREAD_SPAN_LARGE_CACHE</a>&nbsp;&nbsp;&nbsp;100</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans in thread cache for large spans (must be greater than LARGE_CLASS_COUNT / 2) <a href="#a51b78975d481805f29847ad91c77d6ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9cc04738eb37814086f557943373d8">THREAD_SPAN_LARGE_CACHE_TRANSFER</a>&nbsp;&nbsp;&nbsp;6</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans to transfer between thread and global cache for large spans. <a href="#a2e9cc04738eb37814086f557943373d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>(ptr, ofs)&nbsp;&nbsp;&nbsp;(void *)((char *)(ptr) + (ptrdiff_t)(ofs))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>(first, second)&nbsp;&nbsp;&nbsp;  (ptrdiff_t)((<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)(first) - (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)(second))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d666267d99d22454086d5fa0390bff">INVALID_POINTER</a>&nbsp;&nbsp;&nbsp;((void *)((uintptr_t) - 1))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>&nbsp;&nbsp;&nbsp;<a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>&nbsp;&nbsp;&nbsp;((uint32_t) - 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c82279e204e31a5dc89b64d2c6c27c">SPAN_FLAG_MASTER</a>&nbsp;&nbsp;&nbsp;1U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating span is the first (master) span of a split superspan. <a href="#a98c82279e204e31a5dc89b64d2c6c27c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fcaea32cf5846f1f5b40a882175dbb0">SPAN_FLAG_SUBSPAN</a>&nbsp;&nbsp;&nbsp;2U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating span is a secondary (sub) span of a split superspan. <a href="#a2fcaea32cf5846f1f5b40a882175dbb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1094486bd3e5ee282e7a4ce7de9c7db">SPAN_FLAG_ALIGNED_BLOCKS</a>&nbsp;&nbsp;&nbsp;4U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating span has blocks with increased alignment. <a href="#ad1094486bd3e5ee282e7a4ce7de9c7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132ac3786920f0bf24b2d2f7c73cf863">SPAN_FLAG_UNMAPPED_MASTER</a>&nbsp;&nbsp;&nbsp;8U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating an unmapped master span. <a href="#a132ac3786920f0bf24b2d2f7c73cf863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a025a8c2529bc60cb95c78d3948c52">_memory_default_span_size</a>&nbsp;&nbsp;&nbsp;(64 * 1024)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global data. <a href="#a04a025a8c2529bc60cb95c78d3948c52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dedf1d71cda4a8f3d1f372934ddad30">_memory_default_span_size_shift</a>&nbsp;&nbsp;&nbsp;16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0a343b3498bb882ebd7e0c3caa0935">_memory_default_span_mask</a>&nbsp;&nbsp;&nbsp;(~((uintptr_t)(<a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a> - 1)))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>&nbsp;&nbsp;&nbsp;<a href="#a04a025a8c2529bc60cb95c78d3948c52">_memory_default_span_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hardwired span size. <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>&nbsp;&nbsp;&nbsp;<a href="#a3dedf1d71cda4a8f3d1f372934ddad30">_memory_default_span_size_shift</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>&nbsp;&nbsp;&nbsp;<a href="#ada0a343b3498bb882ebd7e0c3caa0935">_memory_default_span_mask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf2ef5bd78a81c297328a5534f0ddf4">TLS_MODEL</a>&nbsp;&nbsp;&nbsp;__attribute__((tls_model("initial-exec")))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thread local heap and ID. <a href="#a3cf2ef5bd78a81c297328a5534f0ddf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### \_Atomic {#a472f0bf448a2dc3f31c0b79acd70d829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef volatile _Atomic(int32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Atomic access abstraction (since MSVC does not do C11 yet)</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### global\_cache\_t {#abb5df2e5e21b2980d57f68200c97da21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct global_cache_t global_cache_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global cache.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### heap\_size\_class\_t {#a10712f237da38c0bbb00bf9693dd9f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct heap_size_class_t heap_size_class_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### heap\_t {#a75c19bcef00dee4542c1ddab212e29a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct heap_t heap_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data types.</p>


<p>A memory heap, per thread</p>


<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### size\_class\_t {#a58b8a67689d7a172819769e39f933e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct size_class_t size_class_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size class definition.</p>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### span\_active\_t {#af801d58362e979c2a31744800624dcf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct span_active_t span_active_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Span active data.</p>

<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### span\_cache\_t {#aece665fc81eaec031382485a4a2ea5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct span_cache_t span_cache_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### span\_large\_cache\_t {#a8e7b9e9139e15a9faa403425e19b0c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct span_large_cache_t span_large_cache_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### span\_list\_t {#af2f2ee0936896aa297771a26dec63027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct span_list_t span_list_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Span list.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### span\_t {#aa34fdcc23a2d119e7436a33e05ddb665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct span_t span_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Span of memory pages.</p>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### \_rpmalloc\_adjust\_size\_class() {#a223c890fd871bff9081258f6520fc8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_adjust_size_class (size_t iclass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adjust and optimize the size class properties for the given class.</p>

<p>Definition at line 3022 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a8458c6b330ad96112bceb468802e8eb4">_rpmalloc_memcpy_const</a>, <a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_aligned\_allocate() {#a4c63f26f6c18bccde67513ce760b613a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_aligned_allocate (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t alignment, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2541 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a9641beb0030ad56b2df025775823b2af">_memory_medium_size_limit</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="#a599c57201987cc23a9787a745296e575">_rpmalloc_stat_add_peak</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#ad1094486bd3e5ee282e7a4ce7de9c7db">SPAN_FLAG_ALIGNED_BLOCKS</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> and <a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>.</p>

</div>
</div>

### \_rpmalloc\_aligned\_reallocate() {#a27aafcff5a8ed8f91ea6b53ac93a0fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_aligned_reallocate (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, void * ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2969 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#ab3774a093749aeca1d4e387b11e79395">RPMALLOC_GROW_OR_FAIL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#affda05352198b9ef86d42be851a1349f">RPMALLOC_NO_PRESERVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a>.</p>


<p>Referenced by <a href="#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate() {#a3bef7e16a625f1968110eaf331332eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a block of the given size.</p>

<p>Definition at line 2530 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a9641beb0030ad56b2df025775823b2af">_memory_medium_size_limit</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="#a6866e2b7c1e8f60d6c74ea8fba6be44d">LARGE_SIZE_LIMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a> and <a href="#a2727f400656ed5d5857d7a6e1e05b61b">rpmalloc</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate\_from\_heap\_fallback() {#a0a241af7d6b9c4eb88bc5480f3fa10d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate_from_heap_fallback (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/heap-size-class-t">heap_size_class_t</a> * heap_size_class, uint32_t class_idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a small/medium sized memory block from the given heap.</p>

<p>Definition at line 2376 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#a49d22808308e599742e41ef2d4671cfa">_rpmalloc_span_double_link_list_pop_head</a>, <a href="#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>, <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a>, <a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/span-t/#a7ee7892ce3c5d8342af193f1824a5098">span_t::block_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a97df83853dc6ddf7e0114691b15edb49">span_t::block_size</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a22b0340927d02f0c7c4486f01c31358e">span_t::free_list_deferred</a>, <a href="/web-llvm/docs/api/structs/span-t/#af093d9cb1719d72c20f96a9b467590f5">span_t::free_list_limit</a>, <a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a>, <a href="#ac8dde7c610d47213bd49d710016f9476">free_list_pop</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="#a194bc284667af78821354e7e3c45049e">rpmalloc_assume</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>


<p>Referenced by <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> and <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate\_huge() {#abd2feafaa32ab4fd14728c6f1b27cb76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate_huge (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a huge block by mapping memory pages directly.</p>

<p>Definition at line 2501 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#a599c57201987cc23a9787a745296e575">_rpmalloc_stat_add_peak</a>, <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate\_large() {#a8bdabec99c6c3fe43d727ccd713ac112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate_large (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a large sized memory block from the given heap.</p>

<p>Definition at line 2471 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate\_medium() {#ac615e23f8046310bb788e678b486b20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate_medium (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a medium sized memory block from the given heap.</p>

<p>Definition at line 2454 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd4c41e806e09b0468b6db0ae56ed461">_rpmalloc_stat_inc_alloc</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="#ac8dde7c610d47213bd49d710016f9476">free_list_pop</a>, <a href="#a95449a66565995789e144cfc3f538261">MEDIUM_GRANULARITY_SHIFT</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> and <a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_allocate\_small() {#a3dd2306a260dcdc3e852a2898914cbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_allocate_small (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a small sized memory block from the given heap.</p>

<p>Definition at line 2440 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd4c41e806e09b0468b6db0ae56ed461">_rpmalloc_stat_inc_alloc</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="#ac8dde7c610d47213bd49d710016f9476">free_list_pop</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a> and <a href="#a66893939b9053e9bf8a97a5f50bc773a">SMALL_GRANULARITY_SHIFT</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate() {#ae324fa158db468143544693dfe539800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate (void * p)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate the given block.</p>

<p>Definition at line 2862 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a> and <a href="#af8f864d9fe0055b43dc8034fe9060630">UNEXPECTED</a>.</p>


<p>Referenced by <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a> and <a href="#a19186eb24d08ef02b924951abb865b51">rpfree</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_defer\_free\_span() {#ac8a96725f034c08fdff774eb54785947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_defer_free_span (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2711 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a303f700546874a81e694eda44cc3174d">atomic_cas_ptr</a>, <a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a354c0beb35fd982bc4dbd3783b2dd1ff">heap_t::span_free_deferred</a>.</p>


<p>Referenced by <a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a> and <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_defer\_small\_or\_medium() {#a6cc5147be3d12c47a533a9cd14e36801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_defer_small_or_medium (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, void * block)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Put the block in the deferred free list of the owning span.</p>

<p>Definition at line 2721 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a>, <a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/span-t/#a7ee7892ce3c5d8342af193f1824a5098">span_t::block_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a22b0340927d02f0c7c4486f01c31358e">span_t::free_list_deferred</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#a95d666267d99d22454086d5fa0390bff">INVALID_POINTER</a> and <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>.</p>


<p>Referenced by <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_direct\_small\_or\_medium() {#a6c1102ef8a3812f1098cad573ea7794e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_direct_small_or_medium (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, void * block)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocation entry points.</p>


<p>Deallocate the given small/medium memory block in the current thread local heap</p>


<p>Definition at line 2671 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a>, <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>, <a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a>, <a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/span-t/#a7ee7892ce3c5d8342af193f1824a5098">span_t::block_count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a22b0340927d02f0c7c4486f01c31358e">span_t::free_list_deferred</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#a95d666267d99d22454086d5fa0390bff">INVALID_POINTER</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#af8f864d9fe0055b43dc8034fe9060630">UNEXPECTED</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>


<p>Referenced by <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_huge() {#a61e3c97b4484c79f1edd1757dc3d0e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_huge (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global cache.</p>


<p>Deallocate the given huge span.</p>


<p>Heap control</p>


<p>Definition at line 2834 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#a829d3a1ca51d0ba687990a8111940c42">_rpmalloc_stat_sub</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>.</p>


<p>Referenced by <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a> and <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_large() {#a573fc7baab7be24c6bac115b7f62192f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_large (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate the given large memory block to the current heap.</p>

<p>Definition at line 2769 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="/web-llvm/docs/api/structs/span-t/#a07d2ba73260e7e5dbe98c76436888c5f">span_t::offset_from_master</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4aecbd1cbb36425fddd53125ea1a84c7">span_t::remaining_spans</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#a98c82279e204e31a5dc89b64d2c6c27c">SPAN_FLAG_MASTER</a>, <a href="#a2fcaea32cf5846f1f5b40a882175dbb0">SPAN_FLAG_SUBSPAN</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa549da79e540bdd3e963e294a39f64cf">heap_t::span_reserve</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa6719c6b21d6c30ce96e404a63cc4bae">heap_t::span_reserve_master</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>.</p>

</div>
</div>

### \_rpmalloc\_deallocate\_small\_or\_medium() {#a7fdcd37f930a06ca527ab10334bf1d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_deallocate_small_or_medium (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, void * p)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2745 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#ab3168e56cb172bc471c410e9daaf7ca1">_rpmalloc_stat_inc_free</a>, <a href="/web-llvm/docs/api/structs/span-t/#a97df83853dc6ddf7e0114691b15edb49">span_t::block_size</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>, <a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#ad1094486bd3e5ee282e7a4ce7de9c7db">SPAN_FLAG_ALIGNED_BLOCKS</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>.</p>

</div>
</div>

### \_rpmalloc\_global\_get\_reserved\_spans() {#a80ccc3407de6606e73356a7c4e2dc6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_global_get_reserved_spans (size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Use global reserved spans to fulfill a memory map request (reserve size must be checked by caller)</p>

<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a>, <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>, <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>.</p>

</div>
</div>

### \_rpmalloc\_global\_set\_reserved\_spans() {#aa6d37b325f0f3c68f89cdf681681a09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_global_set_reserved_spans (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * master, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * reserve, size_t reserve_span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Store the given spans as global reserve (must only be called from within new heap allocation, not thread safe)</p>

<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a>, <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a> and <a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_allocate() {#a0b2f5071d70703ea5cc1e670361a8cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t * _rpmalloc_heap_allocate (int first_class)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a new heap, potentially reusing a previously orphaned heap.</p>

<p>Definition at line 2223 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#ae3a524405e2a853229e95546df284be2">_memory_orphan_heaps</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#acef9b939687a94621d82016836da1c91">_rpmalloc_heap_extract_orphan</a>, <a href="#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a>, <a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a> and <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>.</p>


<p>Referenced by <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_allocate\_new() {#a648de3a42660a0567102d78aa59ceded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t * _rpmalloc_heap_allocate_new (void)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a new heap from newly mapped memory pages.</p>

<p>Definition at line 2131 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a>, <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>, <a href="#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a>, <a href="#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a348c1835d21f0af4a3776f96bdba64fb">heap_t::master_heap</a> and <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_cache\_adopt\_deferred() {#af44e92f7ed42c434bd33a0ae98210a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_cache_adopt_deferred (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> ** single_span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adopt the deferred span cache list, optionally extracting the first single span for immediate re-use.</p>

<p>Definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#aab22b36fb2408434cc731fb9fe6a5cec">_rpmalloc_stat_dec</a>, <a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a354c0beb35fd982bc4dbd3783b2dd1ff">heap_t::span_free_deferred</a>.</p>


<p>Referenced by <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a> and <a href="#a86b7049fa43f5ff960119426a26c81fc">_rpmalloc_heap_thread_cache_deferred_extract</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_cache\_insert() {#abdbbc20ab63d76c1709722f3f2305610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_cache_insert (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Span control.</p>


<p>Insert a single span into thread heap cache, releasing to global cache if overflow.</p>


<p>Definition at line 1892 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/span-large-cache-t/#a07da73cfe1c11642973a6eb1386a3a1c">span_large_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="#aebbd8639c3b627f526bd557e065f1c00">MAX_THREAD_SPAN_CACHE</a>, <a href="#a51b78975d481805f29847ad91c77d6ad">MAX_THREAD_SPAN_LARGE_CACHE</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>, <a href="/web-llvm/docs/api/structs/span-large-cache-t/#a77eff1faca249ec6ae27881769f7d979">span_large_cache_t::span</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#a24ad9380461f94f601227da3fe3676da">THREAD_SPAN_CACHE_TRANSFER</a>, <a href="#a2e9cc04738eb37814086f557943373d8">THREAD_SPAN_LARGE_CACHE_TRANSFER</a> and <a href="#af8f864d9fe0055b43dc8034fe9060630">UNEXPECTED</a>.</p>


<p>Referenced by <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_extract\_new\_span() {#acf65e6242a6d42e38959bac148c7aadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_heap_extract_new_span (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/heap-size-class-t">heap_size_class_t</a> * heap_size_class, size_t span_count, uint32_t class_idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a span from one of the cache levels (thread cache, reserved, global cache) or fallback to mapping more memory.</p>

<p>Definition at line 2050 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a>, <a href="#a9beacd6369e4fdac1b24268d2515a858">_rpmalloc_heap_reserved_extract</a>, <a href="#a86b7049fa43f5ff960119426a26c81fc">_rpmalloc_heap_thread_cache_deferred_extract</a>, <a href="#ab3f1ac00b9740730f851945218be4d6a">_rpmalloc_heap_thread_cache_extract</a>, <a href="#a56211c3481cd02195d9bac3c1475cdfb">_rpmalloc_inc_span_statistics</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#a72cb3beffa763418cb7c8e89ff257b8e">heap_size_class_t::cache</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a> and <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a> and <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_extract\_orphan() {#acef9b939687a94621d82016836da1c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t * _rpmalloc_heap_extract_orphan (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> ** heap_list)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/heap-t/#a87e83453c93d1e6de70f6a45044e510d">heap_t::next_orphan</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_finalize() {#a2a1e3b11c0a8fc714d6def51250c6906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_finalize (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2307 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#a72cb3beffa763418cb7c8e89ff257b8e">heap_size_class_t::cache</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a354c0beb35fd982bc4dbd3783b2dd1ff">heap_t::span_free_deferred</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_global\_cache\_extract() {#abeb50100f90c725f1e16944cd67e9f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_heap_global_cache_extract (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a span from the global cache.</p>

<p>Definition at line 1992 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>, <a href="#a24ad9380461f94f601227da3fe3676da">THREAD_SPAN_CACHE_TRANSFER</a> and <a href="#a2e9cc04738eb37814086f557943373d8">THREAD_SPAN_LARGE_CACHE_TRANSFER</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_global\_finalize() {#a2f7a67a3403fd19a70e7a0418714af57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_global_finalize (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a2342224142317f85fca91614fc973131">heap_t::id</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a> and <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_initialize() {#a58f109a58b8e38970cda041f4ea96772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_initialize (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#af42cdefbf9addf1c268ba19e63c60f29">_memory_heap_id</a>, <a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="#ab88f2b93229da2f2dfdc12f60bcec450">_rpmalloc_memset_const</a>, <a href="#a1fe9c932f58e2baffed3ea33fd299691">atomic_incr32</a>, <a href="#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a2342224142317f85fca91614fc973131">heap_t::id</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_orphan() {#a5bd98ea2cfee2186b2aa2b921450807f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_orphan (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, int first_class)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae3a524405e2a853229e95546df284be2">_memory_orphan_heaps</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a87e83453c93d1e6de70f6a45044e510d">heap_t::next_orphan</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_release() {#a1b9ab55b2401b2d4240bbca4b313f6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_release (void * heapptr, int first_class, int release_cache)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2241 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a>, <a href="#aacc7bcb924cab5e38c3fe65c5d0b4ab0">_rpmalloc_main_thread_id</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a49e532a65b873a6c3315aa769299687c">_rpmalloc_stat_add64</a>, <a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a>, <a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a>, <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a> and <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>.</p>


<p>Referenced by <a href="#aa378f245dd9ff587c375db42472ac954">_rpmalloc_heap_release_raw</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_release\_raw() {#aa378f245dd9ff587c375db42472ac954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_release_raw (void * heapptr, int release_cache)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2299 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>.</p>


<p>Referenced by <a href="#a375befcec19545c40cb27c22512501bb">_rpmalloc_heap_release_raw_fc</a> and <a href="#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_release\_raw\_fc() {#a375befcec19545c40cb27c22512501bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_release_raw_fc (void * heapptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#aa378f245dd9ff587c375db42472ac954">_rpmalloc_heap_release_raw</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_reserved\_extract() {#a9beacd6369e4fdac1b24268d2515a858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_heap_reserved_extract (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1984 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_set\_reserved\_spans() {#ae4a00ccf859d64a7519ae121563a56e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_set_reserved_spans (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * master, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * reserve, size_t reserve_span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Store the given spans as reserve in the given heap.</p>

<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/heap-t/#aa549da79e540bdd3e963e294a39f64cf">heap_t::span_reserve</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa6719c6b21d6c30ce96e404a63cc4bae">heap_t::span_reserve_master</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> and <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_thread\_cache\_deferred\_extract() {#a86b7049fa43f5ff960119426a26c81fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_heap_thread_cache_deferred_extract (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a> and <a href="#ab3f1ac00b9740730f851945218be4d6a">_rpmalloc_heap_thread_cache_extract</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_thread\_cache\_extract() {#ab3f1ac00b9740730f851945218be4d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_heap_thread_cache_extract (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the given number of spans from the different cache levels.</p>

<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a> and <a href="/web-llvm/docs/api/structs/span-cache-t/#a8cc6a9b0d6d8d6bf8367bca0101b1ae3">span_cache_t::span</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a> and <a href="#a86b7049fa43f5ff960119426a26c81fc">_rpmalloc_heap_thread_cache_deferred_extract</a>.</p>

</div>
</div>

### \_rpmalloc\_heap\_unmap() {#a0d896198d6c5673397704f9f6bdadbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_heap_unmap (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1830 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a59fb66e831ef1e0d56d826b1851576eb">heap_t::child_count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a348c1835d21f0af4a3776f96bdba64fb">heap_t::master_heap</a>.</p>


<p>Referenced by <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a> and <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>.</p>

</div>
</div>

### \_rpmalloc\_inc\_span\_statistics() {#a56211c3481cd02195d9bac3c1475cdfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_inc_span_statistics (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count, uint32_t class_idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2031 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a599c57201987cc23a9787a745296e575">_rpmalloc_stat_add_peak</a>, <a href="#a1fe9c932f58e2baffed3ea33fd299691">atomic_incr32</a> and <a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>.</p>

</div>
</div>

### \_rpmalloc\_mmap() {#afb297c8e6c20ce017a62ea42b70be194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_mmap (size_t size, size_t * offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map more virtual memory.</p>

<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a599c57201987cc23a9787a745296e575">_rpmalloc_stat_add_peak</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>.</p>

</div>
</div>

### \_rpmalloc\_mmap\_os() {#a833da3799d95ff35eae22f00833538b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_mmap_os (size_t size, size_t * offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default implementation to map new pages to virtual memory.</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="#a4cdf64413eaa3e80f8a1dfe158bd2525">_memory_huge_pages</a>, <a href="#a1e29d8d18139babda354d5d92d46ca02">_memory_map_granularity</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_reallocate() {#a9942f9f958830d9f83ecf67b85de3ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_reallocate (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, void * p, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reallocate the given block to the given size.</p>

<p>Definition at line 2885 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/span-t/#a97df83853dc6ddf7e0114691b15edb49">span_t::block_size</a>, <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#ab3774a093749aeca1d4e387b11e79395">RPMALLOC_GROW_OR_FAIL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#affda05352198b9ef86d42be851a1349f">RPMALLOC_NO_PRESERVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> and <a href="#a8f9643796f1e94fcc804c5c97a7985e9">rprealloc</a>.</p>

</div>
</div>

### \_rpmalloc\_set\_name() {#a66c4be5ac967e1374b25eb8ac80f68d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_set_name (void * address, size_t size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Low level memory map/unmap.</p>

<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="#a4cdf64413eaa3e80f8a1dfe158bd2525">_memory_huge_pages</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_align\_count() {#a6780f79fe39d5c99886e27fccaf4133c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _rpmalloc_span_align_count (size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the aligned number of spans to map in based on wanted count, configured mapping granularity and the page size.</p>

<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">_memory_span_map_count</a> and <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>.</p>


<p>Referenced by <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_double\_link\_list\_add() {#ac32a750ddf4072d46c28f52b9f3ee018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_double_link_list_add (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> ** head, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Span linked list management.</p>


<p>Add a span to double linked list at the head</p>


<p>Definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_double\_link\_list\_pop\_head() {#a49d22808308e599742e41ef2d4671cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_double_link_list_pop_head (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> ** head, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pop head span from double linked list.</p>

<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a> and <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_double\_link\_list\_remove() {#aec7913670102d551e3fd60509cd381a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_double_link_list_remove (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> ** head, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a span from double linked list.</p>

<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/span-t/#a386f776cc556d33534161ece5083e4de">span_t::prev</a> and <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>.</p>


<p>Referenced by <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_extract\_free\_list\_deferred() {#af2ca2fcf7e544c9458ef49057a40b78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_extract_free_list_deferred (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1555 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a>, <a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a22b0340927d02f0c7c4486f01c31358e">span_t::free_list_deferred</a>, <a href="#a95d666267d99d22454086d5fa0390bff">INVALID_POINTER</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_finalize() {#aa776faada2c6d5b7edda58a3a1d701c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int _rpmalloc_span_finalize (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t iclass, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> ** list_head)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1574 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#aab22b36fb2408434cc731fb9fe6a5cec">_rpmalloc_stat_dec</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>


<p>Referenced by <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_initialize() {#ad5eb163989618d4ea0eff254cdbdd596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_initialize (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, size_t total_span_count, size_t span_count, size_t align_offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setup a newly mapped span.</p>

<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4aecbd1cbb36425fddd53125ea1a84c7">span_t::remaining_spans</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#a98c82279e204e31a5dc89b64d2c6c27c">SPAN_FLAG_MASTER</a> and <a href="/web-llvm/docs/api/structs/span-t/#af32dc4254a995d8ba3ab99376c9ad4d0">span_t::total_spans</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a> and <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_initialize\_new() {#a64debeb0ce94e6048da7c8fad19b1d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * _rpmalloc_span_initialize_new (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/heap-size-class-t">heap_size_class_t</a> * heap_size_class, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span, uint32_t class_idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize an unused span (from cache or mapped) to be new active span, putting the initial free list in heap class free list.</p>

<p>Definition at line 1519 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#ac32a750ddf4072d46c28f52b9f3ee018">_rpmalloc_span_double_link_list_add</a>, <a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#aeded978bd21c13b71d9b0310b5bb09ec">size_class_t::block_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a7ee7892ce3c5d8342af193f1824a5098">span_t::block_count</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#a007fc7dd52ba1f95d9a6ce88f47a614b">size_class_t::block_size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a97df83853dc6ddf7e0114691b15edb49">span_t::block_size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#ac411b0f198d4e31569fc30ca2c174f65">heap_size_class_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#a22b0340927d02f0c7c4486f01c31358e">span_t::free_list_deferred</a>, <a href="/web-llvm/docs/api/structs/span-t/#af093d9cb1719d72c20f96a9b467590f5">span_t::free_list_limit</a>, <a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a6aa789c3cdf7e70df144c248d18c5f4c">heap_t::full_span_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#ad1094486bd3e5ee282e7a4ce7de9c7db">SPAN_FLAG_ALIGNED_BLOCKS</a>, <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_is\_fully\_utilized() {#ade7fb930b30a5a8bd04ecc97cad60e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int _rpmalloc_span_is_fully_utilized (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/span-t/#a7ee7892ce3c5d8342af193f1824a5098">span_t::block_count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#af093d9cb1719d72c20f96a9b467590f5">span_t::free_list_limit</a> and <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a> and <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_map() {#ae3ba0ad3b30a2fa8c63ff06218750cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_span_map (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map in memory pages for the given number of spans (or use previously reserved pages)</p>

<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>, <a href="#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">_memory_span_map_count</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>, <a href="#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a>, <a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="#a9beacd6369e4fdac1b24268d2515a858">_rpmalloc_heap_reserved_extract</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_map\_aligned\_count() {#a2a4e560819e42925aaa4494511aae43d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_span_map_aligned_count (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map an aligned set of spans, taking configured mapping granularity and the page size into account.</p>

<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a>, <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>, <a href="#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#ae4a00ccf859d64a7519ae121563a56e7">_rpmalloc_heap_set_reserved_spans</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a6780f79fe39d5c99886e27fccaf4133c">_rpmalloc_span_align_count</a>, <a href="#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa549da79e540bdd3e963e294a39f64cf">heap_t::span_reserve</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa6719c6b21d6c30ce96e404a63cc4bae">heap_t::span_reserve_master</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_map\_from\_reserve() {#afaa0ba431359c9bab42909cfc9248b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t * _rpmalloc_span_map_from_reserve (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Use reserved spans to fulfill a memory map request (reserve size must be checked by caller)</p>

<p>Definition at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa549da79e540bdd3e963e294a39f64cf">heap_t::span_reserve</a>, <a href="/web-llvm/docs/api/structs/heap-t/#aa6719c6b21d6c30ce96e404a63cc4bae">heap_t::span_reserve_master</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a8d5b27011e1ab5140090f90a75584329">heap_t::spans_reserved</a>.</p>


<p>Referenced by <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_mark\_as\_subspan\_unless\_master() {#a91bf3ee061b188b8a650fbac9babef4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_mark_as_subspan_unless_master (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * master, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * subspan, size_t span_count)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declare the span to be a subspan and store distance from master span and span count.</p>

<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/span-t/#a07d2ba73260e7e5dbe98c76436888c5f">span_t::offset_from_master</a>, <a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#a98c82279e204e31a5dc89b64d2c6c27c">SPAN_FLAG_MASTER</a> and <a href="#a2fcaea32cf5846f1f5b40a882175dbb0">SPAN_FLAG_SUBSPAN</a>.</p>


<p>Referenced by <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a> and <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_release\_to\_cache() {#a62b31eca2760e37676716c54c5b64947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_release_to_cache (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap, <a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the span (used for small or medium allocations) to the heap thread cache.</p>

<p>Definition at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#aab22b36fb2408434cc731fb9fe6a5cec">_rpmalloc_stat_dec</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#a72cb3beffa763418cb7c8e89ff257b8e">heap_size_class_t::cache</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/structs/span-t/#a345270ce5d1e5e112b45cfde43f37da0">span_t::heap</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a> and <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>.</p>


<p>Referenced by <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>.</p>

</div>
</div>

### \_rpmalloc\_span\_unmap() {#a1b31ff8fa0abcdb205dadd8afc026014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_span_unmap (<a href="/web-llvm/docs/api/structs/span-t">span_t</a> * span)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unmap memory pages for the given number of spans (or mark as unused if no partial unmappings)</p>

<p>Definition at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a829d3a1ca51d0ba687990a8111940c42">_rpmalloc_stat_sub</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="/web-llvm/docs/api/structs/span-t/#a13753de75bc52a5b8a1a9532083c9ba4">span_t::align_offset</a>, <a href="#af327588f7260778f453d9a212396e0e0">atomic_add32</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4de89d484559557bb639a2703c750b17">span_t::flags</a>, <a href="/web-llvm/docs/api/structs/span-t/#a07d2ba73260e7e5dbe98c76436888c5f">span_t::offset_from_master</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a4aecbd1cbb36425fddd53125ea1a84c7">span_t::remaining_spans</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="#a98c82279e204e31a5dc89b64d2c6c27c">SPAN_FLAG_MASTER</a>, <a href="#a2fcaea32cf5846f1f5b40a882175dbb0">SPAN_FLAG_SUBSPAN</a>, <a href="#a132ac3786920f0bf24b2d2f7c73cf863">SPAN_FLAG_UNMAPPED_MASTER</a> and <a href="/web-llvm/docs/api/structs/span-t/#af32dc4254a995d8ba3ab99376c9ad4d0">span_t::total_spans</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>, <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### \_rpmalloc\_spin() {#a335307d78e0ff77d4da9cf42156803ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_spin (void)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> and <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a>.</p>

</div>
</div>

### \_rpmalloc\_unmap() {#abfbbb8e2f9b086d466fe2898a283c98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_unmap (void * address, size_t size, size_t offset, size_t release)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unmap virtual memory.</p>

<p>Definition at line 1024 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a4a53d0cfdcf755d4fbbae446a055440c">_rpmalloc_stat_add</a>, <a href="#a829d3a1ca51d0ba687990a8111940c42">_rpmalloc_stat_sub</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a> and <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### \_rpmalloc\_unmap\_os() {#a693c463bae081b54b0b799e97bf84fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void _rpmalloc_unmap_os (void * address, size_t size, size_t offset, size_t release)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default implementation to unmap pages from virtual memory.</p>

<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1e29d8d18139babda354d5d92d46ca02">_memory_map_granularity</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a>, <a href="#a829d3a1ca51d0ba687990a8111940c42">_rpmalloc_stat_sub</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_usable\_size() {#adc5743a6b15192da5b7e023f85360208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _rpmalloc_usable_size (void * p)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reallocation entry points.</p>


<p>Initialization, finalization and utility.</p>


<p>Get the usable size of the given block</p>


<p>Definition at line 3002 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="/web-llvm/docs/api/structs/span-t/#a97df83853dc6ddf7e0114691b15edb49">span_t::block_size</a>, <a href="#af51a6ed47e80b1b57187f1d5be6c8b4c">pointer_diff</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="#a3f84dd23eb0ef3cf54aeb6afff0618ae">SIZE_CLASS_LARGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> and <a href="#a7a9f597c853963de259b40e985d81113">rpmalloc_usable_size</a>.</p>

</div>
</div>

### atomic\_add32() {#af327588f7260778f453d9a212396e0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int32_t atomic_add32 (atomic32_t * val, int32_t add)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### atomic\_add64() {#a481f7733c3d6469b66e9a746e0afb0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int64_t atomic_add64 (atomic64_t * val, int64_t add)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>

</div>
</div>

### atomic\_cas\_ptr() {#a303f700546874a81e694eda44cc3174d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int atomic_cas_ptr (atomicptr_t * dst, void * val, void * ref)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>.</p>

</div>
</div>

### atomic\_cas32\_acquire() {#a2071bf7ebae50eced1f16b359f9d5c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int atomic_cas32_acquire (atomic32_t * dst, int32_t val, int32_t ref)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> and <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a>.</p>

</div>
</div>

### atomic\_decr32() {#a4f0dc3c548801773a4da1c96f39b04c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int32_t atomic_decr32 (atomic32_t * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a> and <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### atomic\_exchange\_ptr\_acquire() {#a00bbb337491324377139681240567490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void * atomic_exchange_ptr_acquire (atomicptr_t * dst, void * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a> and <a href="#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>.</p>

</div>
</div>

### atomic\_incr32() {#a1fe9c932f58e2baffed3ea33fd299691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int32_t atomic_incr32 (atomic32_t * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a> and <a href="#a56211c3481cd02195d9bac3c1475cdfb">_rpmalloc_inc_span_statistics</a>.</p>

</div>
</div>

### atomic\_load\_ptr() {#a912154b2fc1b8fc6d74c6364523f1f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void * atomic_load_ptr (atomicptr_t * src)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### atomic\_load64() {#a083ecd4af0f476009595e8ee78cf2ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE int64_t atomic_load64 (atomic64_t * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### atomic\_store\_ptr() {#ae261e72f93968b03a76ada7a6b150965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void atomic_store_ptr (atomicptr_t * dst, void * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>

</div>
</div>

### atomic\_store\_ptr\_release() {#a94d4ba8d2181723f35b45da39c91d8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void atomic_store_ptr_release (atomicptr_t * dst, void * val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a> and <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### atomic\_store32() {#aa1ee77cdccf0341222f64395d0be2626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void atomic_store32 (atomic32_t * dst, int32_t val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#a56211c3481cd02195d9bac3c1475cdfb">_rpmalloc_inc_span_statistics</a>, <a href="#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### atomic\_store32\_release() {#a2a87a6060d5387fe8491a00600073687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FORCEINLINE void atomic_store32_release (atomic32_t * dst, int32_t val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a724fb9f82013c782db5c3c12ea36aac8">FORCEINLINE</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>, <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### free\_list\_partial\_init() {#addf543f30c5eefc1dded60025c78a816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t free_list_partial_init (void ** list, void ** first_block, void * page_start, void * block_start, uint32_t block_count, uint32_t block_size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a (partial) free list up to next system memory page, while reserving the first block as allocated, returning number of blocks in list.</p>

<p>Definition at line 1484 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#ab4225911698b67188e1538c334cfe16c">pointer_offset</a> and <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a> and <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### free\_list\_pop() {#ac8dde7c610d47213bd49d710016f9476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * free_list_pop (void ** list)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocation entry points.</p>


<p>Pop first block from a free list</p>


<p>Definition at line 2369 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> and <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>.</p>

</div>
</div>

### get\_thread\_heap() {#afb9f599f45127d8ba79cf413ad35d90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t * get_thread_heap (void)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the current thread heap.</p>

<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a90593dceacf0c04f14d084bed7e7eabe">EXPECTED</a>, <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> and <a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a>.</p>


<p>Referenced by <a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>, <a href="#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a>, <a href="#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a>, <a href="#a2727f400656ed5d5857d7a6e1e05b61b">rpmalloc</a> and <a href="#a8f9643796f1e94fcc804c5c97a7985e9">rprealloc</a>.</p>

</div>
</div>

### get\_thread\_heap\_raw() {#a149fe6706f44dfb65fbdbba32c926476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t * get_thread_heap_raw (void)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="#a6f18b8696daac522d93e448aadd7cd4b">rpmalloc_is_thread_initialized</a>, <a href="#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a>, <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### get\_thread\_id() {#a84e326ca88dee0bd7ca995727bb52381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t get_thread_id (void)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fast thread ID.</p>

<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a53adc7f95e9b3fa3e62ba8f50add0ce9">rpmalloc_set_main_thread</a> and <a href="#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>

</div>
</div>

### rpaligned\_alloc() {#a76c23d646a743db9d2576b599b3d01fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpaligned_alloc (size_t alignment, size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of at least the given size and alignment.</p>

<p>Definition at line 3438 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#ae572e25a23de1a9793b4e5b1ec0550b1">rpaligned_calloc</a>, <a href="#a61de67ff29b3d0e5d130ac9a7d0d2538">rpmemalign</a> and <a href="#ae6f35022f9384e2a22ed2b96c00995b2">rpposix_memalign</a>.</p>

</div>
</div>

### rpaligned\_calloc() {#ae572e25a23de1a9793b4e5b1ec0550b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpaligned_calloc (size_t alignment, size_t num, size_t size)</td>
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



<p>Definition at line 3444 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpaligned\_realloc() {#a4f191e772a1cda4fb5de7300bac4ea37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpaligned_realloc (void * ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reallocate the given block to at least the given size and alignment,.</p>

<p>Definition at line 3424 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpcalloc() {#a5627c7b5f1dc087ce096df1c787b5ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpcalloc (size_t num, size_t size)</td>
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



<p>Definition at line 3387 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpfree() {#a19186eb24d08ef02b924951abb865b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpfree (void * ptr)</td>
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

<p>Free the given memory block.</p>

<p>Definition at line 3385 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>.</p>

</div>
</div>

### rpmalloc() {#a2727f400656ed5d5857d7a6e1e05b61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpmalloc (size_t size)</td>
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

<p>Allocate a memory block of at least the given size.</p>

<p>Definition at line 3374 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpmalloc\_config() {#a43c11aa4589298b607afc250133440e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const rpmalloc_config_t * rpmalloc_config (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get allocator configuration.</p>

<p>Definition at line 3370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>.</p>

</div>
</div>

### rpmalloc\_dump\_statistics() {#a759e72612fab78b1159ab7129a7f7e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_dump_statistics (void * file)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump all statistics in human readable format to file (should be a FILE*)</p>

<p>Definition at line 3694 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a440c6f31099f3836f7beb5e47d14fb2d">global_cache_t::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, <a href="#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a8bb140aee00ffae527f7c0706d98c3d1">global_cache_t::overflow</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>.</p>

</div>
</div>

### rpmalloc\_finalize() {#aff58cf54f7ebc5d3d71a2ad80a0dab94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_finalize (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the allocator.</p>


<p>Finalize allocator.</p>


<p>Definition at line 3293 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a>, <a href="#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>, <a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="#af327588f7260778f453d9a212396e0e0">atomic_add32</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a>.</p>

</div>
</div>

### rpmalloc\_global\_statistics() {#ae6278b2864893c2bc2d86b5d6d9f2d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_global_statistics (<a href="/web-llvm/docs/api/structs/rpmalloc-global-statistics-t">rpmalloc_global_statistics_t</a> * stats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get global statistics.</p>

<p>Definition at line 3572 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a>, <a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a440c6f31099f3836f7beb5e47d14fb2d">global_cache_t::count</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a9c0563645d0d1fd53044a9c00dad6dc0">global_cache_t::lock</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a8bb140aee00ffae527f7c0706d98c3d1">global_cache_t::overflow</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a971b2fc3751cade0a6b2f76c92774317">stats</a>.</p>

</div>
</div>

### rpmalloc\_initialize() {#a995ec0e5a8f40e3fb178abab89dc7fd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rpmalloc_initialize (void)</td>
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

<p>Initialize the allocator and setup global data.</p>


<p>Initialize allocator with default configuration.</p>


<p>Definition at line 3047 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> and <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>.</p>


<p>Referenced by <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>.</p>

</div>
</div>

### rpmalloc\_initialize\_config() {#a2ae01990651a75a352409fb1fbf85d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rpmalloc_initialize_config (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a> * config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize allocator with given configuration.</p>

<p>Definition at line 3055 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="#ada0a343b3498bb882ebd7e0c3caa0935">_memory_default_span_mask</a>, <a href="#a04a025a8c2529bc60cb95c78d3948c52">_memory_default_span_size</a>, <a href="#a3dedf1d71cda4a8f3d1f372934ddad30">_memory_default_span_size_shift</a>, <a href="#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a>, <a href="#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="#a4cdf64413eaa3e80f8a1dfe158bd2525">_memory_huge_pages</a>, <a href="#a1e29d8d18139babda354d5d92d46ca02">_memory_map_granularity</a>, <a href="#a9641beb0030ad56b2df025775823b2af">_memory_medium_size_limit</a>, <a href="#ae3a524405e2a853229e95546df284be2">_memory_orphan_heaps</a>, <a href="#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">_memory_span_map_count</a>, <a href="#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="#a375befcec19545c40cb27c22512501bb">_rpmalloc_heap_release_raw_fc</a>, <a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="#ab88f2b93229da2f2dfdc12f60bcec450">_rpmalloc_memset_const</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="#af8803f4eab133ac4c823104577553d78">DEFAULT_SPAN_MAP_COUNT</a>, <a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>, <a href="#a0cbe158c682e307dc9372ee5a0b5167a">MEDIUM_GRANULARITY</a>, <a href="#aecb085054ab2d682b41748925519c084">MEDIUM_SIZE_LIMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2e1b5bd9424a1d1082d4bd670b1a0be6">rc</a>, <a href="#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="#a70d0f00495eb8c073a81cd0119fa8429">rpmalloc_linker_reference</a>, <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a>, <a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a>, <a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a> and <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a>.</p>

</div>
</div>

### rpmalloc\_is\_thread\_initialized() {#a6f18b8696daac522d93e448aadd7cd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rpmalloc_is_thread_initialized (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query if allocator is initialized for calling thread.</p>

<p>Definition at line 3366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a>.</p>

</div>
</div>

### rpmalloc\_linker\_reference() {#a70d0f00495eb8c073a81cd0119fa8429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_linker_reference (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dummy empty function for forcing linker symbol inclusion.</p>

<p>Definition at line 3992 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### rpmalloc\_set\_main\_thread() {#a53adc7f95e9b3fa3e62ba8f50add0ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_set_main_thread (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set main thread ID.</p>

<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#aacc7bcb924cab5e38c3fe65c5d0b4ab0">_rpmalloc_main_thread_id</a> and <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a>.</p>

</div>
</div>

### rpmalloc\_thread\_collect() {#a6db2d5852bc3af5ee8bbbfae2db30997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_thread_collect (void)</td>
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

<p>Perform deferred deallocations pending for the calling thread heap.</p>

<p>Definition at line 3487 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### rpmalloc\_thread\_finalize() {#a6e5fc3857f84254caa88503e02bf163c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_thread_finalize (int release_caches)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize thread, orphan heap.</p>


<p>Finalize allocator for calling thread.</p>


<p>Definition at line 3356 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#aa378f245dd9ff587c375db42472ac954">_rpmalloc_heap_release_raw</a>, <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> and <a href="#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>


<p>Referenced by <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### rpmalloc\_thread\_initialize() {#a85a64540090a42380ee6d969ec1897c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_thread_initialize (void)</td>
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

<p>Initialize thread, assign heap.</p>


<p>Initialize allocator for calling thread.</p>


<p>Definition at line 3342 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> and <a href="#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>


<p>Referenced by <a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### rpmalloc\_thread\_statistics() {#acb3289e60a1c405dbb154dce3f3d6c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rpmalloc_thread_statistics (<a href="/web-llvm/docs/api/structs/rpmalloc-thread-statistics-t">rpmalloc_thread_statistics_t</a> * stats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get per-thread statistics.</p>

<p>Definition at line 3489 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a>, <a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#aeded978bd21c13b71d9b0310b5bb09ec">size_class_t::block_count</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#a007fc7dd52ba1f95d9a6ce88f47a614b">size_class_t::block_size</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#af093d9cb1719d72c20f96a9b467590f5">span_t::free_list_limit</a>, <a href="#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a>, <a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a354c0beb35fd982bc4dbd3783b2dd1ff">heap_t::span_free_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a971b2fc3751cade0a6b2f76c92774317">stats</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>

</div>
</div>

### rpmalloc\_usable\_size() {#a7a9f597c853963de259b40e985d81113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_usable_size (void * ptr)</td>
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

<p>Query the usable size of the given memory block (from given pointer to the end of block)</p>

<p>Definition at line 3483 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>.</p>

</div>
</div>

### rpmemalign() {#a61de67ff29b3d0e5d130ac9a7d0d2538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rpmemalign (size_t alignment, size_t size)</td>
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

<p>Allocate a memory block of at least the given size and alignment.</p>

<p>Definition at line 3469 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpposix\_memalign() {#ae6f35022f9384e2a22ed2b96c00995b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rpposix_memalign (void ** memptr, size_t alignment, size_t size)</td>
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

<p>Allocate a memory block of at least the given size and alignment.</p>

<p>Definition at line 3474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rprealloc() {#a8f9643796f1e94fcc804c5c97a7985e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_ALLOCATOR void * rprealloc (void * ptr, size_t size)</td>
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

<p>Reallocate the given block to at least the given size.</p>

<p>Definition at line 3413 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### set\_thread\_heap() {#a4a224c6ef987eb60f3e3be98239109ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void set_thread_heap (<a href="/web-llvm/docs/api/structs/heap-t">heap_t</a> * heap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the current thread heap.</p>

<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="#a84e326ca88dee0bd7ca995727bb52381">get_thread_id</a> and <a href="/web-llvm/docs/api/structs/heap-t/#a436e67271364d132c12f2f5f0d4c79ef">heap_t::owner_thread</a>.</p>


<p>Referenced by <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a> and <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### \_memory\_config {#ae1f1297fe3d143e41deac95ee7a7f8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">rpmalloc_config_t _memory_config</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Configuration.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="#a43c11aa4589298b607afc250133440e4">rpmalloc_config</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_global\_lock {#a1cb428169705ddd63fb35383132dbc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomic32_t _memory_global_lock</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to restrict access to mapping memory for huge pages.</p>

<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_global\_reserve {#a411d5d6c063a099c1a08fa853851b764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* _memory_global_reserve</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global reserved spans.</p>

<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### \_memory\_global\_reserve\_count {#a19d785146ca5053c2da69ad1ec4de94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_global_reserve_count</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global reserved count.</p>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### \_memory\_global\_reserve\_master {#a1d5126b78d2bb31fe3476abcd07dd801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">span_t* _memory_global_reserve_master</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global reserved master.</p>

<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#aa6d37b325f0f3c68f89cdf681681a09f">_rpmalloc_global_set_reserved_spans</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### \_memory\_heap\_id {#af42cdefbf9addf1c268ba19e63c60f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">atomic32_t _memory_heap_id</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Heap ID counter.</p>

<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>.</p>

</div>
</div>

### \_memory\_heap\_reserve\_count {#ada12637cd22672d5ad52ceba482b7f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_heap_reserve_count</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans to keep reserved in each heap.</p>

<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_heaps {#a3e39052a111a2e243645494f1d6ca439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* _memory_heaps[HEAP_ARRAY_SIZE]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All heaps.</p>

<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_huge\_pages {#a4cdf64413eaa3e80f8a1dfe158bd2525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int _memory_huge_pages</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Huge page support.</p>

<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_map\_granularity {#a1e29d8d18139babda354d5d92d46ca02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_map_granularity</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Granularity at which memory pages are mapped by OS.</p>

<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_medium\_size\_limit {#a9641beb0030ad56b2df025775823b2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_medium_size_limit</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run-time size limit of medium blocks.</p>

<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_orphan\_heaps {#ae3a524405e2a853229e95546df284be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">heap_t* _memory_orphan_heaps</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Orphaned heaps.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="#a5bd98ea2cfee2186b2aa2b921450807f">_rpmalloc_heap_orphan</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_page\_size {#a3667b745f7290a10ff5c5a71575533d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_page_size</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memory page size.</p>

<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a6780f79fe39d5c99886e27fccaf4133c">_rpmalloc_span_align_count</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>, <a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a>, <a href="#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_page\_size\_shift {#a9d7ec974d864302bb4f8516859c4b212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_page_size_shift</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Shift to divide by page size.</p>

<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_size\_class {#a33cddb08b9ee0f969cc82dbf9cddb947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_class_t _memory_size_class[SIZE_CLASS_COUNT]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global size classes.</p>

<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### \_memory\_span\_map\_count {#a3d9a7f69f3e3cc2dc7ea18d8c58b274c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t _memory_span_map_count</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans to map in each map call.</p>

<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a6780f79fe39d5c99886e27fccaf4133c">_rpmalloc_span_align_count</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_initialized {#a6414f61e9643ce358f1a33e6a2c6aeaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int _rpmalloc_initialized</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialized flag.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>, <a href="#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a>, <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> and <a href="#a70d0f00495eb8c073a81cd0119fa8429">rpmalloc_linker_reference</a>.</p>

</div>
</div>

### \_rpmalloc\_main\_thread\_id {#aacc7bcb924cab5e38c3fe65c5d0b4ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t _rpmalloc_main_thread_id</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Main thread ID.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a> and <a href="#a53adc7f95e9b3fa3e62ba8f50add0ce9">rpmalloc_set_main_thread</a>.</p>

</div>
</div>

### TLS\_MODEL {#ae1964ae1d59012d78e56e6eedb86c58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">_Thread_local heap_t* _memory_thread_heap TLS_MODEL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### \_\_has\_builtin {#ac3f7c39ed647332bed5de139441f45fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_builtin(b)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build time configurable limits.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### \_memory\_default\_span\_mask {#ada0a343b3498bb882ebd7e0c3caa0935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_default_span_mask&nbsp;&nbsp;&nbsp;(~((uintptr_t)(<a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a> - 1)))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_default\_span\_size {#a04a025a8c2529bc60cb95c78d3948c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_default_span_size&nbsp;&nbsp;&nbsp;(64 * 1024)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global data.</p>


<p>Default span size (64KiB)</p>


<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_default\_span\_size\_shift {#a3dedf1d71cda4a8f3d1f372934ddad30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_default_span_size_shift&nbsp;&nbsp;&nbsp;16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_span\_mask {#a3f784cd2178650b1990ea81980646a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_span_mask&nbsp;&nbsp;&nbsp;<a href="#ada0a343b3498bb882ebd7e0c3caa0935">_memory_default_span_mask</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a0d896198d6c5673397704f9f6bdadbdf">_rpmalloc_heap_unmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_memory\_span\_size {#a58df6aa2dfcdd796fd55cd102fdb177f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_span_size&nbsp;&nbsp;&nbsp;<a href="#a04a025a8c2529bc60cb95c78d3948c52">_memory_default_span_size</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hardwired span size.</p>

<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a6780f79fe39d5c99886e27fccaf4133c">_rpmalloc_span_align_count</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a>, <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### \_memory\_span\_size\_shift {#a09739783c3930851b45151ebfb1dde31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _memory_span_size_shift&nbsp;&nbsp;&nbsp;<a href="#a3dedf1d71cda4a8f3d1f372934ddad30">_memory_default_span_size_shift</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_memcpy\_const {#a8458c6b330ad96112bceb468802e8eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_memcpy_const(x, y, s)&nbsp;&nbsp;&nbsp;memcpy(x, y, s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>.</p>

</div>
</div>

### \_rpmalloc\_memset\_const {#ab88f2b93229da2f2dfdc12f60bcec450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_memset_const(x, y, s)&nbsp;&nbsp;&nbsp;memset(x, y, s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_add {#a4a53d0cfdcf755d4fbbae446a055440c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_add(counter, value)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a> and <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_add\_peak {#a599c57201987cc23a9787a745296e575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_add_peak(counter, value, peak)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a56211c3481cd02195d9bac3c1475cdfb">_rpmalloc_inc_span_statistics</a> and <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_add64 {#a49e532a65b873a6c3315aa769299687c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_add64(counter, value)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a> and <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_dec {#aab22b36fb2408434cc731fb9fe6a5cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_dec(counter)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a> and <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_inc {#ab51bbcd0d9d41ba9c6f4ad547ba77405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_inc(counter)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Statistics related functions (evaluate to nothing when statistics not enabled)</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>, <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#ab3f1ac00b9740730f851945218be4d6a">_rpmalloc_heap_thread_cache_extract</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>, <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a> and <a href="#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_inc\_alloc {#abd4c41e806e09b0468b6db0ae56ed461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_inc_alloc(heap, class_idx)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> and <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_inc\_free {#ab3168e56cb172bc471c410e9daaf7ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_inc_free(heap, class_idx)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>.</p>

</div>
</div>

### \_rpmalloc\_stat\_sub {#a829d3a1ca51d0ba687990a8111940c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _rpmalloc_stat_sub(counter, value)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a> and <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>.</p>

</div>
</div>

### DEFAULT\_SPAN\_MAP\_COUNT {#af8803f4eab133ac4c823104577553d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFAULT_SPAN_MAP_COUNT&nbsp;&nbsp;&nbsp;64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default number of spans to map in call to map more virtual memory (default values yield 4MiB here)</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### DISABLE\_UNMAP {#ae777722890578ce47ae32f908b4005b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DISABLE_UNMAP&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable unmapping memory pages (also enables unlimited cache)</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_ADAPTIVE\_THREAD\_CACHE {#a74abd212deb430c20e3bbf5cadbe075c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_ADAPTIVE_THREAD_CACHE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable adaptive thread cache size based on use heuristics.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_ADAPTIVE\_THREAD\_CACHE {#a74abd212deb430c20e3bbf5cadbe075c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_ADAPTIVE_THREAD_CACHE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable adaptive thread cache size based on use heuristics.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_ASSERTS {#ad616b76a55f585c9f7f75af50575911a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_ASSERTS&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable asserts.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_GLOBAL\_CACHE {#a39fd01af4bfcf583a5039c34d23e2bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_GLOBAL_CACHE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable global cache shared between all threads, requires thread cache.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_OVERRIDE {#ac2f574bcf90e64a0529171141caef930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_OVERRIDE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Override standard library malloc/free and new/delete entry points.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_PRELOAD {#ae7896aa9035235aefac2ab04a90c9d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_PRELOAD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support preloading.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_STATISTICS {#aab186ebd3fdc6562bb8aadad4ccce3ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_STATISTICS&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable statistics collection.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_THREAD\_CACHE {#a69503d4619673c88e0882f291eb6d86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_THREAD_CACHE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable per-thread cache.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_UNLIMITED\_CACHE {#afc6937f23f518f51f693f7d034100f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_UNLIMITED_CACHE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable unlimited global cache (no unmapping until finalization)</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_UNLIMITED\_CACHE {#afc6937f23f518f51f693f7d034100f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_UNLIMITED_CACHE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable unlimited global cache (no unmapping until finalization)</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### ENABLE\_VALIDATE\_ARGS {#a53baabd23f5ba123eb9a9d6121faed9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_VALIDATE_ARGS&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable validation of args to public entry points.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### EXPECTED {#a90593dceacf0c04f14d084bed7e7eabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EXPECTED(x)&nbsp;&nbsp;&nbsp;__builtin_expect((x), 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a> and <a href="#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>.</p>

</div>
</div>

### FORCEINLINE {#a724fb9f82013c782db5c3c12ea36aac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FORCEINLINE&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> __attribute__((__always_inline__))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Platform and arch specifics.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#af327588f7260778f453d9a212396e0e0">atomic_add32</a>, <a href="#a481f7733c3d6469b66e9a746e0afb0e9">atomic_add64</a>, <a href="#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a>, <a href="#a303f700546874a81e694eda44cc3174d">atomic_cas_ptr</a>, <a href="#a4f0dc3c548801773a4da1c96f39b04c9">atomic_decr32</a>, <a href="#a00bbb337491324377139681240567490">atomic_exchange_ptr_acquire</a>, <a href="#a1fe9c932f58e2baffed3ea33fd299691">atomic_incr32</a>, <a href="#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a>, <a href="#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>, <a href="#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="#ae261e72f93968b03a76ada7a6b150965">atomic_store_ptr</a> and <a href="#a94d4ba8d2181723f35b45da39c91d8ab">atomic_store_ptr_release</a>.</p>

</div>
</div>

### GLOBAL\_CACHE\_MULTIPLIER {#aec9c1ea6434b5703d7b6e01cfffd1261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GLOBAL_CACHE_MULTIPLIER&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplier for global cache.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### HEAP\_ARRAY\_SIZE {#ac7e4a352a230ef04d4372db43a454b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEAP_ARRAY_SIZE&nbsp;&nbsp;&nbsp;47</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of heap hashmap.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a58f109a58b8e38970cda041f4ea96772">_rpmalloc_heap_initialize</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> and <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### INVALID\_POINTER {#a95d666267d99d22454086d5fa0390bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INVALID_POINTER&nbsp;&nbsp;&nbsp;((void *)((uintptr_t) - 1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a> and <a href="#af2ca2fcf7e544c9458ef49057a40b78e">_rpmalloc_span_extract_free_list_deferred</a>.</p>

</div>
</div>

### LARGE\_CLASS\_COUNT {#a04406da3f5ff4e24f155c97591678ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LARGE_CLASS_COUNT&nbsp;&nbsp;&nbsp;63</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of large block size classes.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#acf65e6242a6d42e38959bac148c7aadc">_rpmalloc_heap_extract_new_span</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>, <a href="#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### LARGE\_SIZE\_LIMIT {#a6866e2b7c1e8f60d6c74ea8fba6be44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LARGE_SIZE_LIMIT&nbsp;&nbsp;&nbsp;  ((<a href="#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a> * <a href="#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>) - <a href="#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum size of a large block.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>.</p>

</div>
</div>

### MAX\_THREAD\_SPAN\_CACHE {#aebbd8639c3b627f526bd557e065f1c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_THREAD_SPAN_CACHE&nbsp;&nbsp;&nbsp;400</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans in thread cache.</p>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>.</p>

</div>
</div>

### MAX\_THREAD\_SPAN\_LARGE\_CACHE {#a51b78975d481805f29847ad91c77d6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_THREAD_SPAN_LARGE_CACHE&nbsp;&nbsp;&nbsp;100</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans in thread cache for large spans (must be greater than LARGE_CLASS_COUNT / 2)</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>.</p>

</div>
</div>

### MEDIUM\_CLASS\_COUNT {#a554df4bc024ffaa8328e6ef37cec5c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEDIUM_CLASS_COUNT&nbsp;&nbsp;&nbsp;61</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of medium block size classes.</p>

<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### MEDIUM\_GRANULARITY {#a0cbe158c682e307dc9372ee5a0b5167a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEDIUM_GRANULARITY&nbsp;&nbsp;&nbsp;512</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Granularity of a medium allocation block.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### MEDIUM\_GRANULARITY\_SHIFT {#a95449a66565995789e144cfc3f538261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEDIUM_GRANULARITY_SHIFT&nbsp;&nbsp;&nbsp;9</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Medium granularity shift count.</p>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>.</p>

</div>
</div>

### MEDIUM\_SIZE\_LIMIT {#aecb085054ab2d682b41748925519c084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MEDIUM_SIZE_LIMIT&nbsp;&nbsp;&nbsp;  (<a href="#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a> + (<a href="#a0cbe158c682e307dc9372ee5a0b5167a">MEDIUM_GRANULARITY</a> * <a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum size of a medium block.</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### PLATFORM\_POSIX {#ad0092e018a32f308bad3efeaa795c92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PLATFORM_POSIX&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### PLATFORM\_WINDOWS {#a20cd3c4775f1897fb5658d2dc61382c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PLATFORM_WINDOWS&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### pointer\_diff {#af51a6ed47e80b1b57187f1d5be6c8b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define pointer_diff(first, second)&nbsp;&nbsp;&nbsp;  (ptrdiff_t)((<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)(first) - (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)(second))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>.</p>

</div>
</div>

### pointer\_offset {#ab4225911698b67188e1538c334cfe16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define pointer_offset(ptr, ofs)&nbsp;&nbsp;&nbsp;(void *)((char *)(ptr) + (ptrdiff_t)(ofs))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="#a80ccc3407de6606e73356a7c4e2dc6ee">_rpmalloc_global_get_reserved_spans</a>, <a href="#a648de3a42660a0567102d78aa59ceded">_rpmalloc_heap_allocate_new</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="#ae3ba0ad3b30a2fa8c63ff06218750cd0">_rpmalloc_span_map</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#afaa0ba431359c9bab42909cfc9248b63">_rpmalloc_span_map_from_reserve</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> and <a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a>.</p>

</div>
</div>

### rpmalloc\_assert {#ad008ddf766a4f56fbde2edf2c51d9a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rpmalloc_assert(truth, message)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="#a61e3c97b4484c79f1edd1757dc3d0e46">_rpmalloc_deallocate_huge</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a1b9ab55b2401b2d4240bbca4b313f6a2">_rpmalloc_heap_release</a>, <a href="#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a49d22808308e599742e41ef2d4671cfa">_rpmalloc_span_double_link_list_pop_head</a>, <a href="#aec7913670102d551e3fd60509cd381a3">_rpmalloc_span_double_link_list_remove</a>, <a href="#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="#ade7fb930b30a5a8bd04ecc97cad60e6b">_rpmalloc_span_is_fully_utilized</a>, <a href="#a2a4e560819e42925aaa4494511aae43d">_rpmalloc_span_map_aligned_count</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a>, <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>, <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>, <a href="#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="#addf543f30c5eefc1dded60025c78a816">free_list_partial_init</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a>, <a href="#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### rpmalloc\_assume {#a194bc284667af78821354e7e3c45049e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rpmalloc_assume(cond)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>.</p>

</div>
</div>

### SIZE\_CLASS\_COUNT {#aa74d427b2b9955ff2d9719693d9fc80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIZE_CLASS_COUNT&nbsp;&nbsp;&nbsp;(<a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> + <a href="#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of small + medium size classes.</p>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a2a1e3b11c0a8fc714d6def51250c6906">_rpmalloc_heap_finalize</a>, <a href="#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a62b31eca2760e37676716c54c5b64947">_rpmalloc_span_release_to_cache</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>, <a href="#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### SIZE\_CLASS\_HUGE {#a284460248778c94b6ee9ea1529299439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIZE_CLASS_HUGE&nbsp;&nbsp;&nbsp;((uint32_t) - 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#ac8a96725f034c08fdff774eb54785947">_rpmalloc_deallocate_defer_free_span</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a> and <a href="#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### SIZE\_CLASS\_LARGE {#a3f84dd23eb0ef3cf54aeb6afff0618ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIZE_CLASS_LARGE&nbsp;&nbsp;&nbsp;<a href="#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#af44e92f7ed42c434bd33a0ae98210a3f">_rpmalloc_heap_cache_adopt_deferred</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a> and <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>.</p>

</div>
</div>

### SMALL\_CLASS\_COUNT {#afef7a20458b75404cdbba364a751694a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SMALL_CLASS_COUNT&nbsp;&nbsp;&nbsp;65</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of small block size classes.</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### SMALL\_GRANULARITY {#a000afcda168a6fd19a9435e049508463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SMALL_GRANULARITY&nbsp;&nbsp;&nbsp;16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Preconfigured limits and sizes.</p>


<p>Granularity of a small allocation block (must be power of two)</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### SMALL\_GRANULARITY\_SHIFT {#a66893939b9053e9bf8a97a5f50bc773a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SMALL_GRANULARITY_SHIFT&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Small granularity shift count.</p>

<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>.</p>

</div>
</div>

### SMALL\_SIZE\_LIMIT {#aecf578949f89fb109c5f6f527a2dc49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SMALL_SIZE_LIMIT&nbsp;&nbsp;&nbsp;(<a href="#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a> * (<a href="#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a> - 1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum size of a small block.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### SPAN\_FLAG\_ALIGNED\_BLOCKS {#ad1094486bd3e5ee282e7a4ce7de9c7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SPAN_FLAG_ALIGNED_BLOCKS&nbsp;&nbsp;&nbsp;4U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating span has blocks with increased alignment.</p>

<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a> and <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>.</p>

</div>
</div>

### SPAN\_FLAG\_MASTER {#a98c82279e204e31a5dc89b64d2c6c27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SPAN_FLAG_MASTER&nbsp;&nbsp;&nbsp;1U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating span is the first (master) span of a split superspan.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#ad5eb163989618d4ea0eff254cdbdd596">_rpmalloc_span_initialize</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### SPAN\_FLAG\_SUBSPAN {#a2fcaea32cf5846f1f5b40a882175dbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SPAN_FLAG_SUBSPAN&nbsp;&nbsp;&nbsp;2U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating span is a secondary (sub) span of a split superspan.</p>

<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a573fc7baab7be24c6bac115b7f62192f">_rpmalloc_deallocate_large</a>, <a href="#a91bf3ee061b188b8a650fbac9babef4a">_rpmalloc_span_mark_as_subspan_unless_master</a> and <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### SPAN\_FLAG\_UNMAPPED\_MASTER {#a132ac3786920f0bf24b2d2f7c73cf863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SPAN_FLAG_UNMAPPED_MASTER&nbsp;&nbsp;&nbsp;8U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating an unmapped master span.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a1b31ff8fa0abcdb205dadd8afc026014">_rpmalloc_span_unmap</a>.</p>

</div>
</div>

### SPAN\_HEADER\_SIZE {#a645356809d937167848705edabde7d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SPAN_HEADER_SIZE&nbsp;&nbsp;&nbsp;128</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of a span header (must be a multiple of SMALL_GRANULARITY and a power of two)</p>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="#a7fdcd37f930a06ca527ab10334bf1d1e">_rpmalloc_deallocate_small_or_medium</a>, <a href="#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a> and <a href="#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### THREAD\_SPAN\_CACHE\_TRANSFER {#a24ad9380461f94f601227da3fe3676da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREAD_SPAN_CACHE_TRANSFER&nbsp;&nbsp;&nbsp;64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans to transfer between thread and global cache.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a> and <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a>.</p>

</div>
</div>

### THREAD\_SPAN\_LARGE\_CACHE\_TRANSFER {#a2e9cc04738eb37814086f557943373d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREAD_SPAN_LARGE_CACHE_TRANSFER&nbsp;&nbsp;&nbsp;6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans to transfer between thread and global cache for large spans.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a> and <a href="#abeb50100f90c725f1e16944cd67e9f00">_rpmalloc_heap_global_cache_extract</a>.</p>

</div>
</div>

### TLS\_MODEL {#a3cf2ef5bd78a81c297328a5534f0ddf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLS_MODEL&nbsp;&nbsp;&nbsp;__attribute__((tls_model("initial-exec")))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Thread local heap and ID.</p>


<p>Current thread heap</p>


<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### UNEXPECTED {#af8f864d9fe0055b43dc8034fe9060630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNEXPECTED(x)&nbsp;&nbsp;&nbsp;__builtin_expect((x), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Referenced by <a href="#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>, <a href="#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a> and <a href="#abdbbc20ab63d76c1709722f3f2305610">_rpmalloc_heap_cache_insert</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
