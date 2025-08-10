---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `rpmalloc.h` File



## Included Headers

<div class="doxyIncludesList">#include &lt;stddef.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/rpmalloc-global-statistics-t">rpmalloc_global_statistics_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/rpmalloc-thread-statistics-t">rpmalloc_thread_statistics_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct rpmalloc_global_statistics_t <a href="#a8ed79e533ed034f305cf34cff57bd4a7">rpmalloc_global_statistics_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct rpmalloc_thread_statistics_t <a href="#aaef706ac2be95d5a4f00bfab78128234">rpmalloc_thread_statistics_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct rpmalloc_config_t <a href="#afea1bd62321a935b2ce6e268c7bcaf10">rpmalloc_config_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bbaa4b2e6a5524d4ba62a6c9c939df">rpmalloc_initialize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize allocator with default configuration. <a href="#a24bbaa4b2e6a5524d4ba62a6c9c939df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2159e8de05a62e3697024fd2aec1a8c2">rpmalloc_initialize_config</a> (const rpmalloc_config_t *config)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize allocator with given configuration. <a href="#a2159e8de05a62e3697024fd2aec1a8c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc56478dec8242e140e2cc3792b23f8">rpmalloc_config</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get allocator configuration. <a href="#a6dc56478dec8242e140e2cc3792b23f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1ba6b797d81b14895f0a2114d78476">rpmalloc_finalize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize allocator. <a href="#a1c1ba6b797d81b14895f0a2114d78476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4166a6bd4ba8707f381910f73a0d858e">rpmalloc_thread_initialize</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize allocator for calling thread. <a href="#a4166a6bd4ba8707f381910f73a0d858e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01edf01df2797283168e0eff740390b6">rpmalloc_thread_finalize</a> (int release_caches)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize allocator for calling thread. <a href="#a01edf01df2797283168e0eff740390b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe32b20a0a8c471b85225975f22de7b0">rpmalloc_thread_collect</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform deferred deallocations pending for the calling thread heap. <a href="#afe32b20a0a8c471b85225975f22de7b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651de9989dde0bba2f3eac7d4c09f97a">rpmalloc_is_thread_initialized</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query if allocator is initialized for calling thread. <a href="#a651de9989dde0bba2f3eac7d4c09f97a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c086aa3f5d9fbc936fea87cfa62e2e">rpmalloc_thread_statistics</a> (rpmalloc_thread_statistics_t *stats)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get per-thread statistics. <a href="#a29c086aa3f5d9fbc936fea87cfa62e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21dbb043c42cbe1bfd7ba3f1fe012f5f">rpmalloc_global_statistics</a> (rpmalloc_global_statistics_t *stats)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get global statistics. <a href="#a21dbb043c42cbe1bfd7ba3f1fe012f5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c33a5925ba558f8dc534c668e344db1">rpmalloc_dump_statistics</a> (void *file)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump all statistics in human readable format to file (should be a FILE*) <a href="#a3c33a5925ba558f8dc534c668e344db1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d759881b9417a87c22b6d554a9e0c0">rpmalloc</a> (size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE(1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size. <a href="#a89d759881b9417a87c22b6d554a9e0c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608a7c1ac37d930b1d82748d98009149">rpfree</a> (void *ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free the given memory block. <a href="#a608a7c1ac37d930b1d82748d98009149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6640211f01727c7df7fe2bd876dbfc70">rpcalloc</a> (size_t num, size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE2(1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and zero initialize it. <a href="#a6640211f01727c7df7fe2bd876dbfc70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void <a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2ce317d77869e70d3b22f20ce3938d">rprealloc</a> (void *ptr, size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE(2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocate the given block to at least the given size. <a href="#adb2ce317d77869e70d3b22f20ce3938d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef34737cfa8ffaf5860d1512392911a">rpaligned_realloc</a> (void *ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE(3)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reallocate the given block to at least the given size and alignment,. <a href="#a2ef34737cfa8ffaf5860d1512392911a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3dfc775f84e5ba1c20fb4c3b2e36888">rpaligned_alloc</a> (size_t alignment, size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE(2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#ab3dfc775f84e5ba1c20fb4c3b2e36888">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afacba300cb4003f3f47f2e2ef5dd4085">rpaligned_calloc</a> (size_t alignment, size_t num, size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE2(2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment, and zero initialize it. <a href="#afacba300cb4003f3f47f2e2ef5dd4085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void <a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa443ec6d7524561a060f1f8971d47646">rpmemalign</a> (size_t alignment, size_t size) RPMALLOC_ATTRIB_MALLOC RPMALLOC_ATTRIB_ALLOC_SIZE(2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#aa443ec6d7524561a060f1f8971d47646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f43fd4642bf70f3c43ed24694611bc3">rpposix_memalign</a> (void **memptr, size_t alignment, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a memory block of at least the given size and alignment. <a href="#a3f43fd4642bf70f3c43ed24694611bc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b4c800cec1406d162b8a7787587a46">rpmalloc_usable_size</a> (void *ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the usable size of the given memory block (from given pointer to the end of block) <a href="#a52b4c800cec1406d162b8a7787587a46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552c801b7cccad28e9b009660a4dbaa3">rpmalloc_linker_reference</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dummy empty function for forcing linker symbol inclusion. <a href="#a552c801b7cccad28e9b009660a4dbaa3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec208006a1707aadcfb577cd0e05014">RPMALLOC_ATTRIB_MALLOC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78a4db7a8c062ad908eb3756e88cc8a">RPMALLOC_ATTRIB_ALLOC_SIZE</a>(size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a97eca6d8747153e041a7acbdf2d2d4">RPMALLOC_ATTRIB_ALLOC_SIZE2</a>(count, size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6929e86935eadfa5b1dc9c9ff2cd60">RPMALLOC_CDECL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dccadaf86473444d85530d361d4109d">RPMALLOC_CONFIGURABLE</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define RPMALLOC_CONFIGURABLE to enable configuring sizes. Will introduce. <a href="#a6dccadaf86473444d85530d361d4109d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20456aea27df9da3c00efecb1dba3b4">RPMALLOC_FIRST_CLASS_HEAPS</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define RPMALLOC_FIRST_CLASS_HEAPS to enable heap based API (rpmalloc_heap_* functions). <a href="#aa20456aea27df9da3c00efecb1dba3b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affda05352198b9ef86d42be851a1349f">RPMALLOC_NO_PRESERVE</a>&nbsp;&nbsp;&nbsp;1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to rpaligned_realloc to not preserve content in reallocation. <a href="#affda05352198b9ef86d42be851a1349f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3774a093749aeca1d4e387b11e79395">RPMALLOC_GROW_OR_FAIL</a>&nbsp;&nbsp;&nbsp;2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to rpaligned_realloc to fail and return null pointer if grow cannot be done in-place,. <a href="#ab3774a093749aeca1d4e387b11e79395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### rpmalloc\_config\_t {#afea1bd62321a935b2ce6e268c7bcaf10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct rpmalloc_config_t rpmalloc_config_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### rpmalloc\_global\_statistics\_t {#a8ed79e533ed034f305cf34cff57bd4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct rpmalloc_global_statistics_t rpmalloc_global_statistics_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### rpmalloc\_thread\_statistics\_t {#aaef706ac2be95d5a4f00bfab78128234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct rpmalloc_thread_statistics_t rpmalloc_thread_statistics_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### rpaligned\_alloc() {#ab3dfc775f84e5ba1c20fb4c3b2e36888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpaligned_alloc (size_t alignment, size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of at least the given size and alignment.</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3438 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae572e25a23de1a9793b4e5b1ec0550b1">rpaligned_calloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61de67ff29b3d0e5d130ac9a7d0d2538">rpmemalign</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae6f35022f9384e2a22ed2b96c00995b2">rpposix_memalign</a>.</p>

