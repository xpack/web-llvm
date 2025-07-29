---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/prediteratorcache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PredIteratorCache` Class

<p><a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a> - This class is an extremely trivial cache for predecessor iterator queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PredIteratorCache { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">llvm/IR/PredIteratorCache.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c3960dda906754affa59a2fb7c632f">size</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4997ba4fd2495e1737dcf98457f8419">get</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9591b7adcdf007126703405b17307ce4">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Remove all information. <a href="#a9591b7adcdf007126703405b17307ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e90e66466c7ee429525c93e38fad61d">BlockToPredsMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached list of predecessors, allocated in Memory. <a href="#a0e90e66466c7ee429525c93e38fad61d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9899c329f1143b8aa3835190e4bb6201">Memory</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memory - This is the space that holds cached preds. <a href="#a9899c329f1143b8aa3835190e4bb6201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a> - This class is an extremely trivial cache for predecessor iterator queries.</p>


<p>This is useful for code that repeatedly wants the predecessor list for the same blocks.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### clear() {#a9591b7adcdf007126703405b17307ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PredIteratorCache::clear ()</td>
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

<p>clear - Remove all information.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>

</div>
</div>

### get() {#aa4997ba4fd2495e1737dcf98457f8419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BasicBlock * &gt; llvm::PredIteratorCache::get (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#ab90f4a46f63bfddff132d20866be2da2">ComputeLiveInBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a> and <a href="#a60c3960dda906754affa59a2fb7c632f">size</a>.</p>

</div>
</div>

### size() {#a60c3960dda906754affa59a2fb7c632f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::PredIteratorCache::size (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>


<p>References <a href="#aa4997ba4fd2495e1737dcf98457f8419">get</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockToPredsMap {#a0e90e66466c7ee429525c93e38fad61d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, ArrayRef&lt;BasicBlock *&gt; &gt; llvm::PredIteratorCache::BlockToPredsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached list of predecessors, allocated in Memory.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>

</div>
</div>

### Memory {#a9899c329f1143b8aa3835190e4bb6201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::PredIteratorCache::Memory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memory - This is the space that holds cached preds.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/prediteratorcache-h">PredIteratorCache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
