---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoopPeel.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looppeel-h">llvm/Transforms/Utils/LoopPeel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loads-h">llvm/Analysis/Loads.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">llvm/Analysis/LoopIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopsimplify-h">llvm/Transforms/Utils/LoopSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">llvm/Transforms/Utils/ValueMapper.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-looppeel-cpp-">anonymous{LoopPeel.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-looppeel-cpp-/phianalyzer">PhiAnalyzer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/weightinfo">WeightInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e9e8d290525be96b07046de14b8540">STATISTIC</a> (NumPeeled, "Number of loops peeled")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1d9cfaf2d4ef4eca30ce71eb8c3a89">peelToTurnInvariantLoadsDerefencebale</a> (Loop &amp;L, DominatorTree &amp;DT, AssumptionCache *AC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a> (Loop &amp;L, unsigned MaxPeelCount, ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d391dbabb8fc073db875548184a768d">violatesLegacyMultiExitLoopCheck</a> (Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This "heuristic" exactly matches implicit behavior which used to exist inside getLoopEstimatedTripCount. <a href="#a7d391dbabb8fc073db875548184a768d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070d953c06601ec34680fdc35c867b17">updateBranchWeights</a> (Instruction *Term, WeightInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the branch weights of an exiting block of a peeled-off loop iteration. <a href="#a070d953c06601ec34680fdc35c867b17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8a7753c2685a14185133433c0bbf26">initBranchWeights</a> (DenseMap&lt; Instruction *, WeightInfo &gt; &amp;WeightInfos, Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the weights for all exiting blocks. <a href="#acd8a7753c2685a14185133433c0bbf26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a> (Loop *L, unsigned IterNumber, BasicBlock *InsertTop, BasicBlock *InsertBot, SmallVectorImpl&lt; std::pair&lt; BasicBlock *, BasicBlock * &gt; &gt; &amp;ExitEdges, SmallVectorImpl&lt; BasicBlock * &gt; &amp;NewBlocks, LoopBlocksDFS &amp;LoopBlocks, ValueToValueMapTy &amp;VMap, ValueToValueMapTy &amp;LVMap, DominatorTree *DT, LoopInfo *LI, ArrayRef&lt; MDNode * &gt; LoopLocalNoAliasDeclScopes, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clones the body of the loop L, putting it between <span class="doxyComputerOutput">InsertTop</span> and <span class="doxyComputerOutput">InsertBot</span>. <a href="#a8478b291f8a10892334ba0bcf6a18528">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9badf8f59af8beee7f66a5252019f70">UnrollPeelCount</a>("unroll-peel-count", cl::Hidden, cl::desc("Set the unroll peeling count, for testing purposes"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626a61b9d8aa04db77aaff8e96059f93">UnrollAllowPeeling</a>("unroll-allow-peeling", cl::init(true), cl::Hidden, cl::desc("Allows loops to be peeled when the dynamic " "trip count is known to be low."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d9cb6aeac6c6254d62eeb6c4b662ee">UnrollAllowLoopNestsPeeling</a>("unroll-allow-loop-nests-peeling", cl::init(false), cl::Hidden, cl::desc("Allows loop nests to be peeled."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a7dd364657e3ef9947efb9224aaca4">UnrollPeelMaxCount</a>("unroll-peel-max-count", cl::init(7), cl::Hidden, cl::desc("Max average trip count which will cause loop peeling."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6383b9c934edc393f9e9f3fd992559aa">UnrollForcePeelCount</a>("unroll-force-peel-count", cl::init(0), cl::Hidden, cl::desc("Force a peel count regardless of profiling information."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354acc6ff0fdfde87ae2eb07c6127620">DisableAdvancedPeeling</a>("disable-advanced-peeling", cl::init(false), cl::Hidden, cl::desc("Disable advance peeling. Issues for convergent targets (D134803)."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5685c46cf812c90576046af45cd7fa">PeeledCountMetaData</a> = "llvm.loop.peeled.count"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"loop-peel"</td>
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


<div class="doxySectionDef">

## Functions

### cloneLoopBlocks() {#a8478b291f8a10892334ba0bcf6a18528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cloneLoopBlocks (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, unsigned IterNumber, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertTop, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBot, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; ExitEdges, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; NewBlocks, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs">LoopBlocksDFS</a> &amp; LoopBlocks, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; LVMap, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; LoopLocalNoAliasDeclScopes, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Clones the body of the loop L, putting it between <span class="doxyComputerOutput">InsertTop</span> and <span class="doxyComputerOutput">InsertBot</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IterNumber</td>
<td class="doxyParamItemDescription"><p>The serial number of the iteration currently being peeled off.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitEdges</td>
<td class="doxyParamItemDescription"><p>The exit edges of the original loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] NewBlocks</td>
<td class="doxyParamItemDescription"><p>A list of the blocks in the newly created clone</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] VMap</td>
<td class="doxyParamItemDescription"><p>The value map between the loop and the new clone.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoopBlocks</td>
<td class="doxyParamItemDescription"><p>A helper for DFS-traversal of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LVMap</td>
<td class="doxyParamItemDescription"><p>A value-map that maps instructions from the original loop to instructions in the last peeled-off iteration.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a63f099d3bf7cf97eb3ae2d630e3d1afc">llvm::LoopBase&lt; BlockT, LoopT &gt;::addBasicBlockToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a4211a49504539a8a37aebb00e1390370">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#a003fe6215d300fc9720b1b056cdf4c23">llvm::LoopBlocksDFS::beginRPO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a2881c226e1c102190d54c3b664330aba">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7abd0e34c17dcb201a4138dc65cc067">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe8e2e0edcd7756ff5985b8798270c5d">llvm::cloneLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#aeebda6b0288bea7cd706111624ca73f6">llvm::LoopBlocksDFS::endRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6dc58a1259941c7a17142e6103d059e">llvm::ScalarEvolution::forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae959364e4640ac025bbc046d3d7c7e61">llvm::Instruction::setSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>.</p>

</div>
</div>

### countToEliminateCompares() {#a7098623cafc05376a44b27d202b03372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned countToEliminateCompares (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, unsigned MaxPeelCount, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a33583576f220997d1c415df033559a57">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad80020012061cb562a6f9c9f715c2cf0">llvm::ScalarEvolution::evaluatePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0182f006bb2ae6411c2111427d58f242">llvm::ScalarEvolution::getConstantMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa92b3e6375805368f9a24cf69ce73797">llvm::ScalarEvolution::getMonotonicPredicateType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a6429bca8fd0024ceb2d76ccaace43c4e">llvm::SCEVNAryExpr::hasNoSelfWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a1b9806d21518ef7fb4d5c4299e21411f">llvm::ScalarEvolution::isKnownNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a672708a81ae8da8fb56e32638ca9b3">llvm::ScalarEvolution::isKnownPositive</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>.</p>

</div>
</div>

### initBranchWeights() {#acd8a7753c2685a14185133433c0bbf26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initBranchWeights (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/structs/weightinfo">WeightInfo</a> &gt; &amp; WeightInfos, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>Initialize the weights for all exiting blocks.</p>

<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>.</p>

</div>
</div>

### peelToTurnInvariantLoadsDerefencebale() {#aaa1d9cfaf2d4ef4eca30ce71eb8c3a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned peelToTurnInvariantLoadsDerefencebale (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a153ea412ff7a0ba105111155d1e16128">llvm::SmallPtrSetImpl&lt; PtrType &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf1028e2af158aae1e00d3288ca013bb">llvm::isDereferenceablePointer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>.</p>

</div>
</div>

### STATISTIC() {#ad7e9e8d290525be96b07046de14b8540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPeeled, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> peeled")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>

</div>
</div>

### updateBranchWeights() {#a070d953c06601ec34680fdc35c867b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateBranchWeights (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Term, <a href="/web-llvm/docs/api/structs/weightinfo">WeightInfo</a> &amp; Info)</td>
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

<p>Update the branch weights of an exiting block of a peeled-off loop iteration.</p>


<p>Let F is a weight of the edge to continue (fallthrough) into the loop. Let E is a weight of the edge to an exit. F/(F+E) is a probability to go to loop and E/(F+E) is a probability to go to exit. Then, Estimated ExitCount = F / E. For I-th (counting from 0) peeled off iteration we set the weights for the peeled exit as (EC - I, 1). It gives us reasonable distribution, The probability to go to exit 1/(EC-I) increases. At the same time the estimated exit count in the remainder loop reduces by I. To avoid dealing with division rounding we can just multiple both part of weights to E and use weight as (F - I * E, E).</p>


<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>.</p>

</div>
</div>

### violatesLegacyMultiExitLoopCheck() {#a7d391dbabb8fc073db875548184a768d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool violatesLegacyMultiExitLoopCheck (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>This "heuristic" exactly matches implicit behavior which used to exist inside getLoopEstimatedTripCount.</p>


<p>It was added here to keep an improvement inside that API from causing peeling to become more aggressive. This should probably be removed.</p>


<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a96b8f11f6f21ca0321294669dab83b35">llvm::BranchInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a6796a84f02394ce6ebef227c866cd5eb">llvm::BasicBlock::getTerminatingDeoptimizeCall</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableAdvancedPeeling {#a354acc6ff0fdfde87ae2eb07c6127620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableAdvancedPeeling("disable-advanced-peeling", cl::init(false), cl::Hidden, cl::desc( "Disable advance peeling. Issues for convergent targets (D134803)."))</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3aea1e78510aa7469457aade10808e51">llvm::canPeel</a>.</p>

</div>
</div>

### PeeledCountMetaData {#a7f5685c46cf812c90576046af45cd7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* PeeledCountMetaData = "llvm.loop.peeled.count"</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>.</p>

</div>
</div>

### UnrollAllowLoopNestsPeeling {#aa4d9cb6aeac6c6254d62eeb6c4b662ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollAllowLoopNestsPeeling("unroll-allow-loop-nests-peeling", cl::init(false), cl::Hidden, cl::desc("Allows loop nests to be peeled."))</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>.</p>

</div>
</div>

### UnrollAllowPeeling {#a626a61b9d8aa04db77aaff8e96059f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollAllowPeeling("unroll-allow-peeling", cl::init(true), cl::Hidden, cl::desc("Allows loops to be peeled when the dynamic " "trip count is known to be low."))</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>.</p>

</div>
</div>

### UnrollForcePeelCount {#a6383b9c934edc393f9e9f3fd992559aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollForcePeelCount("unroll-force-peel-count", cl::init(0), cl::Hidden, cl::desc("Force a peel count regardless of profiling information."))</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>.</p>

</div>
</div>

### UnrollPeelCount {#aa9badf8f59af8beee7f66a5252019f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollPeelCount("unroll-peel-count", cl::Hidden, cl::desc("Set the unroll peeling count, for testing purposes"))</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>.</p>

</div>
</div>

### UnrollPeelMaxCount {#a36a7dd364657e3ef9947efb9224aaca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollPeelMaxCount("unroll-peel-max-count", cl::init(7), cl::Hidden, cl::desc("Max average trip count which will cause loop peeling."))</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"loop-peel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp">LoopPeel.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
