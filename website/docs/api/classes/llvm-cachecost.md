---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cachecost
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CacheCost` Class Reference

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a></span> represents the estimated cost of a inner loop as the number of cache lines used by the memory references it contains. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CacheCost { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">llvm/Analysis/LoopCacheAnalysis.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39adfb717d2e5948ce40e5d7aaa94f66">LoopTripCountTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e7fa19be9906cb7159a62bb90c7ad5">LoopCacheCostTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cc894ddad08bd7a0c618141f7ece5f3">CacheCostTy</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacdc6d3e99463d9d10cafa0181aac761">operator&lt;&lt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db9458acd704df3f1edef80bcd75121">CacheCost</a> (const LoopVectorTy &amp;Loops, const LoopInfo &amp;LI, ScalarEvolution &amp;SE, TargetTransformInfo &amp;TTI, AAResults &amp;AA, DependenceInfo &amp;DI, std::optional&lt; unsigned &gt; TRT=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> object for the loop nest described by <span class="doxyComputerOutput">Loops</span>. <a href="#a2db9458acd704df3f1edef80bcd75121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1cc894ddad08bd7a0c618141f7ece5f3">CacheCostTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14c5c1bfcf45b9ab5be1911532eca4c">getLoopCost</a> (const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the estimated cost of loop <span class="doxyComputerOutput">L</span> if the given loop is part of the loop nest associated with this object. <a href="#ae14c5c1bfcf45b9ab5be1911532eca4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; LoopCacheCostTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43aa7ccf009b6e2a2ad77cee9693f6d1">getLoopCosts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the estimated ordered loop costs. <a href="#a43aa7ccf009b6e2a2ad77cee9693f6d1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfabf549697eb8956a6cf7e17a76754a">calculateCacheFootprint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the cache footprint of each loop in the nest (when it is considered to be in the innermost position). <a href="#abfabf549697eb8956a6cf7e17a76754a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746ef146f75ef1ac0f5983517ce2742c">populateReferenceGroups</a> (ReferenceGroupsTy &amp;RefGroups) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partition store/load instructions in the loop nest into reference groups. <a href="#a746ef146f75ef1ac0f5983517ce2742c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1cc894ddad08bd7a0c618141f7ece5f3">CacheCostTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0779f9f46859809b945be45ee984dae">computeLoopCacheCost</a> (const Loop &amp;L, const ReferenceGroupsTy &amp;RefGroups) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the cost of the given loop <span class="doxyComputerOutput">L</span> assuming it is the innermost loop in nest. <a href="#aa0779f9f46859809b945be45ee984dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1cc894ddad08bd7a0c618141f7ece5f3">CacheCostTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6d8ebfaadbd658fde419cd48098695">computeRefGroupCacheCost</a> (const ReferenceGroupTy &amp;RG, const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cost of a representative reference in reference group <span class="doxyComputerOutput">RG</span> when the given loop <span class="doxyComputerOutput">L</span> is considered as the innermost loop in the nest. <a href="#a7d6d8ebfaadbd658fde419cd48098695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6662ecc3c3c9c61b48355be36936d221">sortLoopCosts</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort the LoopCosts vector by decreasing cache cost. <a href="#a6662ecc3c3c9c61b48355be36936d221">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb000270489064c858fb4b790ed22bd">Loops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loops in the loop nest associated with this object. <a href="#abfb000270489064c858fb4b790ed22bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LoopTripCountTy, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc095d39743fdea105d4566893493206">TripCounts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trip counts for the loops in the loop nest associated with this object. <a href="#abc095d39743fdea105d4566893493206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LoopCacheCostTy, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5f7e43cf268579108487436f3914b4">LoopCosts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache costs for the loops in the loop nest associated with this object. <a href="#aba5f7e43cf268579108487436f3914b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d700c613dbfcb1e93ea14930c848bc">TRT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The max. <a href="#ad0d700c613dbfcb1e93ea14930c848bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35412369bcec316026e8a45ac314d36">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5326ce447cb9bb6b094b390693fbd2">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e7433cfc0ceca0a2e4cff160189c03">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af802ae4e0fdafcc8613fb83de0bf3cc7">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac156f833f21f0b1eee517d11a3e2953d">DI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa74e490a12ab54ad9687e6844fe605f1">getCacheCost</a> (Loop &amp;Root, LoopStandardAnalysisResults &amp;AR, DependenceInfo &amp;DI, std::optional&lt; unsigned &gt; TRT=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> for the loop nest rooted by <span class="doxyComputerOutput">Root</span>. <a href="#aa74e490a12ab54ad9687e6844fe605f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a></span> represents the estimated cost of a inner loop as the number of cache lines used by the memory references it contains.</p>


<p>The 'cache cost' of a loop 'L' in a loop nest 'LN' is computed as the sum of the cache costs of all of its reference groups when the loop is considered to be in the innermost position in the nest. A reference group represents memory references that fall into the same cache line. Each reference group is analysed with respect to the innermost loop in a loop nest. The cost of a reference is defined as follow:</p>


<ul class="doxyList ">
<li>one if it is loop invariant w.r.t the innermost loop,</li>
<li>equal to the loop trip count divided by the cache line times the reference stride if the reference stride is less than the cache line size (CLS), and the coefficient of this loop's index variable used in all other subscripts is zero (e.g. RefCost = TripCount/(CLS/RefStride))</li>
<li>equal to the innermost loop trip count if the reference stride is greater or equal to the cache line size CLS.</li>
</ul>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LoopCacheCostTy {#ac2e7fa19be9906cb7159a62bb90c7ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CacheCost::LoopCacheCostTy =  std::pair&lt;const Loop *, CacheCostTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### LoopTripCountTy {#a39adfb717d2e5948ce40e5d7aaa94f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CacheCost::LoopTripCountTy =  std::pair&lt;const Loop *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#aacdc6d3e99463d9d10cafa0181aac761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> &amp; CC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>References <a href="#a2db9458acd704df3f1edef80bcd75121">CacheCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CacheCost() {#a2db9458acd704df3f1edef80bcd75121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheCost::CacheCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a> &amp; Loops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, std::optional&lt; unsigned &gt; TRT=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> object for the loop nest described by <span class="doxyComputerOutput">Loops</span>.</p>


<p>The optional parameter <span class="doxyComputerOutput">TRT</span> can be used to specify the max. distance between array elements accessed in a loop so that the elements are classified to have temporal reuse.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#aed354954ff68154d1ca7f088d95a8a53">DefaultTripCount</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a51b2f22a247da9ef886c267dfb77cd4d">TemporalReuseThreshold</a>.</p>


<p>Referenced by <a href="#aacdc6d3e99463d9d10cafa0181aac761">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getLoopCost() {#ae14c5c1bfcf45b9ab5be1911532eca4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheCostTy llvm::CacheCost::getLoopCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
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

<p>Return the estimated cost of loop <span class="doxyComputerOutput">L</span> if the given loop is part of the loop nest associated with this object.</p>


<p>Return -1 otherwise.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>.</p>

</div>
</div>

### getLoopCosts() {#a43aa7ccf009b6e2a2ad77cee9693f6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; LoopCacheCostTy &gt; llvm::CacheCost::getLoopCosts ()</td>
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

<p>Return the estimated ordered loop costs.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateCacheFootprint() {#abfabf549697eb8956a6cf7e17a76754a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CacheCost::calculateCacheFootprint ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the cache footprint of each loop in the nest (when it is considered to be in the innermost position).</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### computeLoopCacheCost() {#aa0779f9f46859809b945be45ee984dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheCostTy CacheCost::computeLoopCacheCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aef98c9f2de85c49568e5bdc094b97066">ReferenceGroupsTy</a> &amp; RefGroups)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the cost of the given loop <span class="doxyComputerOutput">L</span> assuming it is the innermost loop in nest.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### computeRefGroupCacheCost() {#a7d6d8ebfaadbd658fde419cd48098695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheCostTy CacheCost::computeRefGroupCacheCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a41a90a6262b81ec6c4f9db15111b6825">ReferenceGroupTy</a> &amp; RG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cost of a representative reference in reference group <span class="doxyComputerOutput">RG</span> when the given loop <span class="doxyComputerOutput">L</span> is considered as the innermost loop in the nest.</p>


<p>The computed cost is an estimate for the number of cache lines used by the reference group. The representative reference cost is defined as:</p>


<ul class="doxyList ">
<li>equal to one if the reference is loop invariant, or</li>
<li>equal to '(TripCount * stride) / cache_line_size' if (a) loop <span class="doxyComputerOutput">L's</span> induction variable is used only in the reference subscript associated with loop <span class="doxyComputerOutput">L</span>, and (b) the reference stride is less than the cache line size, or</li>
<li>TripCount otherwise</li>
</ul>

<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### populateReferenceGroups() {#a746ef146f75ef1ac0f5983517ce2742c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CacheCost::populateReferenceGroups (<a href="/web-llvm/docs/api/namespaces/llvm/#aef98c9f2de85c49568e5bdc094b97066">ReferenceGroupsTy</a> &amp; RefGroups)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partition store/load instructions in the loop nest into reference groups.</p>


<p>Two or more memory accesses belong in the same reference group if they share the same cache line.</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### sortLoopCosts() {#a6662ecc3c3c9c61b48355be36936d221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CacheCost::sortLoopCosts ()</td>
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

<p>Sort the LoopCosts vector by decreasing cache cost.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#af802ae4e0fdafcc8613fb83de0bf3cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; llvm::CacheCost::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### DI {#ac156f833f21f0b1eee517d11a3e2953d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo&amp; llvm::CacheCost::DI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### LI {#ae35412369bcec316026e8a45ac314d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo&amp; llvm::CacheCost::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### LoopCosts {#aba5f7e43cf268579108487436f3914b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LoopCacheCostTy, 3&gt; llvm::CacheCost::LoopCosts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache costs for the loops in the loop nest associated with this object.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### Loops {#abfb000270489064c858fb4b790ed22bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorTy llvm::CacheCost::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loops in the loop nest associated with this object.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### SE {#aac5326ce447cb9bb6b094b390693fbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::CacheCost::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### TripCounts {#abc095d39743fdea105d4566893493206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LoopTripCountTy, 3&gt; llvm::CacheCost::TripCounts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Trip counts for the loops in the loop nest associated with this object.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### TRT {#ad0d700c613dbfcb1e93ea14930c848bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::CacheCost::TRT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The max.</p>


<p>distance between array elements accessed in a loop so that the elements are classified to have temporal reuse.</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### TTI {#a92e7433cfc0ceca0a2e4cff160189c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo&amp; llvm::CacheCost::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCacheCost() {#aa74e490a12ab54ad9687e6844fe605f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CacheCost &gt; CacheCost::getCacheCost (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; Root, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, std::optional&lt; unsigned &gt; TRT=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> for the loop nest rooted by <span class="doxyComputerOutput">Root</span>.</p>


<p>The optional parameter <span class="doxyComputerOutput">TRT</span> can be used to specify the max. distance between array elements accessed in a loop so that the elements are classified to have temporal reuse.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#abd7da877be8576011299f4fcaaf299be">llvm::LoopStandardAnalysisResults::AA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c754cdf7230d80a20aded3ead0c6d37">llvm::breadth_first</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a8b3e30ba3a19f0debefc124b3682a1a1">getInnerMostLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a0fa33dfd6ffaaae721fc05b6941263aa">llvm::LoopBase&lt; BlockT, LoopT &gt;::isOutermost</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aa09379aa4435be95eb717dd9b5d8b4c5">llvm::LoopStandardAnalysisResults::LI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a124376878e24aef4252795ba9fea420f">llvm::LoopStandardAnalysisResults::SE</a> and <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a3444a9359f5f17f1694f82c41d5fd574">llvm::LoopStandardAnalysisResults::TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopcacheprinterpass/#aa35925026f576bd3c47e2f91cd2eb737">llvm::LoopCachePrinterPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
