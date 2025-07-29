---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-coveragemapping-cpp-/segmentbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SegmentBuilder` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CoverageMapping.cpp}::SegmentBuilder { ... }
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465fe9d0416eff2d05c6e854334c3f32">SegmentBuilder</a> (std::vector&lt; CoverageSegment &gt; &amp;Segments)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2091cacde43c2884f003c63f0741a6">startSegment</a> (const CountedRegion &amp;Region, LineColPair StartLoc, bool IsRegionEntry, bool EmitSkippedRegion=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a segment with the count from <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> starting at <span class="doxyComputerOutput">StartLoc</span>. <a href="#afa2091cacde43c2884f003c63f0741a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8433456c6ef84e4cc037f6f108d276">completeRegionsUntil</a> (std::optional&lt; LineColPair &gt; Loc, unsigned FirstCompletedRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit segments for active regions which end before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#a5c8433456c6ef84e4cc037f6f108d276">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a331360b1539ddfa158145ef019e1b5e9">buildSegmentsImpl</a> (ArrayRef&lt; CountedRegion &gt; Regions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment">CoverageSegment</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a4e9609ccb1cdaf8afdadf56724849">Segments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9478df12750b28a65d83fa06cccaf2c">ActiveRegions</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment">CoverageSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8282297d221bfcda27421d3ed9792a">buildSegments</a> (MutableArrayRef&lt; CountedRegion &gt; Regions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a sorted list of CoverageSegments from a list of Regions. <a href="#a3f8282297d221bfcda27421d3ed9792a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0816805d17b126067e1d95ea9c7ee722">sortNestedRegions</a> (MutableArrayRef&lt; CountedRegion &gt; Regions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort a nested sequence of regions from a single file. <a href="#a0816805d17b126067e1d95ea9c7ee722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b1f7a3452c5cf3c65436d35aa0be1b">combineRegions</a> (MutableArrayRef&lt; CountedRegion &gt; Regions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine counts of regions which cover the same area. <a href="#a91b1f7a3452c5cf3c65436d35aa0be1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### SegmentBuilder() {#a465fe9d0416eff2d05c6e854334c3f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CoverageMapping.cpp}::SegmentBuilder::SegmentBuilder (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment">CoverageSegment</a> &gt; &amp; Segments)</td>
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



<p>Definition at line 1134 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildSegmentsImpl() {#a331360b1539ddfa158145ef019e1b5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::SegmentBuilder::buildSegmentsImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &gt; Regions)</td>
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



<p>Definition at line 1228 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### completeRegionsUntil() {#a5c8433456c6ef84e4cc037f6f108d276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::SegmentBuilder::completeRegionsUntil (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a851320504101eab08260161f30355996">LineColPair</a> &gt; Loc, unsigned FirstCompletedRegion)</td>
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

<p>Emit segments for active regions which end before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>:</span> The start location of the next region. If std::nullopt, all active regions are completed. <span class="doxyComputerOutput">FirstCompletedRegion:</span> Index of the first completed region.</p>


<p>Definition at line 1175 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### startSegment() {#afa2091cacde43c2884f003c63f0741a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::SegmentBuilder::startSegment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &amp; Region, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a851320504101eab08260161f30355996">LineColPair</a> StartLoc, bool IsRegionEntry, bool EmitSkippedRegion=false)</td>
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

<p>Emit a segment with the count from <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> starting at <span class="doxyComputerOutput">StartLoc</span>.</p>


<p><span class="doxyComputerOutput">IsRegionEntry:</span> The segment is at the start of a new non-gap region. <span class="doxyComputerOutput">EmitSkippedRegion:</span> The segment must be emitted as a skipped region.</p>


<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ActiveRegions {#ad9478df12750b28a65d83fa06cccaf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const CountedRegion *, 8&gt; anonymous{CoverageMapping.cpp}::SegmentBuilder::ActiveRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### Segments {#a13a4e9609ccb1cdaf8afdadf56724849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CoverageSegment&gt;&amp; anonymous{CoverageMapping.cpp}::SegmentBuilder::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### buildSegments() {#a3f8282297d221bfcda27421d3ed9792a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; CoverageSegment &gt; anonymous{CoverageMapping.cpp}::SegmentBuilder::buildSegments (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &gt; Regions)</td>
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

<p>Build a sorted list of CoverageSegments from a list of Regions.</p>

<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a34ad2641d791bf884c9a78152d2a9782">llvm::coverage::CoverageMapping::getCoverageForExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#adaf5d4d6faed1306110085c3b7569213">llvm::coverage::CoverageMapping::getCoverageForFile</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#ac13588be0e11b5b26d15a3c4c5c41082">llvm::coverage::CoverageMapping::getCoverageForFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### combineRegions() {#a91b1f7a3452c5cf3c65436d35aa0be1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; CountedRegion &gt; anonymous{CoverageMapping.cpp}::SegmentBuilder::combineRegions (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &gt; Regions)</td>
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

<p>Combine counts of regions which cover the same area.</p>

<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### sortNestedRegions() {#a0816805d17b126067e1d95ea9c7ee722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::SegmentBuilder::sortNestedRegions (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a> &gt; Regions)</td>
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

<p>Sort a nested sequence of regions from a single file.</p>

<p>Definition at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
