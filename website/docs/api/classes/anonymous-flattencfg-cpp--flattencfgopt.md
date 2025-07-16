---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-flattencfg-cpp-/flattencfgopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FlattenCFGOpt` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{FlattenCFG.cpp}::FlattenCFGOpt { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e871a2e46ee5238f21562d2bf1c73d">FlattenCFGOpt</a> (AliasAnalysis *AA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602f2acd35dc9f79595697f2a5296541">run</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c4a877405938fc939c1d6a0608a66c">FlattenParallelAndOr</a> (BasicBlock *BB, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> parallel-and or parallel-or to generate conditions for conditional branches. <a href="#a01c4a877405938fc939c1d6a0608a66c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65d79d777754e58abf8492a744102e07">MergeIfRegion</a> (BasicBlock *BB, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If. <a href="#a65d79d777754e58abf8492a744102e07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6497762f15f3955e4f17e95706189cb">CompareIfRegionBlock</a> (BasicBlock *Block1, BasicBlock *Block2, BasicBlock *Head2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare a pair of blocks: <span class="doxyComputerOutput">Block1</span> and <span class="doxyComputerOutput">Block2</span>, which are from two if-regions, where <span class="doxyComputerOutput">Head2</span> is the entry block of the 2nd if-region. <a href="#aa6497762f15f3955e4f17e95706189cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58aaa09a6e2d647ecdf2ff5624c5d578">AA</a></td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FlattenCFGOpt() {#ae4e871a2e46ee5238f21562d2bf1c73d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{FlattenCFG.cpp}::FlattenCFGOpt::FlattenCFGOpt (<a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a17cfa55ecdb44273a17f59b0a68503eb">llvm::FlattenCFG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a602f2acd35dc9f79595697f2a5296541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FlattenCFGOpt::run (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CompareIfRegionBlock() {#aa6497762f15f3955e4f17e95706189cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FlattenCFGOpt::CompareIfRegionBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Block1, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Block2, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Head2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare a pair of blocks: <span class="doxyComputerOutput">Block1</span> and <span class="doxyComputerOutput">Block2</span>, which are from two if-regions, where <span class="doxyComputerOutput">Head2</span> is the entry block of the 2nd if-region.</p>


<p>Compare blocks from two if-regions, where.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">Block1</span> and <span class="doxyComputerOutput">Block2</span> contain identical instructions, and have no memory reference alias with <span class="doxyComputerOutput">Head2</span>. This is used as a legality check for merging if-regions.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Head2</td>
<td class="doxyParamItemDescription"><p>is the entry of the 2nd if-region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Block1</td>
<td class="doxyParamItemDescription"><p>is a block in the 1st if-region to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Block2</td>
<td class="doxyParamItemDescription"><p>is a block in the 2nd if-region to compare.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if Block1 and Block2 have identical instructions and do not have memory reference alias with Head2.</p></dd>
</dl>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>

</div>
</div>

### FlattenParallelAndOr() {#a01c4a877405938fc939c1d6a0608a66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FlattenCFGOpt::FlattenParallelAndOr (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> parallel-and or parallel-or to generate conditions for conditional branches.</p>


<p>If.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] BB</td>
<td class="doxyParamItemDescription"><p>has more than one predecessor that is a conditional branch, attempt to use parallel and/or for the branch condition.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success.</p></dd>
</dl>


<p>Before: ...... cmp10 = fcmp une float tmp1, tmp2 br i1 cmp10, label if.then, label lor.rhs</p>


<p>lor.rhs: ...... cmp11 = fcmp une float tmp3, tmp4 br i1 cmp11, label if.then, label ifend</p>


<p>if.end: // the merge block ......</p>


<p>if.then: // has two predecessors, both of them contains conditional branch. ...... br label if.end;</p>


<p>After: ...... cmp10 = fcmp une float tmp1, tmp2 ...... cmp11 = fcmp une float tmp3, tmp4 cmp12 = or i1 cmp10, cmp11 // parallel-or mode. br i1 cmp12, label if.then, label ifend</p>


<p>if.end: ......</p>


<p>if.then: ...... br label if.end;</p>


<p>Current implementation handles two cases. Case 1: BB is on the else-path.</p>



<pre><code>    BB1
  /     |
 BB2    |
/   \   |
</code></pre>


<p>BB3 \ | where, BB1, BB2 contain conditional branches. \ | / BB3 contains unconditional branch. \ | / BB4 corresponds to BB which is also the merge. BB =&gt; BB4</p>


<p>Corresponding source code:</p>


<p>if (a == b &amp;&amp; c == d) statement; // BB3</p>


<p>Case 2: BB is on the then-path.</p>



<pre><code>       BB1
    /      |
   |      BB2
   \    /    |  where BB1, BB2 contain conditional branches.
</code></pre>


<p>BB =&gt; BB3 | BB3 contains unconditiona branch and corresponds \ / to BB. BB4 is the merge. BB4</p>


<p>Corresponding source code:</p>


<p>if (a == b || c == d) statement; // BB3</p>


<p>In both cases, BB is the common successor of conditional branches. In Case 1, BB (BB4) has an unconditional branch (BB3) as its predecessor. In Case 2, BB (BB3) only has conditional branches as its predecessors.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>

</div>
</div>

### MergeIfRegion() {#a65d79d777754e58abf8492a744102e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FlattenCFGOpt::MergeIfRegion (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If.</p>


<p>Check whether.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>is the merge block of an if-region, attempt to merge the if-region with an adjacent if-region upstream if two if-regions contain identical instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>is the merge block of a if-region. If yes, check whether there exists an adjacent if-region upstream, the two if-regions contain identical instructions and can be legally merged.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the two if-regions are merged.</p></dd>
</dl>


<p>From: if (a) statement; if (b) statement;</p>


<p>To: if (a || b) statement;</p>


<p>And from: if (a) ; else statement; if (b) ; else statement;</p>


<p>To: if (a &amp;&amp; b) ; else statement;</p>


<p>We always take the form of the first if-region. This means that if the statement in the first if-region, is in the "then-path", while in the second if-region it is in the "else-path", then we convert the second to the first form, by inverting the condition and the branch successors. The same approach goes for the opposite case.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a58aaa09a6e2d647ecdf2ff5624c5d578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{FlattenCFG.cpp}::FlattenCFGOpt::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/flattencfg-cpp">FlattenCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
