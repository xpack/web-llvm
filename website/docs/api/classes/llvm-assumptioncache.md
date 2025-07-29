---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/assumptioncache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AssumptionCache` Class

<p>A cache of @llvm.assume calls within a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AssumptionCache { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb96f5985968dbd97e67c57164122ba">AffectedValuesMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; AffectedValueCallbackVH, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem">ResultElem</a>, 1 &gt;, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">AffectedValueCallbackVH::DMI</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of values about which an assumption might be providing information to the relevant set of assumptions. <a href="#a6cb96f5985968dbd97e67c57164122ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a05a03a071a8a55948ba0db3b5bf594ba">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem/#a0085dfe0ee247e594c95dbb6f768f235">ResultElem::Index</a> indicating that the argument to the call of the llvm.assume. <a href="#a05a03a071a8a55948ba0db3b5bf594ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a2d92539d4596ba55f6d953ec7c188">AssumptionCache</a> (Function &amp;F, TargetTransformInfo *TTI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> from a function by scanning all of its instructions. <a href="#ab6a2d92539d4596ba55f6d953ec7c188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4867ed1b6dfd356558bd881567602049">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This cache is designed to be self-updating and so it should never be invalidated. <a href="#a4867ed1b6dfd356558bd881567602049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23187618f079555e127ba0e7b4581530">registerAssumption</a> (AssumeInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an @llvm.assume intrinsic to this function's cache. <a href="#a23187618f079555e127ba0e7b4581530">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8137607e298da393c72cfcffb2edc352">unregisterAssumption</a> (AssumeInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an @llvm.assume intrinsic from this function's cache if it has been added to the cache earlier. <a href="#a8137607e298da393c72cfcffb2edc352">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa8956db34e5076680cfd8398d090dc">updateAffectedValues</a> (AssumeInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the cache of values being affected by this assumption (i.e. <a href="#a5fa8956db34e5076680cfd8398d090dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5aab0e9687dd8250c8fa49d4de1b1b">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the cache of @llvm.assume intrinsics for a function. <a href="#a2f5aab0e9687dd8250c8fa49d4de1b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem">ResultElem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc4a01d7ae02545172aaee110d4a01c">assumptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the list of assumption handles currently tracked for this function. <a href="#a6bc4a01d7ae02545172aaee110d4a01c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem">ResultElem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab711f68db26cb29c8332ac93c0bebed1">assumptionsFor</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the list of assumptions which affect this value. <a href="#ab711f68db26cb29c8332ac93c0bebed1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem">ResultElem</a>, 1 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a4886ab0d28861fdc78be8f5967e7b">getOrInsertAffectedValues</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the vector of assumptions which affect a value from the cache. <a href="#a31a4886ab0d28861fdc78be8f5967e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be61e61997de05181e113f6755fbfa3">transferAffectedValuesInCache</a> (Value *OV, Value *NV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move affected values in the cache for OV to be affected values for NV. <a href="#a8be61e61997de05181e113f6755fbfa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e13b95cccc7a9ca5d4914d3765ef81e">scanFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the function for assumptions and add them to the cache. <a href="#a4e13b95cccc7a9ca5d4914d3765ef81e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952edfcd1f444ce5c89978299ae9cd57">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function for which this cache is handling assumptions. <a href="#a952edfcd1f444ce5c89978299ae9cd57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d80b90e6981cb5dd7fedc7bec6aed02">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem">ResultElem</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a34836ef83d3d507bd13cc58c1ef60">AssumeHandles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of weak value handles to calls of the @llvm.assume intrinsic. <a href="#af8a34836ef83d3d507bd13cc58c1ef60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c99217904c801604f1a430a11e7ccf">AffectedValueCallbackVH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AffectedValuesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2029524118f64d0aa47fb0f32676772">AffectedValues</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a54db9071afa97154a47e853fed8a0">Scanned</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag tracking whether we have scanned the function yet. <a href="#a39a54db9071afa97154a47e853fed8a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A cache of @llvm.assume calls within a function.</p>


<p>This cache provides fast lookup of assumptions within a function by caching them and amortizing the cost of scanning for them across all queries. Passes that create new assumptions are required to call <a href="#a23187618f079555e127ba0e7b4581530">registerAssumption()</a> to register any new @llvm.assume calls that they create. Deletions of @llvm.assume calls do not require special handling.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AffectedValuesMap {#a6cb96f5985968dbd97e67c57164122ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AssumptionCache::AffectedValuesMap = 
      DenseMap&lt;AffectedValueCallbackVH, SmallVector&lt;ResultElem, 1&gt;,
               AffectedValueCallbackVH::DMI&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of values about which an assumption might be providing information to the relevant set of assumptions.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a05a03a071a8a55948ba0db3b5bf594ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem/#a0085dfe0ee247e594c95dbb6f768f235">ResultElem::Index</a> indicating that the argument to the call of the llvm.assume.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExprResultIdx<a id="a05a03a071a8a55948ba0db3b5bf594baabe329e327a2448aff6bd087678df1c26"></a></td>
<td class="doxyEnumItemDescription"> (= std::numeric_limits&lt;unsigned&gt;::max())</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AssumptionCache() {#ab6a2d92539d4596ba55f6d953ec7c188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AssumptionCache::AssumptionCache (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI=nullptr)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> from a function by scanning all of its instructions.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/assumptionanalysis/#aeb8f2cc893c02d3d5a926b69bab89185">llvm::AssumptionAnalysis::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assumptions() {#a6bc4a01d7ae02545172aaee110d4a01c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; ResultElem &gt; llvm::AssumptionCache::assumptions ()</td>
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

<p>Access the list of assumption handles currently tracked for this function.</p>


<p>Note that these produce weak handles that may be null. The caller must handle that case. FIXME: We should replace this with <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator&lt;filter_iterator&lt;...&gt;&gt;</a> when we can write that to filter out the null values. Then caller code will become simpler.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a12fe141dcc45d0acb90cd466649ae556">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptionprinterpass/#a140e7194c82dc0eda75b3602736a0b83">llvm::AssumptionPrinterPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a8438c57f709573b02939ac340a2df1ec">llvm::AlignmentFromAssumptionsPass::runImpl</a>.</p>

</div>
</div>

### assumptionsFor() {#ab711f68db26cb29c8332ac93c0bebed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; ResultElem &gt; llvm::AssumptionCache::assumptionsFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Access the list of assumptions which affect this value.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ade489c0f3b2b272cfcf0bb8f011399">llvm::getKnowledgeForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>.</p>

</div>
</div>

### clear() {#a2f5aab0e9687dd8250c8fa49d4de1b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AssumptionCache::clear ()</td>
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

<p>Clear the cache of @llvm.assume intrinsics for a function.</p>


<p>It will be re-scanned the next time it is requested.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### invalidate() {#a4867ed1b6dfd356558bd881567602049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AssumptionCache::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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

<p>This cache is designed to be self-updating and so it should never be invalidated.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### registerAssumption() {#a23187618f079555e127ba0e7b4581530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssumptionCache::registerAssumption (<a href="/web-llvm/docs/api/classes/llvm/assumeinst">AssumeInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an @llvm.assume intrinsic to this function's cache.</p>


<p>The call passed in must be an instruction within this function and must not already be in the cache.</p>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a05a03a071a8a55948ba0db3b5bf594baabe329e327a2448aff6bd087678df1c26">ExprResultIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="#a5fa8956db34e5076680cfd8398d090dc">updateAffectedValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45a945c85468ec7d17b48b0d4f612b7e">combineInstructionsOverFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5df9c7cb06c08a066a30482d77cc1d9">llvm::salvageKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### unregisterAssumption() {#a8137607e298da393c72cfcffb2edc352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssumptionCache::unregisterAssumption (<a href="/web-llvm/docs/api/classes/llvm/assumeinst">AssumeInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove an @llvm.assume intrinsic from this function's cache if it has been added to the cache earlier.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem/#a14c11eb4c6cb72fc9922b742c71fe3b3">llvm::AssumptionCache::ResultElem::Assume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>.</p>

</div>
</div>

### updateAffectedValues() {#a5fa8956db34e5076680cfd8398d090dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssumptionCache::updateAffectedValues (<a href="/web-llvm/docs/api/classes/llvm/assumeinst">AssumeInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the cache of values being affected by this assumption (i.e.</p>


<p>the values about which this assumption provides information).</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem/#a14c11eb4c6cb72fc9922b742c71fe3b3">llvm::AssumptionCache::ResultElem::Assume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/assumptioncache/resultelem/#a0085dfe0ee247e594c95dbb6f768f235">llvm::AssumptionCache::ResultElem::Index</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>


<p>Referenced by <a href="#a23187618f079555e127ba0e7b4581530">registerAssumption</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOrInsertAffectedValues() {#a31a4886ab0d28861fdc78be8f5967e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; AssumptionCache::ResultElem, 1 &gt; &amp; AssumptionCache::getOrInsertAffectedValues (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the vector of assumptions which affect a value from the cache.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>

</div>
</div>

### scanFunction() {#a4e13b95cccc7a9ca5d4914d3765ef81e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssumptionCache::scanFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the function for assumptions and add them to the cache.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>

</div>
</div>

### transferAffectedValuesInCache() {#a8be61e61997de05181e113f6755fbfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssumptionCache::transferAffectedValuesInCache (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OV, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move affected values in the cache for OV to be affected values for NV.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AffectedValueCallbackVH {#a59c99217904c801604f1a430a11e7ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::AssumptionCache::AffectedValueCallbackVH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### AffectedValues {#af2029524118f64d0aa47fb0f32676772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AffectedValuesMap llvm::AssumptionCache::AffectedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### AssumeHandles {#af8a34836ef83d3d507bd13cc58c1ef60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ResultElem, 4&gt; llvm::AssumptionCache::AssumeHandles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of weak value handles to calls of the @llvm.assume intrinsic.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### F {#a952edfcd1f444ce5c89978299ae9cd57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::AssumptionCache::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function for which this cache is handling assumptions.</p>


<p>We track this to lazily populate our assumptions.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### Scanned {#a39a54db9071afa97154a47e853fed8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AssumptionCache::Scanned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag tracking whether we have scanned the function yet.</p>


<p>We want to be as lazy about this as possible, and so we scan the function at the last moment.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

### TTI {#a3d80b90e6981cb5dd7fedc7bec6aed02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* llvm::AssumptionCache::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp">AssumptionCache.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
