---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/loopcacheanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LoopCacheAnalysis.cpp` File

<p>This file defines the implementation for the loop cache analysis. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">llvm/Analysis/LoopCacheAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/breadthfirstiterator-h">llvm/ADT/BreadthFirstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sequence-h">llvm/ADT/Sequence.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/delinearization-h">llvm/Analysis/Delinearization.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">llvm/Analysis/DependenceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3e30ba3a19f0debefc124b3682a1a1">getInnerMostLoop</a> (const LoopVectorTy &amp;Loops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the innermost loop in the given loop nest <span class="doxyComputerOutput">Loops</span>. <a href="#a8b3e30ba3a19f0debefc124b3682a1a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a> (const SCEV &amp;AccessFn, const SCEV &amp;ElemSize, const Loop &amp;L, ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a> (const Loop &amp;L, const SCEV &amp;ElemSize, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the trip count for the given loop <span class="doxyComputerOutput">L</span> or assume a default value if it is not a compile time constant. <a href="#a605f4ae007c6b19244c175eb1990abc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed354954ff68154d1ca7f088d95a8a53">DefaultTripCount</a>("default-trip-count", cl::init(100), cl::Hidden, cl::desc("Use this to specify the default trip count of a loop"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b2f22a247da9ef886c267dfb77cd4d">TemporalReuseThreshold</a>("temporal-reuse-threshold", cl::init(2), cl::Hidden, cl::desc("Use this to specify the max. distance between array elements " "accessed in a loop so that the elements are classified to have " "temporal reuse"))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"loop-cache-cost"</td>
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

<p>This file defines the implementation for the loop cache analysis.</p>


<p>The implementation is largely based on the following paper:</p>



<pre><code>  Compiler Optimizations for Improving Data Locality
  By: Steve Carr, Katherine S. McKinley, Chau-Wen Tseng
  http://www.cs.utexas.edu/users/mckinley/papers/asplos-1994.pdf
</code></pre>


<p>The general approach taken to estimate the number of cache lines used by the memory references in an inner loop is:</p>


<ol class="doxyList" type="1">
<li>Partition memory references that exhibit temporal or spacial reuse into reference groups.</li>
<li>For each loop L in the a loop nest LN: a. Compute the cost of the reference group b. Compute the loop cost by summing up the reference groups costs</li>
</ol>

<div class="doxySectionDef">

## Functions

### computeTripCount() {#a605f4ae007c6b19244c175eb1990abc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * computeTripCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; ElemSize, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Compute the trip count for the given loop <span class="doxyComputerOutput">L</span> or assume a default value if it is not a compile time constant.</p>


<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the trip count.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aed354954ff68154d1ca7f088d95a8a53">DefaultTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a22d9bcbd44563106d7217f3bd9a4039e">llvm::ScalarEvolution::getBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3e3935d45c4b79b85a117b47cc1d2e61">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a>.</p>

</div>
</div>

### getInnerMostLoop() {#a8b3e30ba3a19f0debefc124b3682a1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * getInnerMostLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a> &amp; Loops)</td>
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

<p>Retrieve the innermost loop in the given loop nest <span class="doxyComputerOutput">Loops</span>.</p>


<p>It returns a nullptr if any loops in the loop vector supplied has more than one sibling. The loop vector is expected to contain loops collected in breadth-first order.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a57994482c17097d9f936acff3a6598ac">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>.</p>

</div>
</div>

### isOneDimensionalArray() {#a04de41a04706e275a5161b62cfe2b790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOneDimensionalArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; AccessFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; ElemSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a083bb1deb1d2ba244a99ceae9e734bc1">llvm::ScalarEvolution::getNegativeSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a1b9806d21518ef7fb4d5c4299e21411f">llvm::ScalarEvolution::isKnownNegative</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefaultTripCount {#aed354954ff68154d1ca7f088d95a8a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; DefaultTripCount("default-trip-count", cl::init(100), cl::Hidden, cl::desc("Use this to specify the default trip count of a loop"))</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#a2db9458acd704df3f1edef80bcd75121">llvm::CacheCost::CacheCost</a> and <a href="#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>.</p>

</div>
</div>

### TemporalReuseThreshold {#a51b2f22a247da9ef886c267dfb77cd4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TemporalReuseThreshold("temporal-reuse-threshold", cl::init(2), cl::Hidden, cl::desc("Use this to specify the max. distance between array elements " "accessed in a loop so that the elements are classified to have " "temporal reuse"))</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#a2db9458acd704df3f1edef80bcd75121">llvm::CacheCost::CacheCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"loop-cache-cost"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
