---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/rpmalloc-global-statistics-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `rpmalloc_global_statistics_t` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct rpmalloc_global_statistics_t { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">Support/rpmalloc/rpmalloc.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d895a6016dd1c5937f2a74370f2727">mapped</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current amount of virtual memory mapped, all of which might not have been committed (only if ENABLE_STATISTICS=1) <a href="#ab0d895a6016dd1c5937f2a74370f2727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5723376daeb707aa20547190ced2865">mapped_peak</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Peak amount of virtual memory mapped, all of which might not have been committed (only if ENABLE_STATISTICS=1) <a href="#ad5723376daeb707aa20547190ced2865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b10faa79aac5df497ba5eccdd554ae">cached</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current amount of memory in global caches for small and medium sizes (&lt;32KiB) <a href="#a70b10faa79aac5df497ba5eccdd554ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db28c5567049de1e58833c061841f7e">huge_alloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current amount of memory allocated in huge allocations, i.e larger than LARGE_SIZE_LIMIT which is 2MiB by default (only if ENABLE_STATISTICS=1) <a href="#a5db28c5567049de1e58833c061841f7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308868b1a8740da06b79c1bdabae1997">huge_alloc_peak</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Peak amount of memory allocated in huge allocations, i.e larger than LARGE_SIZE_LIMIT which is 2MiB by default (only if ENABLE_STATISTICS=1) <a href="#a308868b1a8740da06b79c1bdabae1997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1916b4138cfc1e46ff0787ff9206375">mapped_total</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total amount of memory mapped since initialization (only if ENABLE_STATISTICS=1) <a href="#af1916b4138cfc1e46ff0787ff9206375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa896cafa124a63254f56621fe2c5241f">unmapped_total</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total amount of memory unmapped since initialization (only if ENABLE_STATISTICS=1) <a href="#aa896cafa124a63254f56621fe2c5241f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### cached {#a70b10faa79aac5df497ba5eccdd554ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::cached</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current amount of memory in global caches for small and medium sizes (&lt;32KiB)</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### huge\_alloc {#a5db28c5567049de1e58833c061841f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::huge_alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current amount of memory allocated in huge allocations, i.e larger than LARGE_SIZE_LIMIT which is 2MiB by default (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### huge\_alloc\_peak {#a308868b1a8740da06b79c1bdabae1997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::huge_alloc_peak</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Peak amount of memory allocated in huge allocations, i.e larger than LARGE_SIZE_LIMIT which is 2MiB by default (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### mapped {#ab0d895a6016dd1c5937f2a74370f2727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::mapped</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current amount of virtual memory mapped, all of which might not have been committed (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### mapped\_peak {#ad5723376daeb707aa20547190ced2865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::mapped_peak</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Peak amount of virtual memory mapped, all of which might not have been committed (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### mapped\_total {#af1916b4138cfc1e46ff0787ff9206375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::mapped_total</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total amount of memory mapped since initialization (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

</div>
</div>

### unmapped\_total {#aa896cafa124a63254f56621fe2c5241f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t rpmalloc_global_statistics_t::unmapped_total</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total amount of memory unmapped since initialization (only if ENABLE_STATISTICS=1)</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h">rpmalloc.h</a>.</p>

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
