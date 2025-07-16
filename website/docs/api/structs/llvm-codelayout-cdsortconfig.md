---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codelayout/cdsortconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CDSortConfig` Struct Reference

<p>Algorithm-specific params for Cache-Directed Sort. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::codelayout::CDSortConfig { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">llvm/Transforms/Utils/CodeLayout.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5722362bbe8b820f7171a89b500180e">CacheEntries</a> = 16</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of the cache. <a href="#ad5722362bbe8b820f7171a89b500180e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3e2b25b382491b92cc2ec6d066dae9">CacheSize</a> = 2048</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of a line in the cache. <a href="#a9b3e2b25b382491b92cc2ec6d066dae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca32aeb071c565b99935586655ac847">MaxChainSize</a> = 128</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size of a chain to create. <a href="#a7ca32aeb071c565b99935586655ac847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8843f638794cf74c8044107ae618200">DistancePower</a> = 0.25</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The power exponent for the distance-based locality. <a href="#ab8843f638794cf74c8044107ae618200">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9844a48ea378fd1887b0a4146a7af3">FrequencyScale</a> = 0.25</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scale factor for the frequency-based locality. <a href="#acf9844a48ea378fd1887b0a4146a7af3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Algorithm-specific params for Cache-Directed Sort.</p>


<p>The values are tuned for the best performance of large-scale front-end bound binaries.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CacheEntries {#ad5722362bbe8b820f7171a89b500180e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::codelayout::CDSortConfig::CacheEntries = 16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of the cache.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a40b559a61a165123bb62e26c941a223b">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

### CacheSize {#a9b3e2b25b382491b92cc2ec6d066dae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::codelayout::CDSortConfig::CacheSize = 2048</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of a line in the cache.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a40b559a61a165123bb62e26c941a223b">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

### DistancePower {#ab8843f638794cf74c8044107ae618200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::codelayout::CDSortConfig::DistancePower = 0.25</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The power exponent for the distance-based locality.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a40b559a61a165123bb62e26c941a223b">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

### FrequencyScale {#acf9844a48ea378fd1887b0a4146a7af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::codelayout::CDSortConfig::FrequencyScale = 0.25</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The scale factor for the frequency-based locality.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a40b559a61a165123bb62e26c941a223b">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

### MaxChainSize {#a7ca32aeb071c565b99935586655ac847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::codelayout::CDSortConfig::MaxChainSize = 128</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size of a chain to create.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a40b559a61a165123bb62e26c941a223b">llvm::codelayout::computeCacheDirectedLayout</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
