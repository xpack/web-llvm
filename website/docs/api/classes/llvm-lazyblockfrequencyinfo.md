---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lazyblockfrequencyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LazyBlockFrequencyInfo` Class Template Reference

<p>Wraps a BFI to allow lazy computation of the block frequencies. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;
class llvm::LazyBlockFrequencyInfo&lt;FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">llvm/Analysis/LazyBlockFrequencyInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4e8310c2d32e700cfa8ca1dbf34787fd">LazyBlockFrequencyInfo</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcf9d6e0d69c79016212934c24124928">setAnalysis</a> (const FunctionT *F, BranchProbabilityInfoPassT *BPIPass, const LoopInfoT *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the per-function input. <a href="#afcf9d6e0d69c79016212934c24124928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockFrequencyInfoT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabf29eed24c2427555b6be5f140066fc">getCalculated</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the BFI with the block frequencies computed. <a href="#aabf29eed24c2427555b6be5f140066fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockFrequencyInfoT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a0418450d455c24d2bdfa3296d3cef8">getCalculated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa50835629c918e8c5899a826477ef3b6">releaseMemory</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockFrequencyInfoT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe384b2f305cdd6783d2586a1edfd01e">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a8a8f9c31bd5fd9de1de07a2ffcaa69">Calculated</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e36ee2dce4a4994e26d1f039f46c61f">F</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BranchProbabilityInfoPassT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a204ff732ceede2464a2c6b03f4443419">BPIPass</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopInfoT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a500e248f1409ffd81b2c0c0aa17e5a2b">LI</a> = nullptr</td>
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

## Description {#details}

<p>Wraps a BFI to allow lazy computation of the block frequencies.</p>


<p>A pass that only conditionally uses BFI can uncondtionally require the analysis without paying for the overhead if BFI doesn't end up being used.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LazyBlockFrequencyInfo() {#a4e8310c2d32e700cfa8ca1dbf34787fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::LazyBlockFrequencyInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<p>Referenced by <a href="#a8a0418450d455c24d2bdfa3296d3cef8">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::getCalculated</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCalculated() {#aabf29eed24c2427555b6be5f140066fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfoT &amp; llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::getCalculated ()</td>
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

<p>Retrieve the BFI with the block frequencies computed.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/bpipasstrait/#a349652dd7389f87410d06137c76bb06c">llvm::BPIPassTrait&lt; PassT &gt;::getBPI</a>.</p>


<p>Referenced by <a href="#a8a0418450d455c24d2bdfa3296d3cef8">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::getCalculated</a>.</p>

</div>
</div>

### getCalculated() {#a8a0418450d455c24d2bdfa3296d3cef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockFrequencyInfoT &amp; llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::getCalculated ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<p>References <a href="#aabf29eed24c2427555b6be5f140066fc">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::getCalculated</a> and <a href="#a4e8310c2d32e700cfa8ca1dbf34787fd">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::LazyBlockFrequencyInfo</a>.</p>

</div>
</div>

### releaseMemory() {#aa50835629c918e8c5899a826477ef3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::releaseMemory ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<p>Reference <a href="#afcf9d6e0d69c79016212934c24124928">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::setAnalysis</a>.</p>

</div>
</div>

### setAnalysis() {#afcf9d6e0d69c79016212934c24124928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::setAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionT * F, BranchProbabilityInfoPassT * BPIPass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopInfoT * LI)</td>
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

<p>Set up the per-function input.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>


<p>Referenced by <a href="#aa50835629c918e8c5899a826477ef3b6">llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::releaseMemory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BFI {#abe384b2f305cdd6783d2586a1edfd01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfoT llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>

</div>
</div>

### BPIPass {#a204ff732ceede2464a2c6b03f4443419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfoPassT* llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::BPIPass = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>

</div>
</div>

### Calculated {#a7a8a8f9c31bd5fd9de1de07a2ffcaa69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::Calculated = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>

</div>
</div>

### F {#a5e36ee2dce4a4994e26d1f039f46c61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionT* llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::F = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>

</div>
</div>

### LI {#a500e248f1409ffd81b2c0c0aa17e5a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT, typename BranchProbabilityInfoPassT, typename LoopInfoT, typename BlockFrequencyInfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfoT* llvm::LazyBlockFrequencyInfo&lt; FunctionT, BranchProbabilityInfoPassT, LoopInfoT, BlockFrequencyInfoT &gt;::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">LazyBlockFrequencyInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