</div>
</div>

### rpaligned\_calloc() {#afacba300cb4003f3f47f2e2ef5dd4085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpaligned_calloc (size_t alignment, size_t num, size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of at least the given size and alignment, and zero initialize it.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>References <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a>, <a href="#aaec208006a1707aadcfb577cd0e05014">RPMALLOC_ATTRIB_MALLOC</a>, <a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpaligned\_realloc() {#a2ef34737cfa8ffaf5860d1512392911a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpaligned_realloc (void * ptr, size_t alignment, size_t size, size_t oldsize, unsigned int flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reallocate the given block to at least the given size and alignment,.</p>

<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3424 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpcalloc() {#a6640211f01727c7df7fe2bd876dbfc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpcalloc (size_t num, size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a memory block of at least the given size and zero initialize it.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>References <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a>, <a href="#aaec208006a1707aadcfb577cd0e05014">RPMALLOC_ATTRIB_MALLOC</a>, <a href="#a2d18f870b8bad81e931c8c0a01e3672b">RPMALLOC_EXPORT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpfree() {#a608a7c1ac37d930b1d82748d98009149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpfree (void * ptr)</td>
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

<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3385 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae324fa158db468143544693dfe539800">_rpmalloc_deallocate</a>.</p>

</div>
</div>

### rpmalloc() {#a89d759881b9417a87c22b6d554a9e0c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpmalloc (size_t size)</td>
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

<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3374 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpmalloc\_config() {#a6dc56478dec8242e140e2cc3792b23f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT const rpmalloc_config_t * rpmalloc_config (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get allocator configuration.</p>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>.</p>

</div>
</div>

### rpmalloc\_dump\_statistics() {#a3c33a5925ba558f8dc534c668e344db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_dump_statistics (void * file)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump all statistics in human readable format to file (should be a FILE*)</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3694 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a440c6f31099f3836f7beb5e47d14fb2d">global_cache_t::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a8bb140aee00ffae527f7c0706d98c3d1">global_cache_t::overflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>.</p>

</div>
</div>

### rpmalloc\_finalize() {#a1c1ba6b797d81b14895f0a2114d78476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_finalize (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize allocator.</p>


<p>Finalize allocator.</p>


<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3293 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a411d5d6c063a099c1a08fa853851b764">_memory_global_reserve</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a19d785146ca5053c2da69ad1ec4de94c">_memory_global_reserve_count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1d5126b78d2bb31fe3476abcd07dd801">_memory_global_reserve_master</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2f7a67a3403fd19a70e7a0418714af57">_rpmalloc_heap_global_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af327588f7260778f453d9a212396e0e0">atomic_add32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a13ccab5430ace95c471aacf1fab0fcd6">heap_t::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac7e4a352a230ef04d4372db43a454b7f">HEAP_ARRAY_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a74b47a0eacf313fe421d32379a2b942c">heap_t::next_heap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6e5fc3857f84254caa88503e02bf163c">rpmalloc_thread_finalize</a>.</p>

</div>
</div>

### rpmalloc\_global\_statistics() {#a21dbb043c42cbe1bfd7ba3f1fe012f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_global_statistics (<a href="/web-llvm/docs/api/structs/rpmalloc-global-statistics-t">rpmalloc_global_statistics_t</a> * stats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get global statistics.</p>

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3572 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a335307d78e0ff77d4da9cf42156803ec">_rpmalloc_spin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2071bf7ebae50eced1f16b359f9d5c7d">atomic_cas32_acquire</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a440c6f31099f3836f7beb5e47d14fb2d">global_cache_t::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a9c0563645d0d1fd53044a9c00dad6dc0">global_cache_t::lock</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/global-cache-t/#a8bb140aee00ffae527f7c0706d98c3d1">global_cache_t::overflow</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a971b2fc3751cade0a6b2f76c92774317">stats</a>.</p>

</div>
</div>

### rpmalloc\_initialize() {#a24bbaa4b2e6a5524d4ba62a6c9c939df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT int rpmalloc_initialize (void)</td>
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

<p>Initialize allocator with default configuration.</p>


<p>Initialize allocator with default configuration.</p>


<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3047 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>.</p>

</div>
</div>

### rpmalloc\_initialize\_config() {#a2159e8de05a62e3697024fd2aec1a8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT int rpmalloc_initialize_config (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/rpmalloc-config-t">rpmalloc_config_t</a> * config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize allocator with given configuration.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3055 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae1f1297fe3d143e41deac95ee7a7f8d4">_memory_config</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ada0a343b3498bb882ebd7e0c3caa0935">_memory_default_span_mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a04a025a8c2529bc60cb95c78d3948c52">_memory_default_span_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3dedf1d71cda4a8f3d1f372934ddad30">_memory_default_span_size_shift</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1cb428169705ddd63fb35383132dbc40">_memory_global_lock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ada12637cd22672d5ad52ceba482b7f5c">_memory_heap_reserve_count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3e39052a111a2e243645494f1d6ca439">_memory_heaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4cdf64413eaa3e80f8a1dfe158bd2525">_memory_huge_pages</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a1e29d8d18139babda354d5d92d46ca02">_memory_map_granularity</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9641beb0030ad56b2df025775823b2af">_memory_medium_size_limit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae3a524405e2a853229e95546df284be2">_memory_orphan_heaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3667b745f7290a10ff5c5a71575533d9">_memory_page_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9d7ec974d864302bb4f8516859c4b212">_memory_page_size_shift</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3d9a7f69f3e3cc2dc7ea18d8c58b274c">_memory_span_map_count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3f784cd2178650b1990ea81980646a3b">_memory_span_mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a09739783c3930851b45151ebfb1dde31">_memory_span_size_shift</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a223c890fd871bff9081258f6520fc8a9">_rpmalloc_adjust_size_class</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a375befcec19545c40cb27c22512501bb">_rpmalloc_heap_release_raw_fc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ab88f2b93229da2f2dfdc12f60bcec450">_rpmalloc_memset_const</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa1ee77cdccf0341222f64395d0be2626">atomic_store32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2a87a6060d5387fe8491a00600073687">atomic_store32_release</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#af8803f4eab133ac4c823104577553d78">DEFAULT_SPAN_MAP_COUNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a554df4bc024ffaa8328e6ef37cec5c77">MEDIUM_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0cbe158c682e307dc9372ee5a0b5167a">MEDIUM_GRANULARITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aecb085054ab2d682b41748925519c084">MEDIUM_SIZE_LIMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2e1b5bd9424a1d1082d4bd670b1a0be6">rc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ad008ddf766a4f56fbde2edf2c51d9a87">rpmalloc_assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a70d0f00495eb8c073a81cd0119fa8429">rpmalloc_linker_reference</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a85a64540090a42380ee6d969ec1897c1">rpmalloc_thread_initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afef7a20458b75404cdbba364a751694a">SMALL_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a000afcda168a6fd19a9435e049508463">SMALL_GRANULARITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aecf578949f89fb109c5f6f527a2dc49d">SMALL_SIZE_LIMIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a645356809d937167848705edabde7d44">SPAN_HEADER_SIZE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a>.</p>

</div>
</div>

### rpmalloc\_is\_thread\_initialized() {#a651de9989dde0bba2f3eac7d4c09f97a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT int rpmalloc_is_thread_initialized (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query if allocator is initialized for calling thread.</p>

<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a>.</p>

</div>
</div>

### rpmalloc\_linker\_reference() {#a552c801b7cccad28e9b009660a4dbaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_linker_reference (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dummy empty function for forcing linker symbol inclusion.</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3992 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6414f61e9643ce358f1a33e6a2c6aeaa">_rpmalloc_initialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### rpmalloc\_thread\_collect() {#afe32b20a0a8c471b85225975f22de7b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_thread_collect (void)</td>
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

<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3487 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>

</div>
</div>

### rpmalloc\_thread\_finalize() {#a01edf01df2797283168e0eff740390b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_thread_finalize (int release_caches)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize allocator for calling thread.</p>


<p>Finalize allocator for calling thread.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3356 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa378f245dd9ff587c375db42472ac954">_rpmalloc_heap_release_raw</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aff58cf54f7ebc5d3d71a2ad80a0dab94">rpmalloc_finalize</a>.</p>

</div>
</div>

### rpmalloc\_thread\_initialize() {#a4166a6bd4ba8707f381910f73a0d858e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_thread_initialize (void)</td>
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

<p>Initialize allocator for calling thread.</p>


<p>Initialize allocator for calling thread.</p>


<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3342 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0b2f5071d70703ea5cc1e670361a8cc1">_rpmalloc_heap_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ab51bbcd0d9d41ba9c6f4ad547ba77405">_rpmalloc_stat_inc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4a224c6ef987eb60f3e3be98239109ec">set_thread_heap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a995ec0e5a8f40e3fb178abab89dc7fd5">rpmalloc_initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

### rpmalloc\_thread\_statistics() {#a29c086aa3f5d9fbc936fea87cfa62e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT void rpmalloc_thread_statistics (<a href="/web-llvm/docs/api/structs/rpmalloc-thread-statistics-t">rpmalloc_thread_statistics_t</a> * stats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get per-thread statistics.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3489 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a33cddb08b9ee0f969cc82dbf9cddb947">_memory_size_class</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a58df6aa2dfcdd796fd55cd102fdb177f">_memory_span_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a083ecd4af0f476009595e8ee78cf2ac0">atomic_load64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a912154b2fc1b8fc6d74c6364523f1f61">atomic_load_ptr</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#aeded978bd21c13b71d9b0310b5bb09ec">size_class_t::block_count</a>, <a href="/web-llvm/docs/api/structs/size-class-t/#a007fc7dd52ba1f95d9a6ce88f47a614b">size_class_t::block_size</a>, <a href="/web-llvm/docs/api/structs/span-cache-t/#a894a66f329862f01de7619aee1954d19">span_cache_t::count</a>, <a href="/web-llvm/docs/api/structs/span-t/#a85527ad364915bcb39b7d421524d0bd6">span_t::free_list</a>, <a href="/web-llvm/docs/api/structs/span-t/#af093d9cb1719d72c20f96a9b467590f5">span_t::free_list_limit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a149fe6706f44dfb65fbdbba32c926476">get_thread_heap_raw</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a04406da3f5ff4e24f155c97591678ed9">LARGE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/structs/span-t/#ad842dbc76a30fb5beee77a2d773a3e91">span_t::list_size</a>, <a href="/web-llvm/docs/api/structs/span-t/#ac62e0e77eb38ebff4443eb5db3ccd45c">span_t::next</a>, <a href="/web-llvm/docs/api/structs/heap-size-class-t/#af829c49d9fc4d933c14113ba0d694e7c">heap_size_class_t::partial_span</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a70f9a96b9071ccb6642894f5a7f56432">heap_t::size_class</a>, <a href="/web-llvm/docs/api/structs/span-t/#a5a977febdd2e9ae15bcf66f83d0cf817">span_t::size_class</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa74d427b2b9955ff2d9719693d9fc80e">SIZE_CLASS_COUNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a284460248778c94b6ee9ea1529299439">SIZE_CLASS_HUGE</a>, <a href="/web-llvm/docs/api/structs/span-t/#ae77d9a2cdd2a2fd46e3b27739d6c88cc">span_t::span_count</a>, <a href="/web-llvm/docs/api/structs/heap-t/#a354c0beb35fd982bc4dbd3783b2dd1ff">heap_t::span_free_deferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a971b2fc3751cade0a6b2f76c92774317">stats</a> and <a href="/web-llvm/docs/api/structs/span-t/#abf4fa6f8f0e7baff0d6a7a96df58bcca">span_t::used_count</a>.</p>

</div>
</div>

### rpmalloc\_usable\_size() {#a52b4c800cec1406d162b8a7787587a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT size_t rpmalloc_usable_size (void * ptr)</td>
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

<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3483 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#adc5743a6b15192da5b7e023f85360208">_rpmalloc_usable_size</a>.</p>

</div>
</div>

### rpmemalign() {#aa443ec6d7524561a060f1f8971d47646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rpmemalign (size_t alignment, size_t size)</td>
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

<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3469 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>, <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rpposix\_memalign() {#a3f43fd4642bf70f3c43ed24694611bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT int rpposix_memalign (void ** memptr, size_t alignment, size_t size)</td>
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

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### rprealloc() {#adb2ce317d77869e70d3b22f20ce3938d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void RPMALLOC_EXPORT RPMALLOC_ALLOCATOR void * rprealloc (void * ptr, size_t size)</td>
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

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>, definition at line 3413 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c">rpmalloc.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb9f599f45127d8ba79cf413ad35d90c">get_thread_heap</a>, <a href="#a85561f3ac6a729bf480cdf706d6c75dc">RPMALLOC_ALLOCATOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### RPMALLOC\_ALLOCATOR {#a85561f3ac6a729bf480cdf706d6c75dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_ALLOCATOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>, <a href="#afacba300cb4003f3f47f2e2ef5dd4085">rpaligned_calloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a>, <a href="#a6640211f01727c7df7fe2bd876dbfc70">rpcalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2727f400656ed5d5857d7a6e1e05b61b">rpmalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61de67ff29b3d0e5d130ac9a7d0d2538">rpmemalign</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8f9643796f1e94fcc804c5c97a7985e9">rprealloc</a>.</p>

</div>
</div>

### RPMALLOC\_ATTRIB\_ALLOC\_SIZE {#aa78a4db7a8c062ad908eb3756e88cc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_ATTRIB_ALLOC_SIZE(size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### RPMALLOC\_ATTRIB\_ALLOC\_SIZE2 {#a5a97eca6d8747153e041a7acbdf2d2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_ATTRIB_ALLOC_SIZE2(count, size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### RPMALLOC\_ATTRIB\_MALLOC {#aaec208006a1707aadcfb577cd0e05014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_ATTRIB_MALLOC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>Referenced by <a href="#afacba300cb4003f3f47f2e2ef5dd4085">rpaligned_calloc</a> and <a href="#a6640211f01727c7df7fe2bd876dbfc70">rpcalloc</a>.</p>

</div>
</div>

### RPMALLOC\_CDECL {#a5c6929e86935eadfa5b1dc9c9ff2cd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_CDECL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### RPMALLOC\_CONFIGURABLE {#a6dccadaf86473444d85530d361d4109d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_CONFIGURABLE&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define RPMALLOC_CONFIGURABLE to enable configuring sizes. Will introduce.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### RPMALLOC\_EXPORT {#a2d18f870b8bad81e931c8c0a01e3672b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_EXPORT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>Referenced by <a href="#afacba300cb4003f3f47f2e2ef5dd4085">rpaligned_calloc</a> and <a href="#a6640211f01727c7df7fe2bd876dbfc70">rpcalloc</a>.</p>

</div>
</div>

### RPMALLOC\_FIRST\_CLASS\_HEAPS {#aa20456aea27df9da3c00efecb1dba3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_FIRST_CLASS_HEAPS&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define RPMALLOC_FIRST_CLASS_HEAPS to enable heap based API (rpmalloc_heap_* functions).</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### RPMALLOC\_GROW\_OR\_FAIL {#ab3774a093749aeca1d4e387b11e79395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_GROW_OR_FAIL&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to rpaligned_realloc to fail and return null pointer if grow cannot be done in-place,.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>.</p>

</div>
</div>

### RPMALLOC\_NO\_PRESERVE {#affda05352198b9ef86d42be851a1349f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RPMALLOC_NO_PRESERVE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to rpaligned_realloc to not preserve content in reallocation.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
