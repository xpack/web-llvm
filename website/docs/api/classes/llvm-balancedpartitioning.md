---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/balancedpartitioning
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BalancedPartitioning` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BalancedPartitioning { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">llvm/Support/BalancedPartitioning.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d508a5461701463a77e7ce2313708a">SignaturesT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; UtilitySignature, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87aa436baf733e7a0624b54d8e7cdded">FunctionNodeRange</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/bpfunctionnode">BPFunctionNode</a> &gt;::iterator &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a935fd76f6365678890bdc8ddd40d9">BalancedPartitioningTest_MoveGain_Test</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae696c5201cce93195993231c207665e2">BalancedPartitioning</a> (const BalancedPartitioningConfig &amp;Config)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279d13f4cbd5c771960ef6aadd6b4cda">run</a> (std::vector&lt; BPFunctionNode &gt; &amp;Nodes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run recursive graph partitioning that optimizes a given objective. <a href="#a279d13f4cbd5c771960ef6aadd6b4cda">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd9f511d48e4a4b5e6a80d1a7e56b1e">bisect</a> (const FunctionNodeRange Nodes, unsigned RecDepth, unsigned RootBucket, unsigned Offset, std::optional&lt; BPThreadPool &gt; &amp;TP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a recursive bisection of a given list of FunctionNodes. <a href="#a7fd9f511d48e4a4b5e6a80d1a7e56b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3cb0f8ea12af62256544c89df0a712">runIterations</a> (const FunctionNodeRange Nodes, unsigned LeftBucket, unsigned RightBucket, std::mt19937 &amp;RNG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run bisection iterations. <a href="#afa3cb0f8ea12af62256544c89df0a712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b0611cb9de840153820a97de472f37">runIteration</a> (const FunctionNodeRange Nodes, unsigned LeftBucket, unsigned RightBucket, SignaturesT &amp;Signatures, std::mt19937 &amp;RNG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a bisection iteration to improve the optimization goal. <a href="#a04b0611cb9de840153820a97de472f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05415d0f2b45e5ce7a63eba9f9faca10">moveFunctionNode</a> (BPFunctionNode &amp;N, unsigned LeftBucket, unsigned RightBucket, SignaturesT &amp;Signatures, std::mt19937 &amp;RNG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to move <span class="doxyComputerOutput">N</span> from one bucket to another. <a href="#a05415d0f2b45e5ce7a63eba9f9faca10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24285085fa8055cca8f921a371cfd84c">split</a> (const FunctionNodeRange Nodes, unsigned StartBucket) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split all the FunctionNodes into 2 buckets, StartBucket and StartBucket + 1 The method is used for an initial assignment before a bisection step. <a href="#a24285085fa8055cca8f921a371cfd84c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b12eace88b5740631cec25e75e3429">logCost</a> (unsigned X, unsigned Y) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of the uniform log-gap cost, assuming a utility node has <span class="doxyComputerOutput">X</span> FunctionNodes in the left bucket and <span class="doxyComputerOutput">Y</span> FunctionNodes in the right one. <a href="#a57b12eace88b5740631cec25e75e3429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60956068f1ad101aad2b00653471eb13">log2Cached</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/balancedpartitioningconfig">BalancedPartitioningConfig</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d9d9a4b59dbd54e5b5967e4b489057">Config</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f4d3e499978bcdfa784f2453cd7f79">Log2Cache</a>[LOG_CACHE_SIZE]</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238d245e46593cc4a4f912a2bc53984f">moveGain</a> (const BPFunctionNode &amp;N, bool FromLeftToRight, const SignaturesT &amp;Signatures)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the move gain for uniform log-gap cost. <a href="#a238d245e46593cc4a4f912a2bc53984f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d10fda47fb6f7b1d9f38472ab41b6a">LOG_CACHE_SIZE</a> = 16384</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Precomputed values of log2(x). Table size is small enough to fit in cache. <a href="#a44d10fda47fb6f7b1d9f38472ab41b6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FunctionNodeRange {#a87aa436baf733e7a0624b54d8e7cdded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BalancedPartitioning::FunctionNodeRange = 
      iterator_range&lt;std::vector&lt;BPFunctionNode&gt;::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### SignaturesT {#af9d508a5461701463a77e7ce2313708a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BalancedPartitioning::SignaturesT =  SmallVector&lt;UtilitySignature, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BalancedPartitioningTest\_MoveGain\_Test {#ac6a935fd76f6365678890bdc8ddd40d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class BalancedPartitioningTest_MoveGain_Test</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Reference <a href="#ac6a935fd76f6365678890bdc8ddd40d9">BalancedPartitioningTest_MoveGain_Test</a>.</p>


<p>Referenced by <a href="#ac6a935fd76f6365678890bdc8ddd40d9">BalancedPartitioningTest_MoveGain_Test</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BalancedPartitioning() {#ae696c5201cce93195993231c207665e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BalancedPartitioning::BalancedPartitioning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/balancedpartitioningconfig">BalancedPartitioningConfig</a> &amp; Config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a279d13f4cbd5c771960ef6aadd6b4cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BalancedPartitioning::run (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/bpfunctionnode">BPFunctionNode</a> &gt; &amp; Nodes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run recursive graph partitioning that optimizes a given objective.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### bisect() {#a7fd9f511d48e4a4b5e6a80d1a7e56b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BalancedPartitioning::bisect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">FunctionNodeRange</a> Nodes, unsigned RecDepth, unsigned RootBucket, unsigned Offset, std::optional&lt; BPThreadPool &gt; &amp; TP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run a recursive bisection of a given list of FunctionNodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RecDepth</td>
<td class="doxyParamItemDescription"><p>the current depth of recursion</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RootBucket</td>
<td class="doxyParamItemDescription"><p>the initial bucket of the dataVertices</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>the assigned buckets are the range [Offset, Offset + Nodes.size()]</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### log2Cached() {#a60956068f1ad101aad2b00653471eb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float BalancedPartitioning::log2Cached (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### logCost() {#a57b12eace88b5740631cec25e75e3429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float BalancedPartitioning::logCost (unsigned X, unsigned Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of the uniform log-gap cost, assuming a utility node has <span class="doxyComputerOutput">X</span> FunctionNodes in the left bucket and <span class="doxyComputerOutput">Y</span> FunctionNodes in the right one.</p>

<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### moveFunctionNode() {#a05415d0f2b45e5ce7a63eba9f9faca10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BalancedPartitioning::moveFunctionNode (<a href="/web-llvm/docs/api/classes/llvm/bpfunctionnode">BPFunctionNode</a> &amp; N, unsigned LeftBucket, unsigned RightBucket, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SignaturesT</a> &amp; Signatures, std::mt19937 &amp; RNG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to move <span class="doxyComputerOutput">N</span> from one bucket to another.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff <span class="doxyComputerOutput">N</span> is moved</p></dd>
</dl>


<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### runIteration() {#a04b0611cb9de840153820a97de472f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BalancedPartitioning::runIteration (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">FunctionNodeRange</a> Nodes, unsigned LeftBucket, unsigned RightBucket, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SignaturesT</a> &amp; Signatures, std::mt19937 &amp; RNG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run a bisection iteration to improve the optimization goal.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the total number of moved FunctionNodes</p></dd>
</dl>


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### runIterations() {#afa3cb0f8ea12af62256544c89df0a712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BalancedPartitioning::runIterations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">FunctionNodeRange</a> Nodes, unsigned LeftBucket, unsigned RightBucket, std::mt19937 &amp; RNG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run bisection iterations.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

### split() {#a24285085fa8055cca8f921a371cfd84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BalancedPartitioning::split (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">FunctionNodeRange</a> Nodes, unsigned StartBucket)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split all the FunctionNodes into 2 buckets, StartBucket and StartBucket + 1 The method is used for an initial assignment before a bisection step.</p>

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Config {#af9d9d9a4b59dbd54e5b5967e4b489057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BalancedPartitioningConfig&amp; llvm::BalancedPartitioning::Config</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### Log2Cache {#a24f4d3e499978bcdfa784f2453cd7f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::BalancedPartitioning::Log2Cache[LOG_CACHE_SIZE]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### moveGain() {#a238d245e46593cc4a4f912a2bc53984f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float BalancedPartitioning::moveGain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bpfunctionnode">BPFunctionNode</a> &amp; N, bool FromLeftToRight, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SignaturesT</a> &amp; Signatures)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the move gain for uniform log-gap cost.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a8efadc1e398432637936757b43272daa">Signatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### LOG\_CACHE\_SIZE {#a44d10fda47fb6f7b1d9f38472ab41b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioning::LOG_CACHE_SIZE = 16384</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Precomputed values of log2(x). Table size is small enough to fit in cache.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
