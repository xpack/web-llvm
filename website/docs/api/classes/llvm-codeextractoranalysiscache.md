---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeextractoranalysiscache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeExtractorAnalysisCache` Class

<p>A cache for the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> analysis. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CodeExtractorAnalysisCache { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">llvm/Transforms/Utils/CodeExtractor.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c11ef80226655b08c6203641896fa50">CodeExtractorAnalysisCache</a> (Function &amp;F)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35fd9ad0c2debb7b171f4c61ce7bdac6">getAllocas</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the allocas in the function at the time the analysis was created. <a href="#a35fd9ad0c2debb7b171f4c61ce7bdac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ee5fce396f816a21443799205fbedd">doesBlockContainClobberOfAddr</a> (BasicBlock &amp;BB, AllocaInst *Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">BB</span> contains an instruction thought to load from, store to, or otherwise clobber the alloca <span class="doxyComputerOutput">Addr</span>. <a href="#af0ee5fce396f816a21443799205fbedd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772f553ea4059bb635b67ecf0ba35ddc">findSideEffectInfoForBlock</a> (BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4c528fe43bd8b8de5c150dcca28e73">Allocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The allocas in the function. <a href="#a1c4c528fe43bd8b8de5c150dcca28e73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6f048ba42645df447ee29834243a5c">BaseMemAddrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base memory addresses of load/store instructions, grouped by block. <a href="#a7d6f048ba42645df447ee29834243a5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94996018a63c3d33436dd371a7f5bb1">SideEffectingBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks which contain instructions which may have unknown side-effects on memory. <a href="#ab94996018a63c3d33436dd371a7f5bb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A cache for the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> analysis.</p>


<p>The operation <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a8561c48aa0b397c37f9e071dad7df392">CodeExtractor::extractCodeRegion</a> is guaranteed not to invalidate this object. This object should conservatively be considered invalid if any other mutating operations on the IR occur.</p>


<p>Constructing this object is O(n) in the size of the function.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CodeExtractorAnalysisCache() {#a6c11ef80226655b08c6203641896fa50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeExtractorAnalysisCache::CodeExtractorAnalysisCache (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doesBlockContainClobberOfAddr() {#af0ee5fce396f816a21443799205fbedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeExtractorAnalysisCache::doesBlockContainClobberOfAddr (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <span class="doxyComputerOutput">BB</span> contains an instruction thought to load from, store to, or otherwise clobber the alloca <span class="doxyComputerOutput">Addr</span>.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ae9ce92095ff18cb2c607d5a3591703ca">llvm::CodeExtractor::isLegalToShrinkwrapLifetimeMarkers</a>.</p>

</div>
</div>

### getAllocas() {#a35fd9ad0c2debb7b171f4c61ce7bdac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; AllocaInst * &gt; llvm::CodeExtractorAnalysisCache::getAllocas ()</td>
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

<p>Get the allocas in the function at the time the analysis was created.</p>


<p>Note that some of these allocas may no longer be present in the function, due to <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a8561c48aa0b397c37f9e071dad7df392">CodeExtractor::extractCodeRegion</a>.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findSideEffectInfoForBlock() {#a772f553ea4059bb635b67ecf0ba35ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractorAnalysisCache::findSideEffectInfoForBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocas {#a1c4c528fe43bd8b8de5c150dcca28e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInst *, 16&gt; llvm::CodeExtractorAnalysisCache::Allocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The allocas in the function.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### BaseMemAddrs {#a7d6f048ba42645df447ee29834243a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, DenseSet&lt;Value *&gt; &gt; llvm::CodeExtractorAnalysisCache::BaseMemAddrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Base memory addresses of load/store instructions, grouped by block.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### SideEffectingBlocks {#ab94996018a63c3d33436dd371a7f5bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;BasicBlock *&gt; llvm::CodeExtractorAnalysisCache::SideEffectingBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks which contain instructions which may have unknown side-effects on memory.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
