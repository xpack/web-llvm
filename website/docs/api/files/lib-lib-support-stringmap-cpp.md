---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/stringmap-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `StringMap.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/reverseiteration-h">llvm/Support/ReverseIteration.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">llvm/Support/xxhash.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74946d2eef6ce1d30a0578dc8fad44c">getMinBucketToReserveForEntries</a> (unsigned NumEntries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of buckets to allocate to ensure that the <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> can accommodate <span class="doxyComputerOutput">NumEntries</span> without need to grow(). <a href="#ab74946d2eef6ce1d30a0578dc8fad44c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringmapentrybase">StringMapEntryBase</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3c891b0c780ce527a4ed687732dff1">createTable</a> (unsigned NewNumBuckets)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956b630921eba82b7480c112b668c4bd">getHashTable</a> (StringMapEntryBase **TheTable, unsigned NumBuckets)</td>
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


<div class="doxySectionDef">

## Functions

### createTable() {#a6c3c891b0c780ce527a4ed687732dff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntryBase ** createTable (unsigned NewNumBuckets)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringmap-cpp">StringMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a53b2f25342c49b78f06fbec9cf7fe644">llvm::safe_calloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a8cd8ff7eae809d0666a26bff53ef14d8">llvm::StringMapImpl::init</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a498d235dfa951d6728354cc777896219">llvm::StringMapImpl::RehashTable</a>.</p>

</div>
</div>

### getHashTable() {#a956b630921eba82b7480c112b668c4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned * getHashTable (<a href="/web-llvm/docs/api/classes/llvm/stringmapentrybase">StringMapEntryBase</a> ** TheTable, unsigned NumBuckets)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringmap-cpp">StringMap.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a4bed18f645cf76fb884f4ee5e9aacea0">llvm::StringMapImpl::FindKey</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a1681c3e5a8a4f67991745ffca1cb72fc">llvm::StringMapImpl::LookupBucketFor</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a498d235dfa951d6728354cc777896219">llvm::StringMapImpl::RehashTable</a>.</p>

</div>
</div>

### getMinBucketToReserveForEntries() {#ab74946d2eef6ce1d30a0578dc8fad44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getMinBucketToReserveForEntries (unsigned NumEntries)</td>
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

<p>Returns the number of buckets to allocate to ensure that the <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> can accommodate <span class="doxyComputerOutput">NumEntries</span> without need to grow().</p>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringmap-cpp">StringMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afb65eef479f0473d0fe1666b80155237">llvm::NextPowerOf2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a0112d5fb05c0d23d0b3b829b91d7c433">llvm::StringMapImpl::StringMapImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
