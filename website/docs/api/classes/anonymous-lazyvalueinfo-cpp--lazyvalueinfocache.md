---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LazyValueInfoCache` Class Reference

<p>This is the cache kept by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo">LazyValueInfo</a> which maintains information about queries across the clients' queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LazyValueInfo.cpp}::LazyValueInfoCache { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636aedde42a1a5df6db71597b2ec847c">insertResult</a> (Value *Val, BasicBlock *BB, const ValueLatticeElement &amp;Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3438d4775f46be4ad02e9b72121afd90">getCachedValueInfo</a> (Value *V, BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4859acf0c0df471e18cca74f49e5599">isNonNullAtEndOfBlock</a> (Value *V, BasicBlock *BB, function_ref&lt; NonNullPointerSet(BasicBlock *)&gt; InitFn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2e1bfaaa9d5b40126f43f6db4027aa">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Empty the cache. <a href="#aef2e1bfaaa9d5b40126f43f6db4027aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc1b79db4c7667587021f8030ec4e2f">eraseValue</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the cache that a given value has been deleted. <a href="#abdc1b79db4c7667587021f8030ec4e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90116bea55d30b6fd5bb74b70a0b0a0a">eraseBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is part of the update interface to inform the cache that a block has been deleted. <a href="#a90116bea55d30b6fd5bb74b70a0b0a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b02f7eb2d588954f8bf193a6bab43e1">threadEdgeImpl</a> (BasicBlock *OldSucc, BasicBlock *NewSucc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the cache to remove any influence an overdefined value in OldSucc might have (unless also overdefined in NewSucc). <a href="#a4b02f7eb2d588954f8bf193a6bab43e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockCacheEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8cd3c18c33301cd8effb62b39fe8a2">getBlockEntry</a> (BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockCacheEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911b93bba088c0a5af9021f05b85b12b">getOrCreateBlockEntry</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6104ac2c555424c0b7b615aeedaed62">addValueHandle</a> (Value *Val)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/poisoningvh">PoisoningVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;, std::unique_ptr&lt; BlockCacheEntry &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b236a4836f677e5e8276d7d27627d47">BlockCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached information per basic block. <a href="#a3b236a4836f677e5e8276d7d27627d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle">LVIValueHandle</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023114d006413c3b0d1dbb6c1fccf664">ValueHandles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of value handles used to erase values from the cache on deletion. <a href="#a023114d006413c3b0d1dbb6c1fccf664">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the cache kept by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo">LazyValueInfo</a> which maintains information about queries across the clients' queries.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### clear() {#aef2e1bfaaa9d5b40126f43f6db4027aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::clear ()</td>
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

<p>clear - Empty the cache.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### eraseBlock() {#a90116bea55d30b6fd5bb74b70a0b0a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyValueInfoCache::eraseBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is part of the update interface to inform the cache that a block has been deleted.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### eraseValue() {#abdc1b79db4c7667587021f8030ec4e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyValueInfoCache::eraseValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inform the cache that a given value has been deleted.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### getCachedValueInfo() {#a3438d4775f46be4ad02e9b72121afd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ValueLatticeElement &gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::getCachedValueInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afa0befbad06a536ee25c232941a09856">llvm::ValueLatticeElement::getOverdefined</a>.</p>

</div>
</div>

### insertResult() {#a636aedde42a1a5df6db71597b2ec847c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::insertResult (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Result)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### isNonNullAtEndOfBlock() {#af4859acf0c0df471e18cca74f49e5599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::isNonNullAtEndOfBlock (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-lazyvalueinfo-cpp-/#a02e7f45327831f3330e6b7cba99a0bfb">NonNullPointerSet</a>(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt; InitFn)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### threadEdgeImpl() {#a4b02f7eb2d588954f8bf193a6bab43e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyValueInfoCache::threadEdgeImpl (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OldSucc, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewSucc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the cache to remove any influence an overdefined value in OldSucc might have (unless also overdefined in NewSucc).</p>


<p>This just flushes elements from the cache and does not add any.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addValueHandle() {#af6104ac2c555424c0b7b615aeedaed62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::addValueHandle (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### getBlockEntry() {#ace8cd3c18c33301cd8effb62b39fe8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockCacheEntry * anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::getBlockEntry (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### getOrCreateBlockEntry() {#a911b93bba088c0a5af9021f05b85b12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockCacheEntry * anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::getOrCreateBlockEntry (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockCache {#a3b236a4836f677e5e8276d7d27627d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PoisoningVH&lt;BasicBlock&gt;, std::unique_ptr&lt;BlockCacheEntry&gt; &gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::BlockCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached information per basic block.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### ValueHandles {#a023114d006413c3b0d1dbb6c1fccf664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;LVIValueHandle, DenseMapInfo&lt;Value *&gt; &gt; anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::ValueHandles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of value handles used to erase values from the cache on deletion.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
