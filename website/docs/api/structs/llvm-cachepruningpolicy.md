---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/cachepruningpolicy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CachePruningPolicy` Struct Reference

<p>Policy for the <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">pruneCache()</a> function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CachePruningPolicy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">llvm/Support/CachePruning.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::chrono::seconds &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f65d4efd088dd6f035a970ef350628">Interval</a> = std::chrono::seconds(1200)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pruning interval. <a href="#a26f65d4efd088dd6f035a970ef350628">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::chrono::seconds</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4e128e83c615ca4ed425980b41e64f">Expiration</a> = std::chrono::hours(7 * 24)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The expiration for a file. <a href="#a4e4e128e83c615ca4ed425980b41e64f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13a6c169c6b44529d9f6bae76c8b4ed">MaxSizePercentageOfAvailableSpace</a> = 75</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size for the cache directory, in terms of percentage of the available space on the disk. <a href="#ac13a6c169c6b44529d9f6bae76c8b4ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c514fa2ef23ee2f092cedf2691886dd">MaxSizeBytes</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size for the cache directory in bytes. <a href="#a8c514fa2ef23ee2f092cedf2691886dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b73cd4206ae3e5edc07c24afb2057ac">MaxSizeFiles</a> = 1000000</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of files in the cache directory. <a href="#a0b73cd4206ae3e5edc07c24afb2057ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Policy for the <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">pruneCache()</a> function.</p>


<p>A default constructed <a href="/web-llvm/docs/api/structs/llvm/cachepruningpolicy">CachePruningPolicy</a> provides a reasonable default policy.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Expiration {#a4e4e128e83c615ca4ed425980b41e64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::chrono::seconds llvm::CachePruningPolicy::Expiration = std::chrono::hours(7 * 24)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The expiration for a file.</p>


<p>When a file hasn't been accessed for Expiration seconds, it is removed from the cache. A value of 0 disables the expiration-based pruning.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

### Interval {#a26f65d4efd088dd6f035a970ef350628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::chrono::seconds&gt; llvm::CachePruningPolicy::Interval = std::chrono::seconds(1200)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pruning interval.</p>


<p>This is intended to be used to avoid scanning the directory too often. It does not impact the decision of which file to prune. A value of 0 forces the scan to occur. A value of std::nullopt disables pruning.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

### MaxSizeBytes {#a8c514fa2ef23ee2f092cedf2691886dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CachePruningPolicy::MaxSizeBytes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size for the cache directory in bytes.</p>


<p>A value over the amount of available space on the disk will be reduced to the amount of available space. A value of 0 disables the absolute size-based pruning.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

### MaxSizeFiles {#a0b73cd4206ae3e5edc07c24afb2057ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CachePruningPolicy::MaxSizeFiles = 1000000</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of files in the cache directory.</p>


<p>A value of 0 disables the number of files based pruning.</p>


<p>This defaults to 1000000 because with that many files there are diminishing returns on the effectiveness of the cache. Some systems have a limit on total number of files, and some also limit the number of files per directory, such as Linux ext4, with the default setting (block size is 4096 and large_dir disabled), there is a per-directory entry limit of 508*510*floor(4096/(40+8))~=20M for average filename length of 40.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

### MaxSizePercentageOfAvailableSpace {#ac13a6c169c6b44529d9f6bae76c8b4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CachePruningPolicy::MaxSizePercentageOfAvailableSpace = 75</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size for the cache directory, in terms of percentage of the available space on the disk.</p>


<p>Set to 100 to indicate no limit, 50 to indicate that the cache size will not be left over half the available disk space. A value over 100 will be reduced to 100. A value of 0 disables the percentage size-based pruning.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">CachePruning.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
