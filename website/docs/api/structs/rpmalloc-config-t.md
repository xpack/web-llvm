---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/rpmalloc-config-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `rpmalloc_config_t` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct rpmalloc_config_t { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">Support/rpmalloc/rpmalloc.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcdb0bb951b75755ad9f6fa95c5fb89">memory_map</a>)(size_t size, size_t *offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map memory pages for the given number of bytes. <a href="#adbcdb0bb951b75755ad9f6fa95c5fb89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10fb22a2f8775aafd70b1c79f6b80630">memory_unmap</a>)(void *address, size_t size, size_t offset, size_t release)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmap the memory pages starting at address and spanning the given number of bytes. <a href="#a10fb22a2f8775aafd70b1c79f6b80630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc0e407dff5707e6e199ba21f7afbc6">error_callback</a>)(const char *message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when an assert fails, if asserts are enabled. <a href="#a4bc0e407dff5707e6e199ba21f7afbc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35106c441d799201ae0c57068d539ca4">map_fail_callback</a>)(size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when a call to map memory pages fails (out of memory). <a href="#a35106c441d799201ae0c57068d539ca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf8dfc992b8b4a4e6cd72e213bf1035">page_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of memory pages. <a href="#adcf8dfc992b8b4a4e6cd72e213bf1035">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab730f9de6da78affe64497f859d6d345">span_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of a span of memory blocks. <a href="#ab730f9de6da78affe64497f859d6d345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cfc60f2a133ca255a762778cc024c6">span_map_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of spans to map at each request to map new virtual memory blocks. <a href="#a84cfc60f2a133ca255a762778cc024c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfb1a2f571e8ebe68185b387f04260b">enable_huge_pages</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable use of large/huge pages. <a href="#a9cfb1a2f571e8ebe68185b387f04260b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1c79b90f2b7f66d98690b1234ab8d8">page_name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Respectively allocated pages and huge allocated pages names for systems. <a href="#a8b1c79b90f2b7f66d98690b1234ab8d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf26ab237ec708c05953e92ae93578f">huge_page_name</a></td>
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


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### enable\_huge\_pages {#a9cfb1a2f571e8ebe68185b387f04260b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rpmalloc_config_t::enable_huge_pages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable use of large/huge pages.</p>


<p>If this flag is set to non-zero and page size is</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### error\_callback {#a4bc0e407dff5707e6e199ba21f7afbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void(* rpmalloc_config_t::error_callback) (const char *message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called when an assert fails, if asserts are enabled.</p>


<p>Will use the standard <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert()</a></p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### huge\_page\_name {#aaaf26ab237ec708c05953e92ae93578f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* rpmalloc_config_t::huge_page_name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### map\_fail\_callback {#a35106c441d799201ae0c57068d539ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int(* rpmalloc_config_t::map_fail_callback) (size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called when a call to map memory pages fails (out of memory).</p>


<p>If this callback is</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### memory\_map {#adbcdb0bb951b75755ad9f6fa95c5fb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void *(* rpmalloc_config_t::memory_map) (size_t size, size_t *offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map memory pages for the given number of bytes.</p>


<p>The returned address MUST be</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### memory\_unmap {#a10fb22a2f8775aafd70b1c79f6b80630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void(* rpmalloc_config_t::memory_unmap) (void *address, size_t size, size_t offset, size_t release)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unmap the memory pages starting at address and spanning the given number of bytes.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### page\_name {#a8b1c79b90f2b7f66d98690b1234ab8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* rpmalloc_config_t::page_name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Respectively allocated pages and huge allocated pages names for systems.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### page\_size {#adcf8dfc992b8b4a4e6cd72e213bf1035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_config_t::page_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of memory pages.</p>


<p>The page size MUST be a power of two. All memory mapping</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### span\_map\_count {#a84cfc60f2a133ca255a762778cc024c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_config_t::span_map_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of spans to map at each request to map new virtual memory blocks.</p>


<p>This can</p>


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### span\_size {#ab730f9de6da78affe64497f859d6d345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_config_t::span_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of a span of memory blocks.</p>


<p>MUST be a power of two, and in [4096,262144]</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
