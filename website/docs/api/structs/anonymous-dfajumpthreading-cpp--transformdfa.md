---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-dfajumpthreading-cpp-/transformdfa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TransformDFA` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{DFAJumpThreading.cpp}::TransformDFA { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866bc63efb375b4f6dc2f7e7294c7161">TransformDFA</a> (AllSwitchPaths *SwitchPaths, DominatorTree *DT, AssumptionCache *AC, TargetTransformInfo *TTI, OptimizationRemarkEmitter *ORE, SmallPtrSet&lt; const Value *, 32 &gt; EphValues)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabdf44b328c31c8eac25a7560df3d935">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb9fcff7d8888ca5e65783ed29f23ce">isLegalAndProfitableToTransform</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function performs both a legality check and profitability check at the same time since it is convenient to do so. <a href="#a5eb9fcff7d8888ca5e65783ed29f23ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b24549f6352eff5cc808c5f58a46f23">createAllExitPaths</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform each threading path to effectively jump thread the DFA. <a href="#a3b24549f6352eff5cc808c5f58a46f23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90e56ad89e5063254fc120dfde4aa7c">createExitPath</a> (DefMap &amp;NewDefs, ThreadingPath &amp;Path, DuplicateBlockMap &amp;DuplicateMap, SmallSet&lt; BasicBlock *, 16 &gt; &amp;BlocksToClean, DomTreeUpdater *DTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a specific <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/threadingpath">ThreadingPath</a> <span class="doxyComputerOutput">Path</span>, create an exit path starting from the determinator block. <a href="#ac90e56ad89e5063254fc120dfde4aa7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52dde36a7734846ad7ac8fc9e562051c">updateSSA</a> (DefMap &amp;NewDefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore SSA form after cloning blocks. <a href="#a52dde36a7734846ad7ac8fc9e562051c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e8a44f0b19e974a79b9fd85199ffed">cloneBlockAndUpdatePredecessor</a> (BasicBlock *BB, BasicBlock *PrevBB, const APInt &amp;NextState, DuplicateBlockMap &amp;DuplicateMap, DefMap &amp;NewDefs, DomTreeUpdater *DTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clones a basic block, and adds it to the CFG. <a href="#a19e8a44f0b19e974a79b9fd85199ffed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6151565920414bc90910b85291ba68">updateSuccessorPhis</a> (BasicBlock *BB, BasicBlock *ClonedBB, const APInt &amp;NextState, ValueToValueMapTy &amp;VMap, DuplicateBlockMap &amp;DuplicateMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the phi nodes in BB's successors. <a href="#abc6151565920414bc90910b85291ba68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3b0abd58b31e252d3089ea3f06686f">updatePredecessor</a> (BasicBlock *PrevBB, BasicBlock *OldBB, BasicBlock *NewBB, DomTreeUpdater *DTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the successor of PrevBB to be NewBB instead of OldBB. <a href="#a4c3b0abd58b31e252d3089ea3f06686f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe982055f317e1eb7c901ff4a462c641">updateDefMap</a> (DefMap &amp;NewDefs, ValueToValueMapTy &amp;VMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add new value mappings to the <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> to keep track of all new definitions for a particular instruction. <a href="#abe982055f317e1eb7c901ff4a462c641">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa881cfcce78ccb07ec7a9f0a3c550855">updateLastSuccessor</a> (ThreadingPath &amp;TPath, DuplicateBlockMap &amp;DuplicateMap, DomTreeUpdater *DTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the last branch of a particular cloned path to point to the correct case successor. <a href="#aa881cfcce78ccb07ec7a9f0a3c550855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39190d3f52e9c4dce2cac0d6db847d8c">cleanPhiNodes</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After cloning blocks, some of the phi nodes have extra incoming values that are no longer used. <a href="#a39190d3f52e9c4dce2cac0d6db847d8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e58c29d32bef818a9f1719725c93840">getClonedBB</a> (BasicBlock *BB, const APInt &amp;NextState, DuplicateBlockMap &amp;DuplicateMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if BB was already cloned for a particular next state value. <a href="#a7e58c29d32bef818a9f1719725c93840">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502d0733a8a62fc311e413937a679ff3">getNextCaseSuccessor</a> (SwitchInst *Switch, const APInt &amp;NextState)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to get the successor corresponding to a particular case value for a switch statement. <a href="#a502d0733a8a62fc311e413937a679ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2c4fe945ca7b9c070871f24c66e735">isPredecessor</a> (BasicBlock *BB, BasicBlock *IncomingBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if IncomingBB is a predecessor of BB. <a href="#a7d2c4fe945ca7b9c070871f24c66e735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/allswitchpaths">AllSwitchPaths</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1216d9eb48f1bffb697e72b1e12348d4">SwitchPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cce2a8cc890ea62a15137e0c6342896">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f19bff2272c417e8e61a684b5df0fed">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a2b31eb4f8ed4171c94f5319c97475">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a6984c90e06561eb837f9f34b554d4">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6cae77f5ad5a6cb1cc8f5b31bc2bca0">EphValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/threadingpath">ThreadingPath</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b0dcbe4141e23383729b1f54a3b12f">TPaths</a></td>
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


<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TransformDFA() {#a866bc63efb375b4f6dc2f7e7294c7161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DFAJumpThreading.cpp}::TransformDFA::TransformDFA (<a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/allswitchpaths">AllSwitchPaths</a> * SwitchPaths, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt; EphValues)</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#aabdf44b328c31c8eac25a7560df3d935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::run ()</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cleanPhiNodes() {#a39190d3f52e9c4dce2cac0d6db847d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::cleanPhiNodes (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>After cloning blocks, some of the phi nodes have extra incoming values that are no longer used.</p>


<p>This function removes them.</p>


<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### cloneBlockAndUpdatePredecessor() {#a19e8a44f0b19e974a79b9fd85199ffed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{DFAJumpThreading.cpp}::TransformDFA::cloneBlockAndUpdatePredecessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PrevBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NextState, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a3ddf7646269f7d1fd4f236e83fc14ea0">DuplicateBlockMap</a> &amp; DuplicateMap, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> &amp; NewDefs, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
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

<p>Clones a basic block, and adds it to the CFG.</p>


<p>This function also includes updating phi nodes in the successors of the BB, and remapping uses that were defined locally in the cloned BB.</p>


<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### createAllExitPaths() {#a3b24549f6352eff5cc808c5f58a46f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::createAllExitPaths ()</td>
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

<p>Transform each threading path to effectively jump thread the DFA.</p>

<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### createExitPath() {#ac90e56ad89e5063254fc120dfde4aa7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::createExitPath (<a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> &amp; NewDefs, <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/threadingpath">ThreadingPath</a> &amp; Path, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a3ddf7646269f7d1fd4f236e83fc14ea0">DuplicateBlockMap</a> &amp; DuplicateMap, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt; &amp; BlocksToClean, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
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

<p>For a specific <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/threadingpath">ThreadingPath</a> <span class="doxyComputerOutput">Path</span>, create an exit path starting from the determinator block.</p>


<p>To remember the correct destination, we have to duplicate blocks corresponding to each state. Also update the terminating instruction of the predecessors, and phis in the successor blocks.</p>


<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### getClonedBB() {#a7e58c29d32bef818a9f1719725c93840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{DFAJumpThreading.cpp}::TransformDFA::getClonedBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NextState, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a3ddf7646269f7d1fd4f236e83fc14ea0">DuplicateBlockMap</a> &amp; DuplicateMap)</td>
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

<p>Checks if BB was already cloned for a particular next state value.</p>


<p>If it was then it returns this cloned block, and otherwise null.</p>


<p>Definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### getNextCaseSuccessor() {#a502d0733a8a62fc311e413937a679ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{DFAJumpThreading.cpp}::TransformDFA::getNextCaseSuccessor (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * Switch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NextState)</td>
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

<p>Helper to get the successor corresponding to a particular case value for a switch statement.</p>

<p>Definition at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### isLegalAndProfitableToTransform() {#a5eb9fcff7d8888ca5e65783ed29f23ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DFAJumpThreading.cpp}::TransformDFA::isLegalAndProfitableToTransform ()</td>
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

<p>This function performs both a legality check and profitability check at the same time since it is convenient to do so.</p>


<p>It iterates through all blocks that will be cloned, and keeps track of the duplication cost. It also returns false if it is illegal to clone some required block.</p>


<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### isPredecessor() {#a7d2c4fe945ca7b9c070871f24c66e735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DFAJumpThreading.cpp}::TransformDFA::isPredecessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IncomingBB)</td>
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

<p>Returns true if IncomingBB is a predecessor of BB.</p>

<p>Definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### updateDefMap() {#abe982055f317e1eb7c901ff4a462c641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::updateDefMap (<a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> &amp; NewDefs, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap)</td>
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

<p>Add new value mappings to the <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> to keep track of all new definitions for a particular instruction.</p>


<p>These will be used while updating SSA form.</p>


<p>Definition at line 1198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### updateLastSuccessor() {#aa881cfcce78ccb07ec7a9f0a3c550855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::updateLastSuccessor (<a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/threadingpath">ThreadingPath</a> &amp; TPath, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a3ddf7646269f7d1fd4f236e83fc14ea0">DuplicateBlockMap</a> &amp; DuplicateMap, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
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

<p>Update the last branch of a particular cloned path to point to the correct case successor.</p>


<p>Note that this is an optional step and would have been done in later optimizations, but it makes the CFG significantly easier to work with.</p>


<p>Definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### updatePredecessor() {#a4c3b0abd58b31e252d3089ea3f06686f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::updatePredecessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PrevBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OldBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewBB, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU)</td>
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

<p>Sets the successor of PrevBB to be NewBB instead of OldBB.</p>


<p>Note that all other successors are kept as well.</p>


<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### updateSSA() {#a52dde36a7734846ad7ac8fc9e562051c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::updateSSA (<a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a969421ec3c0c7d7b983f244f9cb99e48">DefMap</a> &amp; NewDefs)</td>
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

<p>Restore SSA form after cloning blocks.</p>


<p>Each cloned block creates new defs for a variable, and the uses need to be updated to reflect this. The uses may be replaced with a cloned value, or some derived phi instruction. Note that all uses of a value defined in the same block were already remapped when cloning the block.</p>


<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### updateSuccessorPhis() {#abc6151565920414bc90910b85291ba68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DFAJumpThreading.cpp}::TransformDFA::updateSuccessorPhis (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ClonedBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NextState, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a3ddf7646269f7d1fd4f236e83fc14ea0">DuplicateBlockMap</a> &amp; DuplicateMap)</td>
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

<p>Update the phi nodes in BB's successors.</p>


<p>This means creating a new incoming value from NewBB with the new instruction wherever there is an incoming value from BB.</p>


<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a2f19bff2272c417e8e61a684b5df0fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* anonymous{DFAJumpThreading.cpp}::TransformDFA::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### DT {#a3cce2a8cc890ea62a15137e0c6342896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{DFAJumpThreading.cpp}::TransformDFA::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### EphValues {#af6cae77f5ad5a6cb1cc8f5b31bc2bca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 32&gt; anonymous{DFAJumpThreading.cpp}::TransformDFA::EphValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### ORE {#aa6a6984c90e06561eb837f9f34b554d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{DFAJumpThreading.cpp}::TransformDFA::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### SwitchPaths {#a1216d9eb48f1bffb697e72b1e12348d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllSwitchPaths* anonymous{DFAJumpThreading.cpp}::TransformDFA::SwitchPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### TPaths {#af5b0dcbe4141e23383729b1f54a3b12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ThreadingPath&gt; anonymous{DFAJumpThreading.cpp}::TransformDFA::TPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

### TTI {#a72a2b31eb4f8ed4171c94f5319c97475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* anonymous{DFAJumpThreading.cpp}::TransformDFA::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp">DFAJumpThreading.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
