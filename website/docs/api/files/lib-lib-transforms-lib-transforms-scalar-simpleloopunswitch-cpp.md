---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SimpleLoopUnswitch.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">llvm/Transforms/Scalar/SimpleLoopUnswitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sequence-h">llvm/ADT/Sequence.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfg-h">llvm/Analysis/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/guardutils-h">llvm/Analysis/GuardUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">llvm/Analysis/LoopIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">llvm/Analysis/MemorySSAUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">llvm/Support/GenericDomTree.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">llvm/Support/InstructionCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">llvm/Transforms/Utils/ValueMapper.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;iterator&gt;
#include &lt;numeric&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-simpleloopunswitch-cpp-">anonymous{SimpleLoopUnswitch.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/comparedesc">CompareDesc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/injectedinvariant">InjectedInvariant</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/nontrivialunswitchcandidate">NonTrivialUnswitchCandidate</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b466cbd242079ab18347e5248fd1b9">STATISTIC</a> (NumBranches, "Number of branches unswitched")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ab9463ab2f6721ceff43efa0ba37e5">STATISTIC</a> (NumSwitches, "Number of switches unswitched")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b42a29a9e74c94c6d7826358ff0cf51">STATISTIC</a> (NumSelects, "Number of selects turned into branches for unswitching")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825e9b46eaa40a5853a43f520d9b3a9d">STATISTIC</a> (NumGuards, "Number of guards turned into branches for unswitching")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e446decc15b9df1996f94f20798fbf">STATISTIC</a> (NumTrivial, "Number of unswitches that are trivial")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91923c5ac786f070c692a9ae19983ecb">STATISTIC</a> (NumCostMultiplierSkipped, "Number of unswitch candidates that had their cost multiplier skipped")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab781a25844101ae293fa4d6e9f27902f">STATISTIC</a> (NumInvariantConditionsInjected, "Number of invariant conditions injected and unswitched")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a> (Value *Cond)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector">TinyPtrVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a> (const Loop &amp;L, Instruction &amp;Root, const LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all of the loop invariant input values transitively used by the homogeneous instruction graph from a given root. <a href="#a1061b839196c8068b89d05aced41de29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669b909f685098d484bb789192620885">replaceLoopInvariantUses</a> (const Loop &amp;L, Value *Invariant, Constant &amp;Replacement)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ebfee3c290028ee7875184aac567ce">areLoopExitPHIsLoopInvariant</a> (const Loop &amp;L, const BasicBlock &amp;ExitingBB, const BasicBlock &amp;ExitBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that all the LCSSA PHI nodes in the loop exit block have trivial incoming values along this edge. <a href="#a98ebfee3c290028ee7875184aac567ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b06cc0aa3a6fcbace0aacf3b25a9e6">buildPartialUnswitchConditionalBranch</a> (BasicBlock &amp;BB, ArrayRef&lt; Value * &gt; Invariants, bool Direction, BasicBlock &amp;UnswitchedSucc, BasicBlock &amp;NormalSucc, bool InsertFreeze, const Instruction *I, AssumptionCache *AC, const DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a set of loop invariant values <span class="doxyComputerOutput">ToDuplicate</span> and insert them at the end of <span class="doxyComputerOutput">BB</span> and conditionally branch on the copied condition. <a href="#a45b06cc0aa3a6fcbace0aacf3b25a9e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a> (BasicBlock &amp;BB, ArrayRef&lt; Value * &gt; ToDuplicate, bool Direction, BasicBlock &amp;UnswitchedSucc, BasicBlock &amp;NormalSucc, Loop &amp;L, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a set of loop invariant values, and conditionally branch on them. <a href="#a0eaf12b7854445670a7b0af3fe87b86c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003a854484a7b23c151bc0b3d684e5d9">rewritePHINodesForUnswitchedExitBlock</a> (BasicBlock &amp;UnswitchedBB, BasicBlock &amp;OldExitingBB, BasicBlock &amp;OldPH)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the PHI nodes in an unswitched loop exit basic block. <a href="#a003a854484a7b23c151bc0b3d684e5d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a> (BasicBlock &amp;ExitBB, BasicBlock &amp;UnswitchedBB, BasicBlock &amp;OldExitingBB, BasicBlock &amp;OldPH, bool FullUnswitch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the PHI nodes in the loop exit basic block and the split off unswitched block. <a href="#a9a1db01205f9a51a14b99e53e3068da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a> (Loop &amp;L, BasicBlock &amp;Preheader, DominatorTree &amp;DT, LoopInfo &amp;LI, MemorySSAUpdater *MSSAU, ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hoist the current loop up to the innermost loop containing a remaining exit. <a href="#afa8d35023dc30883011a5641eac69d38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a> (const BasicBlock *ExitBB, const LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> (Loop &amp;L, BranchInst &amp;BI, DominatorTree &amp;DT, LoopInfo &amp;LI, ScalarEvolution *SE, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unswitch a trivial branch if the condition is loop invariant. <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a> (Loop &amp;L, SwitchInst &amp;SI, DominatorTree &amp;DT, LoopInfo &amp;LI, ScalarEvolution *SE, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unswitch a trivial switch if the condition is loop invariant. <a href="#aadf6036e1d19c8ba91242af6ec48d40b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a> (Loop &amp;L, DominatorTree &amp;DT, LoopInfo &amp;LI, ScalarEvolution *SE, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine scans the loop to find a branch or switch which occurs before any side effects occur. <a href="#a050cc2b2d1467ffcad6a825f1141424c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a> (Loop &amp;L, BasicBlock *LoopPH, BasicBlock *SplitBB, ArrayRef&lt; BasicBlock * &gt; ExitBlocks, BasicBlock *ParentBB, BasicBlock *UnswitchedSuccBB, BasicBlock *ContinueSuccBB, const SmallDenseMap&lt; BasicBlock *, BasicBlock *, 16 &gt; &amp;DominatingSucc, ValueToValueMapTy &amp;VMap, SmallVectorImpl&lt; DominatorTree::UpdateType &gt; &amp;DTUpdates, AssumptionCache &amp;AC, DominatorTree &amp;DT, LoopInfo &amp;LI, MemorySSAUpdater *MSSAU, ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the cloned blocks for an unswitched copy of the given loop. <a href="#aea49493e2ae224d30cda2b3235d180b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a> (Loop &amp;OrigRootL, Loop *RootParentL, const ValueToValueMapTy &amp;VMap, LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively clone the specified loop and all of its children. <a href="#af747cc9f106d837a03d08bd395ede216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a> (Loop &amp;OrigL, ArrayRef&lt; BasicBlock * &gt; ExitBlocks, const ValueToValueMapTy &amp;VMap, LoopInfo &amp;LI, SmallVectorImpl&lt; Loop * &gt; &amp;NonChildClonedLoops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the cloned loops of an original loop from unswitching. <a href="#afe5225e90ea8896cab9cda7246af413d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a> (Loop &amp;L, ArrayRef&lt; BasicBlock * &gt; ExitBlocks, ArrayRef&lt; std::unique_ptr&lt; ValueToValueMapTy &gt; &gt; VMaps, DominatorTree &amp;DT, MemorySSAUpdater *MSSAU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a> (Loop &amp;L, SmallVectorImpl&lt; BasicBlock * &gt; &amp;ExitBlocks, DominatorTree &amp;DT, LoopInfo &amp;LI, MemorySSAUpdater *MSSAU, ScalarEvolution *SE, LPMUpdater &amp;LoopUpdater)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9b0aa6fff67d00a95f47fc121491e5">recomputeLoopBlockSet</a> (Loop &amp;L, LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recompute the set of blocks in a loop after unswitching. <a href="#a0c9b0aa6fff67d00a95f47fc121491e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a> (Loop &amp;L, ArrayRef&lt; BasicBlock * &gt; ExitBlocks, LoopInfo &amp;LI, SmallVectorImpl&lt; Loop * &gt; &amp;HoistedLoops, ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rebuild a loop after unswitching removes some subset of blocks and edges. <a href="#ab79f3dcf9607c6a8908cda57cc964f49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18b0f192065386f9e0bc793a08bbf3ff">visitDomSubTree</a> (DominatorTree &amp;DT, BasicBlock *BB, CallableT Callable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to visit a dominator subtree, invoking a callable on each node. <a href="#a18b0f192065386f9e0bc793a08bbf3ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45007554e260296266b8ae927dde223f">postUnswitch</a> (Loop &amp;L, LPMUpdater &amp;U, StringRef LoopName, bool CurrentLoopValid, bool PartiallyInvariant, bool InjectedCondition, ArrayRef&lt; Loop * &gt; NewLoops)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> (Loop &amp;L, Instruction &amp;TI, ArrayRef&lt; Value * &gt; Invariants, IVConditionInfo &amp;PartialIVInfo, DominatorTree &amp;DT, LoopInfo &amp;LI, AssumptionCache &amp;AC, ScalarEvolution *SE, MemorySSAUpdater *MSSAU, LPMUpdater &amp;LoopUpdater, bool InsertFreeze, bool InjectedCondition)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a15f5bff768264b9e435e319db18f3">computeDomSubtreeCost</a> (DomTreeNode &amp;N, const SmallDenseMap&lt; BasicBlock *, InstructionCost, 4 &gt; &amp;BBCostMap, SmallDenseMap&lt; DomTreeNode *, InstructionCost, 4 &gt; &amp;DTCostMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively compute the cost of a dominator subtree based on the per-block cost map provided. <a href="#a78a15f5bff768264b9e435e319db18f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a> (SelectInst *SI, DominatorTree &amp;DT, LoopInfo &amp;LI, MemorySSAUpdater *MSSAU, AssumptionCache *AC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turns a select instruction into implicit control flow branch, making the following replacement: <a href="#a2e6301db15e4516c92e21f33761886c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a> (IntrinsicInst *GI, Loop &amp;L, DominatorTree &amp;DT, LoopInfo &amp;LI, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turns a llvm.experimental.guard intrinsic into implicit control flow branch, making the following replacement: <a href="#af3ac46dde637293a34d0ff7b619a656b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a> (const Instruction &amp;TI, const Loop &amp;L, const LoopInfo &amp;LI, const DominatorTree &amp;DT, ArrayRef&lt; NonTrivialUnswitchCandidate &gt; UnswitchCandidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> multiplier is a way to limit potentially exponential behavior of loop-unswitch. <a href="#a0e686f0d790f0fd925a036c4cb50199b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a> (SmallVectorImpl&lt; NonTrivialUnswitchCandidate &gt; &amp;UnswitchCandidates, IVConditionInfo &amp;PartialIVInfo, Instruction *&amp;PartialIVCondBranch, const Loop &amp;L, const LoopInfo &amp;LI, AAResults &amp;AA, const MemorySSAUpdater *MSSAU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bc2ff14a27583461b207499f426ee2">canonicalizeForInvariantConditionInjection</a> (CmpPredicate &amp;Pred, Value *&amp;LHS, Value *&amp;RHS, BasicBlock *&amp;IfTrue, BasicBlock *&amp;IfFalse, const Loop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to canonicalize condition described by: <a href="#a94bc2ff14a27583461b207499f426ee2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbb86574a065a122292322ed4e27b0e">shouldTryInjectInvariantCondition</a> (const ICmpInst::Predicate Pred, const Value *LHS, const Value *RHS, const BasicBlock *IfTrue, const BasicBlock *IfFalse, const Loop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true, if predicate described by ( <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">LHS</span>, <span class="doxyComputerOutput">RHS</span> ) succeeding into blocks ( <span class="doxyComputerOutput">IfTrue</span>, <span class="doxyComputerOutput">IfFalse</span>) can be optimized by injecting a loop-invariant condition. <a href="#a4cbb86574a065a122292322ed4e27b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08d593d99b84298decf28611dd32f50">shouldTryInjectBasingOnMetadata</a> (const BranchInst *BI, const BasicBlock *TakenSucc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true, if metadata on <span class="doxyComputerOutput">BI</span> allows us to optimize branching into <span class="doxyComputerOutput">TakenSucc</span> via injection of invariant conditions. <a href="#af08d593d99b84298decf28611dd32f50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static NonTrivialUnswitchCandidate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a> (NonTrivialUnswitchCandidate Candidate, Loop &amp;L, DominatorTree &amp;DT, LoopInfo &amp;LI, AssumptionCache &amp;AC, MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize pending invariant condition of the given candidate into IR. <a href="#aa8f270ce4d001ee9e7839aa11c607931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a> (SmallVectorImpl&lt; NonTrivialUnswitchCandidate &gt; &amp;UnswitchCandidates, Loop &amp;L, ICmpInst::Predicate Pred, ArrayRef&lt; CompareDesc &gt; Compares, const DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given chain of loop branch conditions looking like: br (Variant &lt; Invariant1) br (Variant &lt; Invariant2) br (Variant &lt; Invariant3) ... collect set of invariant conditions on which we want to unswitch, which look like: Invariant1 &lt;= Invariant2 Invariant2 &lt;= Invariant3 ... Though they might not immediately exist in the IR, we can still inject them. <a href="#a9ba70601e2398b462375dd8f3e9bc1b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a> (SmallVectorImpl&lt; NonTrivialUnswitchCandidate &gt; &amp;UnswitchCandidates, IVConditionInfo &amp;PartialIVInfo, Instruction *&amp;PartialIVCondBranch, Loop &amp;L, const DominatorTree &amp;DT, const LoopInfo &amp;LI, AAResults &amp;AA, const MemorySSAUpdater *MSSAU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect unswitch candidates by invariant conditions that are not immediately present in the loop. <a href="#a607c1e689b230ff38733bfc0bfd3b6da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41cbe08b01edbedddb8d8706d13c5270">isSafeForNoNTrivialUnswitching</a> (Loop &amp;L, LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static NonTrivialUnswitchCandidate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a> (ArrayRef&lt; NonTrivialUnswitchCandidate &gt; UnswitchCandidates, const Loop &amp;L, const DominatorTree &amp;DT, const LoopInfo &amp;LI, AssumptionCache &amp;AC, const TargetTransformInfo &amp;TTI, const IVConditionInfo &amp;PartialIVInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a> (Loop &amp;L, Instruction &amp;TI, DominatorTree &amp;DT, AssumptionCache &amp;AC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a> (Loop &amp;L, DominatorTree &amp;DT, LoopInfo &amp;LI, AssumptionCache &amp;AC, AAResults &amp;AA, TargetTransformInfo &amp;TTI, ScalarEvolution *SE, MemorySSAUpdater *MSSAU, LPMUpdater &amp;LoopUpdater)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a> (Loop &amp;L, DominatorTree &amp;DT, LoopInfo &amp;LI, AssumptionCache &amp;AC, AAResults &amp;AA, TargetTransformInfo &amp;TTI, bool Trivial, bool NonTrivial, ScalarEvolution *SE, MemorySSAUpdater *MSSAU, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, LPMUpdater &amp;LoopUpdater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unswitch control flow predicated on loop invariant conditions. <a href="#a00b3b7cedd83de61be0312c6535f3f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f48517d908cdf7a21eed936deb7f7c">EnableNonTrivialUnswitch</a>("enable-nontrivial-unswitch", cl::init(false), cl::Hidden, cl::desc("Forcibly enables non-trivial loop unswitching rather than " "following the configuration passed into the pass."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639210c26d1952e9108bcdbb0353443b">UnswitchThreshold</a>("unswitch-threshold", cl::init(50), cl::Hidden, cl::desc("The cost threshold for unswitching a loop."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58389dda20e5bd529f3fb18c6531c7ce">EnableUnswitchCostMultiplier</a>("enable-unswitch-cost-multiplier", cl::init(true), cl::Hidden, cl::desc("Enable unswitch cost multiplier that prohibits exponential " "explosion in nontrivial unswitch."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec915a44f00522e05af0372fe598372">UnswitchSiblingsToplevelDiv</a>("unswitch-siblings-toplevel-div", cl::init(2), cl::Hidden, cl::desc("Toplevel siblings divisor for cost multiplier."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49834115bcfb38ad510305e2e587f67a">UnswitchNumInitialUnscaledCandidates</a>("unswitch-num-initial-unscaled-candidates", cl::init(8), cl::Hidden, cl::desc("Number of unswitch candidates that are ignored when calculating " "cost multiplier."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0986070d3233b98011a6bd838a65f1cb">UnswitchGuards</a>("simple-loop-unswitch-guards", cl::init(true), cl::Hidden, cl::desc("If enabled, simple loop unswitching will also consider " "llvm.experimental.guard intrinsics as unswitch candidates."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab1355fa0b9b124a5424d170db011c9e">DropNonTrivialImplicitNullChecks</a>("simple-loop-unswitch-drop-non-trivial-implicit-null-checks", cl::init(false), cl::Hidden, cl::desc("If enabled, drop make.implicit metadata in unswitched implicit " "null checks to save time analyzing if we can keep it."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f97c549049a827518c9bce17a53833">MSSAThreshold</a>("simple-loop-unswitch-memoryssa-threshold", cl::desc("Max number of memory uses to explore during " "partial unswitching analysis"), cl::init(100), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a777551c6c08e4e3588b36665a8572414">FreezeLoopUnswitchCond</a>("freeze-loop-unswitch-cond", cl::init(true), cl::Hidden, cl::desc("If enabled, the freeze instruction will be added to condition " "of loop unswitch to prevent miscompilation."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a777260b6a90536fc8e2d844a891eddb5">InjectInvariantConditions</a>("simple-loop-unswitch-inject-invariant-conditions", cl::Hidden, cl::desc("Whether we should inject new invariants and unswitch them to " "eliminate some existing (non-invariant) conditions."), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5d88dba5221d4277024edf98cec9ac">InjectInvariantConditionHotnesThreshold</a>("simple-loop-unswitch-inject-invariant-condition-hotness-threshold", cl::Hidden, cl::desc("Only try to inject loop invariant conditions and " "unswitch on them to eliminate branches that are " "not-taken 1/<this option> times or less."), cl::init(16))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"simple-loop-unswitch"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>===- <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a> - Hoist loop-invariant control flow ------—===// <a href="#ad78e062f62e0d6e453941fb4ca843e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### areLoopExitPHIsLoopInvariant() {#a98ebfee3c290028ee7875184aac567ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areLoopExitPHIsLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; ExitingBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; ExitBB)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that all the LCSSA PHI nodes in the loop exit block have trivial incoming values along this edge.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### buildClonedLoopBlocks() {#aea49493e2ae224d30cda2b3235d180b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * buildClonedLoopBlocks (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopPH, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * SplitBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ParentBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * UnswitchedSuccBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ContinueSuccBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt; &amp; DominatingSucc, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; DominatorTree::UpdateType &gt; &amp; DTUpdates, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
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

<p>Build the cloned blocks for an unswitched copy of the given loop.</p>


<p>The cloned blocks are inserted before the loop preheader (<span class="doxyComputerOutput">LoopPH</span>) and after the split block (<span class="doxyComputerOutput">SplitBB</span>) that will be used to select between the cloned and original loop.</p>


<p>This routine handles cloning all of the necessary loop blocks and exit blocks including rewriting their instructions and the relevant PHI nodes. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> loop blocks or exit blocks which are dominated by a different successor than the one for this clone of the loop blocks can be trivially skipped. We use the <span class="doxyComputerOutput">DominatingSucc</span> map to determine whether a block satisfies that property with a simple map lookup.</p>


<p>It also correctly creates the unconditional branch in the cloned unswitched parent block to only point at the unswitched successor.</p>


<p>This does not handle most of the necessary updates to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span>. Only exit block splitting is correctly reflected in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span>, essentially all of the cloned blocks (and their loops) are left without full <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> updates. This also doesn't fully update <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a></span>. It adds the cloned blocks to them but doesn't create the cloned <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a></span> structure and instead the caller must recompute an accurate DT. It <em>does</em> correctly update the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a></span> provided in <span class="doxyComputerOutput">AC</span>.</p>


<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6dc58a1259941c7a17142e6103d059e">llvm::ScalarEvolution::forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac1fd6437bbfce263b87f01767d950ce5">llvm::BasicBlock::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a23187618f079555e127ba0e7b4581530">llvm::AssumptionCache::registerAssumption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3c6de822ccc920e435932d6cb73ac146">llvm::RemapDbgRecordRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">llvm::RemapInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da5633028bc27ffa8eab39cc5de65b3108">llvm::RF_IgnoreMissingLocals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da9a24bd8dba1bef2753bc3f087435ae7f">llvm::RF_NoModuleLevelChanges</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a740d35e0d3e2f7601f845b641fe58971">llvm::zip_first</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### buildClonedLoops() {#afe5225e90ea8896cab9cda7246af413d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildClonedLoops (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OrigL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; &amp; NonChildClonedLoops)</td>
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

<p>Build the cloned loops of an original loop from unswitching.</p>


<p>Because unswitching simplifies the CFG of the loop, this isn't a trivial operation. We need to re-verify that there even is a loop (as the backedge may not have been cloned), and even if there are remaining backedges the backedge set may be different. However, we know that each child loop is undisturbed, we only need to find where to place each child loop within either any parent loop or within a cloned version of the original loop.</p>


<p>Because child loops may end up cloned outside of any cloned version of the original loop, multiple cloned sibling loops may be created. All of them are returned so that the newly introduced loop nest roots can be identified.</p>


<p>Definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a63f099d3bf7cf97eb3ae2d630e3d1afc">llvm::LoopBase&lt; BlockT, LoopT &gt;::addBasicBlockToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a5a0ae49bf720341774a25029fd23bf59">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::AllocateLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a3b82484785487f544dc6ef1c2b6a0ffd">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a756142b56356b7a9083d52a88c7bd3af">llvm::LoopBase&lt; BlockT, LoopT &gt;::reserveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### buildPartialInvariantUnswitchConditionalBranch() {#a0eaf12b7854445670a7b0af3fe87b86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildPartialInvariantUnswitchConditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; ToDuplicate, bool Direction, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; UnswitchedSucc, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; NormalSucc, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Copy a set of loop invariant values, and conditionally branch on them.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5a7806c120eb87aea9fbb52fed327e09de">llvm::MemorySSA::BeforeTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ab23ba05c48e8be4a29c36d83deba9146">llvm::MemorySSAUpdater::createMemoryAccessInBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ab15de610fca1c900038bf3c333919e45">llvm::MemorySSA::getMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">llvm::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">llvm::RemapInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da5633028bc27ffa8eab39cc5de65b3108">llvm::RF_IgnoreMissingLocals</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da9a24bd8dba1bef2753bc3f087435ae7f">llvm::RF_NoModuleLevelChanges</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### buildPartialUnswitchConditionalBranch() {#a45b06cc0aa3a6fcbace0aacf3b25a9e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildPartialUnswitchConditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Invariants, bool Direction, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; UnswitchedSucc, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; NormalSucc, bool InsertFreeze, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>Copy a set of loop invariant values <span class="doxyComputerOutput">ToDuplicate</span> and insert them at the end of <span class="doxyComputerOutput">BB</span> and conditionally branch on the copied condition.</p>


<p>We only branch on a single value.</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a563ec77bbc82ad22aab9621dd14c01cd">llvm::IRBuilderBase::CreateFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### CalculateUnswitchCostMultiplier() {#a0e686f0d790f0fd925a036c4cb50199b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CalculateUnswitchCostMultiplier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; TI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; NonTrivialUnswitchCandidate &gt; UnswitchCandidates)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> multiplier is a way to limit potentially exponential behavior of loop-unswitch.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> is multipied in proportion of 2^number of unswitch candidates available. Also accounting for the number of "sibling" loops with the idea to account for previous unswitches that already happened on this cluster of loops. There was an attempt to keep this formula simple, just enough to limit the worst case behavior. Even if it is not that simple now it is still not an attempt to provide a detailed heuristic size prediction.</p>


<p>TODO: Make a proper accounting of "explosion" effect for all kinds of unswitch candidates, making adequate predictions instead of wild guesses. That requires knowing not just the number of "remaining" candidates but also costs of unswitching for each of these candidates.</p>


<p>Definition at line 2818 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ab447b41b9c51151b5c6ef497a60689ae">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a4f728602e7d377829675f13446cf6647">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656efdcee3deb029763304d3e741a2d1">llvm::isGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="#a49834115bcfb38ad510305e2e587f67a">UnswitchNumInitialUnscaledCandidates</a>, <a href="#a8ec915a44f00522e05af0372fe598372">UnswitchSiblingsToplevelDiv</a> and <a href="#a639210c26d1952e9108bcdbb0353443b">UnswitchThreshold</a>.</p>


<p>Referenced by <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### canonicalizeForInvariantConditionInjection() {#a94bc2ff14a27583461b207499f426ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void canonicalizeForInvariantConditionInjection (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> &amp; Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; IfTrue, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; IfFalse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
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

<p>Tries to canonicalize condition described by:</p>


<p>br (LHS pred RHS), label IfTrue, label IfFalse</p>


<p>into its equivalent where <span class="doxyComputerOutput">Pred</span> is something that we support for injected invariants (so far it is limited to ult), LHS in canonicalized form is non-invariant and RHS is an invariant.</p>


<p>Definition at line 2993 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>.</p>

</div>
</div>

### cloneLoopNest() {#af747cc9f106d837a03d08bd395ede216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * cloneLoopNest (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OrigRootL, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * RootParentL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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

<p>Recursively clone the specified loop and all of its children.</p>


<p>The target parent loop for the clone should be provided, or can be null if the clone is a top-level loop. While cloning, all the blocks are mapped with the provided value map. The entire original loop must be present in the value map. The cloned loop is returned.</p>


<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a5a0ae49bf720341774a25029fd23bf59">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::AllocateLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a97de9fb6fdce68e4e31300fcf0e5a20c">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::changeLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a261ee3c4745564c7be9283984c9af06b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getNumBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a16165c1e5da45acaa086c3a54a188d34">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInnermost</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>.</p>

</div>
</div>

### collectHomogenousInstGraphLoopInvariants() {#a1061b839196c8068b89d05aced41de29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TinyPtrVector&lt; Value * &gt; collectHomogenousInstGraphLoopInvariants (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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

<p>Collect all of the loop invariant input values transitively used by the homogeneous instruction graph from a given root.</p>


<p>This essentially walks from a root recursively through loop variant operands which have perform the same logical operation (AND or OR) and finds all inputs which are loop invariant. For some operations these can be re-associated and unswitched out of the loop entirely.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a1437e12220a4cd03b10656dcb607c642">llvm::TinyPtrVector&lt; EltTy &gt;::push_back</a> and <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>.</p>


<p>Referenced by <a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a> and <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### collectUnswitchCandidates() {#a7737deb6a166cd21dc8465bb48f110b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool collectUnswitchCandidates (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NonTrivialUnswitchCandidate &gt; &amp; UnswitchCandidates, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo">IVConditionInfo</a> &amp; PartialIVInfo, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; PartialIVCondBranch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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



<p>Definition at line 2897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a9dc659b723e6725130ad354ed821d400">llvm::TinyPtrVector&lt; EltTy &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f91ce019424451ab50bf348826fa270">llvm::findOptionMDForLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656efdcee3deb029763304d3e741a2d1">llvm::isGuard</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a93f97c549049a827518c9bce17a53833">MSSAThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a> and <a href="#a0986070d3233b98011a6bd838a65f1cb">UnswitchGuards</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### collectUnswitchCandidatesWithInjections() {#a607c1e689b230ff38733bfc0bfd3b6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool collectUnswitchCandidatesWithInjections (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NonTrivialUnswitchCandidate &gt; &amp; UnswitchCandidates, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo">IVConditionInfo</a> &amp; PartialIVInfo, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; PartialIVCondBranch, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Collect unswitch candidates by invariant conditions that are not immediately present in the loop.</p>


<p>However, they can be injected into the code if we decide it's profitable. An example of such conditions is following:</p>


<p>for (...) { x = load ... if (! x &lt;u C1) break; if (! x &lt;u C2) break; &lt;do something&gt; }</p>


<p>We can unswitch by condition "C1 &lt;=u C2". If that is true, then "x &lt;u C1 &lt;=
C2" automatically implies "x &lt;u C2", so we can get rid of one of loop-variant checks in unswitched loop version.</p>


<p>Definition at line 3219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a94bc2ff14a27583461b207499f426ee2">canonicalizeForInvariantConditionInjection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/comparedesc/#ade23e38371e46b268eb92542813f53bc">anonymous{SimpleLoopUnswitch.cpp}::CompareDesc::CompareDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a777260b6a90536fc8e2d844a891eddb5">InjectInvariantConditions</a>, <a href="#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad856c036ca10c903c93082a4e784d4a6">llvm::PatternMatch::m_BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a811d001fa503a556ac2a48d64366500f">llvm::PatternMatch::m_Br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#af08d593d99b84298decf28611dd32f50">shouldTryInjectBasingOnMetadata</a> and <a href="#a4cbb86574a065a122292322ed4e27b0e">shouldTryInjectInvariantCondition</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### computeDomSubtreeCost() {#a78a15f5bff768264b9e435e319db18f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost computeDomSubtreeCost (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> &amp; N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, 4 &gt; &amp; BBCostMap, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, 4 &gt; &amp; DTCostMap)</td>
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

<p>Recursively compute the cost of a dominator subtree based on the per-block cost map provided.</p>


<p>The recursive computation is memozied into the provided DT-indexed cost map to allow querying it for most nodes in the domtree without it becoming quadratic.</p>


<p>Definition at line 2660 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### deleteDeadBlocksFromLoop() {#aeabcdff1c388af9ac5a98f1ec4ba2471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void deleteDeadBlocksFromLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; ExitBlocks, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; LoopUpdater)</td>
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



<p>Definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ae98a33be737ade7a1f27130477b003f2">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::destroy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a917a64b00c1745fd0c78c2b2320cd4ad">llvm::Loop::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater/#ad898592a9fdc638d33b6b5cf0eba2bbe">llvm::LPMUpdater::markLoopAsDeleted</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa0c15073f16693ebc44c2410986cacec">llvm::MemorySSAUpdater::removeBlocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### deleteDeadClonedBlocks() {#a13971a178ec8248ecf4b0a903c4db1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void deleteDeadClonedBlocks (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &gt; &gt; VMaps, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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



<p>Definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa0c15073f16693ebc44c2410986cacec">llvm::MemorySSAUpdater::removeBlocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### findBestNonTrivialUnswitchCandidate() {#a52374e76082ee94158724e5695a88a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonTrivialUnswitchCandidate findBestNonTrivialUnswitchCandidate (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; NonTrivialUnswitchCandidate &gt; UnswitchCandidates, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo">IVConditionInfo</a> &amp; PartialIVInfo)</td>
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



<p>Definition at line 3317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="#a78a15f5bff768264b9e435e319db18f3">computeDomSubtreeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a58389dda20e5bd529f3fb18c6531c7ce">EnableUnswitchCostMultiplier</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656efdcee3deb029763304d3e741a2d1">llvm::isGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a586fb7954fcb7d759a997b3e1e979d30">llvm::Constant::isOneValue</a>, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo/#a8115811b4523cb1c13e1e32c5dc3bb3d">llvm::IVConditionInfo::KnownValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a639210c26d1952e9108bcdbb0353443b">UnswitchThreshold</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### getTopMostExitingLoop() {#a5e771bd40bbd3121ec36a96aa44ef46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * getTopMostExitingLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### hoistLoopToNewParent() {#afa8d35023dc30883011a5641eac69d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void hoistLoopToNewParent (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; Preheader, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
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

<p>Hoist the current loop up to the innermost loop containing a remaining exit.</p>


<p>Because we've removed an exit from the loop, we may have changed the set of loops reachable and need to move the current loop up the loop nest or even to an entirely separate nest.</p>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a97de9fb6fdce68e4e31300fcf0e5a20c">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::changeLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1f7831449cd72e78894e3dcda705cd8">llvm::formDedicatedExitBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae852af0cb2b1bee6f725a552cf7cfdea">llvm::formLCSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>.</p>


<p>Referenced by <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### injectPendingInvariantConditions() {#aa8f270ce4d001ee9e7839aa11c607931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonTrivialUnswitchCandidate injectPendingInvariantConditions (NonTrivialUnswitchCandidate Candidate, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Materialize pending invariant condition of the given candidate into IR.</p>


<p>The injected loop-invariant condition implies the original loop-variant branch condition, so the materialization turns</p>


<p>loop_block: ... br i1 variant_cond, label InLoopSucc, label OutOfLoopSucc</p>


<p>into</p>


<p>preheader: invariant_cond = LHS pred RHS ... loop_block: br i1 invariant_cond, label InLoopSucc, label OriginalCheck OriginalCheck: br i1 variant_cond, label InLoopSucc, label OutOfLoopSucc ...</p>


<p>Definition at line 3083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a470b5b573c7915fe13bd529b22c9adbc">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a62e2cf3675b93f0e6c07a4a00852f7cd">llvm::CmpInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/nontrivialunswitchcandidate/#a428fcbe432c0149594a5fe987bafd318">anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::NonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a17a8f7aba5cca5c7f9faa779a3c4bc37">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::verify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### insertCandidatesWithPendingInjections() {#a9ba70601e2398b462375dd8f3e9bc1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool insertCandidatesWithPendingInjections (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NonTrivialUnswitchCandidate &gt; &amp; UnswitchCandidates, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; CompareDesc &gt; Compares, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>Given chain of loop branch conditions looking like: br (Variant &lt; Invariant1) br (Variant &lt; Invariant2) br (Variant &lt; Invariant3) ... collect set of invariant conditions on which we want to unswitch, which look like: Invariant1 &lt;= Invariant2 Invariant2 &lt;= Invariant3 ... Though they might not immediately exist in the IR, we can still inject them.</p>

<p>Definition at line 3181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a6b13f2e75444202b854672a5fbf85e2e">llvm::CmpInst::getNonStrictPredicate</a>, <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/injectedinvariant/#a9851d6d92871b3a0d2fc4b4f5c205b97">anonymous{SimpleLoopUnswitch.cpp}::InjectedInvariant::InjectedInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#ae955171baab3d9254f3ffb089c082206">llvm::ICmpInst::isRelational</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a7d82fa77fd3d80b33e0beabb65ad8b93">llvm::CmpInst::isStrictPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/nontrivialunswitchcandidate/#a428fcbe432c0149594a5fe987bafd318">anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::NonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>.</p>

</div>
</div>

### isSafeForNoNTrivialUnswitching() {#a41cbe08b01edbedddb8d8706d13c5270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSafeForNoNTrivialUnswitching (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 3274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dadcd5de1248b4d9893c409e7398c21">llvm::containsIrreducibleCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/loopblocksrpo/#aeab06fd248333b13725e55754883b570">llvm::LoopBlocksRPO::perform</a>.</p>


<p>Referenced by <a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### postUnswitch() {#a45007554e260296266b8ae927dde223f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void postUnswitch (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LoopName, bool CurrentLoopValid, bool PartiallyInvariant, bool InjectedCondition, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; NewLoops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a>.</p>


<p>Referenced by <a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a> and <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### rebuildLoopAfterUnswitch() {#ab79f3dcf9607c6a8908cda57cc964f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool rebuildLoopAfterUnswitch (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; &amp; HoistedLoops, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
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

<p>Rebuild a loop after unswitching removes some subset of blocks and edges.</p>


<p>The removal may have removed some child loops entirely but cannot have disturbed any remaining child loops. However, they may need to be hoisted to the parent loop (or to be top-level loops). The original loop may be completely removed.</p>


<p>The sibling loops resulting from this update are returned. If the original loop remains a valid loop, it will be the first entry in this list with all of the newly sibling loops following it.</p>


<p>Returns true if the loop remains a loop after unswitching, and false if it is no longer a loop after unswitching (and should not continue to be referenced).</p>


<p>Definition at line 1906 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a97de9fb6fdce68e4e31300fcf0e5a20c">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::changeLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ae98a33be737ade7a1f27130477b003f2">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::destroy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#aa4defa64d17f14bd55204cac1b3a0c3a">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a0c9b0aa6fff67d00a95f47fc121491e5">recomputeLoopBlockSet</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a7bfb10fc99484961d5fac51621793aa6">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::removeLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### recomputeLoopBlockSet() {#a0c9b0aa6fff67d00a95f47fc121491e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt; const BasicBlock *, 16 &gt; recomputeLoopBlockSet (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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

<p>Recompute the set of blocks in a loop after unswitching.</p>


<p>This walks from the original headers predecessors to rebuild the loop. We take advantage of the fact that new blocks can't have been added, and so we filter by the original loop's blocks. This also handles potentially unreachable code that we don't want to explore but might be found examining the predecessors of the header.</p>


<p>If the original loop is no longer a loop, this will return an empty set. If it remains a loop, all the blocks within it will be added to the set (including those blocks in inner loops).</p>


<p>Definition at line 1795 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>.</p>

</div>
</div>

### replaceLoopInvariantUses() {#a669b909f685098d484bb789192620885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceLoopInvariantUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Invariant, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; Replacement)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### rewritePHINodesForExitAndUnswitchedBlocks() {#a9a1db01205f9a51a14b99e53e3068da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewritePHINodesForExitAndUnswitchedBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; ExitBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; UnswitchedBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; OldExitingBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; OldPH, bool FullUnswitch)</td>
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

<p>Rewrite the PHI nodes in the loop exit basic block and the split off unswitched block.</p>


<p>Because the exit block remains an exit from the loop, this rewrites the LCSSA PHI nodes in it to remove the unswitched edge and introduces PHI nodes into the unswitched basic block to select between the value in the old preheader and the loop exit.</p>


<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>.</p>


<p>Referenced by <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### rewritePHINodesForUnswitchedExitBlock() {#a003a854484a7b23c151bc0b3d684e5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewritePHINodesForUnswitchedExitBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; UnswitchedBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; OldExitingBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; OldPH)</td>
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

<p>Rewrite the PHI nodes in an unswitched loop exit basic block.</p>


<p>Requires that the loop exit and unswitched basic block are the same, and that the exiting block was a unique predecessor of that block. Rewrites the PHI nodes in that block such that what were LCSSA PHI nodes become trivial PHI nodes from the old preheader that now contains the unswitched terminator.</p>


<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### shouldInsertFreeze() {#a81f9271273f74a220003075573119a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldInsertFreeze (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; TI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC)</td>
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



<p>Definition at line 3474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#aca2badb4637a1c884bebc80828feac0a">llvm::ICFLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a777551c6c08e4e3588b36665a8572414">FreezeLoopUnswitchCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#ab40701961745d6467fa8e23b1e451c12">llvm::ICFLoopSafetyInfo::isGuaranteedToExecute</a> and <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### shouldTryInjectBasingOnMetadata() {#af08d593d99b84298decf28611dd32f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldTryInjectBasingOnMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * BI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TakenSucc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true, if metadata on <span class="doxyComputerOutput">BI</span> allows us to optimize branching into <span class="doxyComputerOutput">TakenSucc</span> via injection of invariant conditions.</p>


<p>The branch should be not enough and not previously unswitched, the information about this comes from the metadata.</p>


<p>Definition at line 3043 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="#aad5d88dba5221d4277024edf98cec9ac">InjectInvariantConditionHotnesThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>.</p>

</div>
</div>

### shouldTryInjectInvariantCondition() {#a4cbb86574a065a122292322ed4e27b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldTryInjectInvariantCondition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfTrue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfFalse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
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

<p>Returns true, if predicate described by ( <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">LHS</span>, <span class="doxyComputerOutput">RHS</span> ) succeeding into blocks ( <span class="doxyComputerOutput">IfTrue</span>, <span class="doxyComputerOutput">IfFalse</span>) can be optimized by injecting a loop-invariant condition.</p>

<p>Definition at line 3021 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>.</p>

</div>
</div>

### skipTrivialSelect() {#a5ca2e820d1b5a49dcaad5e6873917198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * skipTrivialSelect (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a>, <a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a>, <a href="#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>, <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### STATISTIC() {#ad5b466cbd242079ab18347e5248fd1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumBranches, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp/#a14311558a7445776def2d5bc13161ba3">branches</a> unswitched")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab3ab9463ab2f6721ceff43efa0ba37e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSwitches, "Number of switches unswitched")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a5b42a29a9e74c94c6d7826358ff0cf51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSelects, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#a3d495d9a0daf7fe32f1b1fb0aa153929">selects</a> turned into <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp/#a14311558a7445776def2d5bc13161ba3">branches</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> unswitching")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a825e9b46eaa40a5853a43f520d9b3a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumGuards, "Number of guards turned into <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp/#a14311558a7445776def2d5bc13161ba3">branches</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> unswitching")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa6e446decc15b9df1996f94f20798fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumTrivial, "Number of unswitches that are trivial")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a91923c5ac786f070c692a9ae19983ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCostMultiplierSkipped, "Number of unswitch candidates that had their cost multiplier skipped")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab781a25844101ae293fa4d6e9f27902f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumInvariantConditionsInjected, "Number of invariant conditions injected and unswitched")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

### turnGuardIntoBranch() {#af3ac46dde637293a34d0ff7b619a656b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * turnGuardIntoBranch (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * GI, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Turns a llvm.experimental.guard intrinsic into implicit control flow branch, making the following replacement:</p>


<p>–code before guard– call void (i1, ...) @llvm.experimental.guard(i1 cond) [ "deopt"() ] –code after guard–</p>


<p>into</p>


<p>–code before guard– br i1 cond, label guarded, label deopt</p>


<p>guarded: –code after guard–</p>


<p>deopt: call void (i1, ...) @llvm.experimental.guard(i1 false) [ "deopt"() ] unreachable</p>


<p>It also makes all relevant DT and LI updates, so that all structures are in valid state after this transform.</p>


<p>Definition at line 2762 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5a7806c120eb87aea9fbb52fed327e09de">llvm::MemorySSA::BeforeTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ab15de610fca1c900038bf3c333919e45">llvm::MemorySSA::getMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa7518e6d6d74227a56b36eb88cfe26e6">llvm::MemorySSAUpdater::moveAllAfterSpliceBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae26e0fb4a78dc439a03ac42c4ba6e674">llvm::MemorySSAUpdater::moveToPlace</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a6550fe5bd437c1c3c6e237d726e36b90">llvm::BranchInst::swapSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a17a8f7aba5cca5c7f9faa779a3c4bc37">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::verify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf0b85d705bf73d1af85056ef77b9c5">llvm::VerifyLoopInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### turnSelectIntoBranch() {#a2e6301db15e4516c92e21f33761886c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * turnSelectIntoBranch (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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

<p>Turns a select instruction into implicit control flow branch, making the following replacement:</p>


<p>head: –code before select– select cond, trueval, falseval –code after select–</p>


<p>into</p>


<p>head: –code before select– br i1 cond, label then, label tail</p>


<p>then: br tail</p>


<p>tail: phi [ trueval, then ], [ falseval, head] unreachable</p>


<p>It also makes all relevant DT and LI updates, so that all structures are in valid state after this transform.</p>


<p>Definition at line 2711 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa7518e6d6d74227a56b36eb88cfe26e6">llvm::MemorySSAUpdater::moveAllAfterSpliceBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### unswitchAllTrivialConditions() {#a050cc2b2d1467ffcad6a825f1141424c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unswitchAllTrivialConditions (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>This routine scans the loop to find a branch or switch which occurs before any side effects occur.</p>


<p>These can potentially be unswitched without duplicating the loop. If a branch or switch is successfully unswitched the scanning continues to see if subsequent branches or switches have become trivial. Once all trivial candidates have been unswitched, this routine returns.</p>


<p>The return value indicates whether anything was unswitched (and therefore changed).</p>


<p>If <span class="doxyComputerOutput">SE</span> is not null, it will be updated based on the potential loop SCEVs invalidated by this.</p>


<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ad586af665c013c65c83a31294555f996">llvm::MemorySSA::getBlockDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>, <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>


<p>Referenced by <a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### unswitchBestCondition() {#acc20b8effcbe869069ff973354344872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unswitchBestCondition (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; LoopUpdater)</td>
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



<p>Definition at line 3494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f91ce019424451ab50bf348826fa270">llvm::findOptionMDForLoop</a>, <a href="#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo/#a753ed4570ed0ac6d4f264c22b69a8add">llvm::IVConditionInfo::InstToDuplicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656efdcee3deb029763304d3e741a2d1">llvm::isGuard</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/nontrivialunswitchcandidate/#a428fcbe432c0149594a5fe987bafd318">anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::NonTrivialUnswitchCandidate</a>, <a href="#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>, <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="#a639210c26d1952e9108bcdbb0353443b">UnswitchThreshold</a>.</p>


<p>Referenced by <a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### unswitchLoop() {#a00b3b7cedd83de61be0312c6535f3f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unswitchLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, bool Trivial, bool NonTrivial, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; LoopUpdater)</td>
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

<p>Unswitch control flow predicated on loop invariant conditions.</p>


<p>This first hoists all branches or switches which are trivial (IE, do not require duplicating any part of the loop) out of the loop body. It then looks at other loop invariant control flows and tries to unswitch those as well by cloning the loop if the result is small enough.</p>


<p>The <span class="doxyComputerOutput">DT</span>, <span class="doxyComputerOutput">LI</span>, <span class="doxyComputerOutput">AC</span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a></span> parameters are required analyses that are also updated based on the unswitch. The <span class="doxyComputerOutput">MSSA</span> analysis is also updated if valid (i.e. its use is enabled).</p>


<p>If either <span class="doxyComputerOutput">NonTrivial</span> is true or the flag <span class="doxyComputerOutput">EnableNonTrivialUnswitch</span> is true, we will attempt to do non-trivial unswitching as well as trivial unswitching.</p>


<p>The <span class="doxyComputerOutput">postUnswitch</span> function will be run after unswitching is complete with information on whether or not the provided loop remains a loop and a list of new sibling loops created.</p>


<p>If <span class="doxyComputerOutput">SE</span> is non-null, we will update that analysis based on the unswitching done.</p>


<p>Definition at line 3587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a08f48517d908cdf7a21eed936deb7f7c">EnableNonTrivialUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a11d1c1af51bf81a6a9f8f5191b5e3cf2">llvm::ProfileSummaryInfo::hasProfileSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a597b25ab8d0a79f855c6c66dc48cb803">llvm::ProfileSummaryInfo::isColdBlock</a>, <a href="#a41cbe08b01edbedddb8d8706d13c5270">isSafeForNoNTrivialUnswitching</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#a45007554e260296266b8ae927dde223f">postUnswitch</a>, <a href="#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a> and <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### unswitchNontrivialInvariants() {#aae4261fb86bc9023c3383785afa66b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void unswitchNontrivialInvariants (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; TI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Invariants, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo">IVConditionInfo</a> &amp; PartialIVInfo, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; LoopUpdater, bool InsertFreeze, bool InjectedCondition)</td>
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



<p>Definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a470b5b573c7915fe13bd529b22c9adbc">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a50d461a887e200e704e5157d3b21514d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="#a45b06cc0aa3a6fcbace0aacf3b25a9e6">buildPartialUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aef781db858f88845051c0f2d7310ab07">llvm::SwitchInst::cases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#aca2badb4637a1c884bebc80828feac0a">llvm::ICFLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4576d69ed1543b06e5c41eb43b630bf1">llvm::Instruction::dropLocation</a>, <a href="#aab1355fa0b9b124a5424d170db011c9e">DropNonTrivialImplicitNullChecks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a592bdd7731b14ff4ff5d646f6f399900">llvm::ScalarEvolution::forgetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7d5bfa1ac3c7c096af6b26fb95cd699d">llvm::ScalarEvolution::forgetTopmostLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1f7831449cd72e78894e3dcda705cd8">llvm::formDedicatedExitBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae852af0cb2b1bee6f725a552cf7cfdea">llvm::formLCSSA</a>, <a href="#a777551c6c08e4e3588b36665a8572414">FreezeLoopUnswitchCond</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a0943fb5f399be0ac6ffbe8c977b619c8">llvm::SwitchInst::getDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">llvm::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo/#a753ed4570ed0ac6d4f264c22b69a8add">llvm::IVConditionInfo::InstToDuplicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/icfloopsafetyinfo/#ab40701961745d6467fa8e23b1e451c12">llvm::ICFLoopSafetyInfo::isGuaranteedToExecute</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a586fb7954fcb7d759a997b3e1e979d30">llvm::Constant::isOneValue</a>, <a href="/web-llvm/docs/api/structs/llvm/ivconditioninfo/#a8115811b4523cb1c13e1e32c5dc3bb3d">llvm::IVConditionInfo::KnownValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksrpo/#aeab06fd248333b13725e55754883b570">llvm::LoopBlocksRPO::perform</a>, <a href="#a45007554e260296266b8ae927dde223f">postUnswitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a95eeaea882b3c388420da771fe488bbc">llvm::MemorySSAUpdater::removeDuplicatePhiEdgesBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a4953231268ee21e95c3740e51ab37a96">llvm::MemorySSAUpdater::removeEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afe7af0c3ec2ef1f525173acd2ea4ba60">llvm::BasicBlock::removePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a3505dab06f59c36142a234321cdc3411">llvm::BranchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#adc5e7f9c460c68455e826783d77f9a99">llvm::BranchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aeb3964d6e7884c21d8118699062c91df">llvm::MemorySSAUpdater::updateExitBlocksForClonedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a667d41d0d3b12af17ccc6c99e3d51e5b">llvm::MemorySSAUpdater::updateForClonedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a17a8f7aba5cca5c7f9faa779a3c4bc37">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::verify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a> and <a href="#a18b0f192065386f9e0bc793a08bbf3ff">visitDomSubTree</a>.</p>


<p>Referenced by <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

### unswitchTrivialBranch() {#a6a082aa2e05f44f7dab89e2ff8c582ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unswitchTrivialBranch (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; BI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Unswitch a trivial branch if the condition is loop invariant.</p>


<p>This routine should only be called when loop code leading to the branch has been validated as trivial (no side effects). This routine checks if the condition is invariant and one of the successors is a loop exit. This allows us to unswitch without duplicating the loop, making it trivial.</p>


<p>If this routine fails to unswitch the branch it returns false.</p>


<p>If the branch can be unswitched, this routine splits the preheader and hoists the branch above that split. Preserves loop simplified form (splitting the exit block as necessary). It simplifies the branch within the loop to an unconditional branch but doesn't remove it entirely. Further cleanup can be done with some simplifycfg like pass.</p>


<p>If <span class="doxyComputerOutput">SE</span> is not null, it will be updated based on the potential loop SCEVs invalidated by this.</p>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ac0404328e9e4f5d3c565daabf46fffac">llvm::MemorySSAUpdater::applyInsertUpdates</a>, <a href="#a98ebfee3c290028ee7875184aac567ce">areLoopExitPHIsLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a45b06cc0aa3a6fcbace0aacf3b25a9e6">buildPartialUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ab0f09aefdf088f84a0bff7cba86454b4">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::deleteEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a9dc659b723e6725130ad354ed821d400">llvm::TinyPtrVector&lt; EltTy &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a592bdd7731b14ff4ff5d646f6f399900">llvm::ScalarEvolution::forgetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7d5bfa1ac3c7c096af6b26fb95cd699d">llvm::ScalarEvolution::forgetTopmostLoop</a>, <a href="#a777551c6c08e4e3588b36665a8572414">FreezeLoopUnswitchCond</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cfg/#a90f12723ad8d5cff45b6f06408a33da8aa458be0f08b7e4ff3c0f633c100176c0">llvm::cfg::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a51145a3ae24ea73b3692a17088edea7b">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::insertEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">llvm::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2276d81e0e6e31d0a69c4352a066ef73">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad4d070a596ae37b8e01f15e4f759fc07">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a1437e12220a4cd03b10656dcb607c642">llvm::TinyPtrVector&lt; EltTy &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a4953231268ee21e95c3740e51ab37a96">llvm::MemorySSAUpdater::removeEdge</a>, <a href="#a669b909f685098d484bb789192620885">replaceLoopInvariantUses</a>, <a href="#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a>, <a href="#a003a854484a7b23c151bc0b3d684e5d9">rewritePHINodesForUnswitchedExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a3505dab06f59c36142a234321cdc3411">llvm::BranchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#adc5e7f9c460c68455e826783d77f9a99">llvm::BranchInst::setSuccessor</a>, <a href="#a5ca2e820d1b5a49dcaad5e6873917198">skipTrivialSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>.</p>

</div>
</div>

### unswitchTrivialSwitch() {#aadf6036e1d19c8ba91242af6ec48d40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unswitchTrivialSwitch (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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

<p>Unswitch a trivial switch if the condition is loop invariant.</p>


<p>This routine should only be called when loop code leading to the switch has been validated as trivial (no side effects). This routine checks if the condition is invariant and that at least one of the successors is a loop exit. This allows us to unswitch without duplicating the loop, making it trivial.</p>


<p>If this routine fails to unswitch the switch it returns false.</p>


<p>If the switch can be unswitched, this routine splits the preheader and copies the switch above that split. If the default case is one of the exiting cases, it copies the non-exiting cases and points them at the new preheader. If the default case is not exiting, it copies the exiting cases and points the default at the preheader. It preserves loop simplified form (splitting the exit blocks as necessary). It simplifies the switch within the loop by removing now-dead cases. If the default case is one of those unswitched, it replaces its destination with a new basic block containing only unreachable. Such basic blocks, while technically loop exits, are not considered for unswitching so this is a stable transform and the same switch will not be revisited. If after unswitching there is only a single in-loop successor, the switch is further simplified to an unconditional branch. Still more cleanup can be done with some simplifycfg like pass.</p>


<p>If <span class="doxyComputerOutput">SE</span> is not null, it will be updated based on the potential loop SCEVs invalidated by this.</p>


<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#a722eca444a919e1bc6af18b07941aad9">llvm::SwitchInstProfUpdateWrapper::addCase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a470b5b573c7915fe13bd529b22c9adbc">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="#a98ebfee3c290028ee7875184aac567ce">areLoopExitPHIsLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a3c1416226bed5e92acb74aebe8e20f5a">llvm::SwitchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Delete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#a241eb312f38b46a95df18ba8a6250636">llvm::SwitchInstProfUpdateWrapper::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a592bdd7731b14ff4ff5d646f6f399900">llvm::ScalarEvolution::forgetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7d5bfa1ac3c7c096af6b26fb95cd699d">llvm::ScalarEvolution::forgetTopmostLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#aa832438a6843b75f7d0ef2cc563153f6">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInstT, ConstantIntT, BasicBlockT &gt;::getCaseSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#ad2b4cf1b26b0b142b243bcdcf300eafa">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInstT, ConstantIntT, BasicBlockT &gt;::getCaseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a80c8a3151e9ef04b1595e222bdfe1cf9">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInstT, ConstantIntT, BasicBlockT &gt;::getSuccessorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#aa78ac7cc796c2905e31c1ef6de35087d">llvm::SwitchInstProfUpdateWrapper::getSuccessorWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a5e771bd40bbd3121ec36a96aa44ef46a">getTopMostExitingLoop</a>, <a href="#afa8d35023dc30883011a5641eac69d38">hoistLoopToNewParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad66c4759666aab78529658362b498c74">llvm::pred_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#adf90515665080eadf537aff00bbf0594">llvm::SwitchInstProfUpdateWrapper::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afe7af0c3ec2ef1f525173acd2ea4ba60">llvm::BasicBlock::removePredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a>, <a href="#a003a854484a7b23c151bc0b3d684e5d9">rewritePHINodesForUnswitchedExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aa22bdae1cee3c836f2b4cf8307fc7598">llvm::SwitchInst::setDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#a1a01b0843bc5ed009f7fdb2c8b8a41a5">llvm::SwitchInstProfUpdateWrapper::setSuccessorWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab9f68be0e2bcdf14f503f45edea63023">llvm::BasicBlock::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>.</p>

</div>
</div>

### visitDomSubTree() {#a18b0f192065386f9e0bc793a08bbf3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void visitDomSubTree (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, CallableT Callable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to visit a dominator subtree, invoking a callable on each node.</p>


<p>Returning false at any point will stop walking past that node of the tree.</p>


<p>Definition at line 2115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DropNonTrivialImplicitNullChecks {#aab1355fa0b9b124a5424d170db011c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DropNonTrivialImplicitNullChecks("simple-loop-unswitch-drop-non-trivial-implicit-null-checks", cl::init(false), cl::Hidden, cl::desc("If enabled, drop make.implicit metadata in unswitched implicit " "null checks to save time analyzing if we can keep it."))</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### EnableNonTrivialUnswitch {#a08f48517d908cdf7a21eed936deb7f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableNonTrivialUnswitch("enable-nontrivial-unswitch", cl::init(false), cl::Hidden, cl::desc("Forcibly enables non-trivial loop unswitching rather than " "following the configuration passed into the pass."))</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### EnableUnswitchCostMultiplier {#a58389dda20e5bd529f3fb18c6531c7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableUnswitchCostMultiplier("enable-unswitch-cost-multiplier", cl::init(true), cl::Hidden, cl::desc("Enable unswitch cost multiplier that prohibits exponential " "explosion in nontrivial unswitch."))</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### FreezeLoopUnswitchCond {#a777551c6c08e4e3588b36665a8572414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; FreezeLoopUnswitchCond("freeze-loop-unswitch-cond", cl::init(true), cl::Hidden, cl::desc("If enabled, the freeze instruction will be added to condition " "of loop unswitch to prevent miscompilation."))</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a>, <a href="#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### InjectInvariantConditionHotnesThreshold {#aad5d88dba5221d4277024edf98cec9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; InjectInvariantConditionHotnesThreshold("simple-loop-unswitch-inject-invariant-condition-hotness-threshold", cl::Hidden, cl::desc("Only try to inject loop invariant conditions and " "unswitch on them to eliminate branches that are " "not-taken 1/&lt;this option&gt; times or less."), cl::init(16))</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#af08d593d99b84298decf28611dd32f50">shouldTryInjectBasingOnMetadata</a>.</p>

</div>
</div>

### InjectInvariantConditions {#a777260b6a90536fc8e2d844a891eddb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; InjectInvariantConditions("simple-loop-unswitch-inject-invariant-conditions", cl::Hidden, cl::desc("Whether we should inject new invariants and unswitch them to " "eliminate some existing (non-invariant) conditions."), cl::init(true))</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>.</p>

</div>
</div>

### MSSAThreshold {#a93f97c549049a827518c9bce17a53833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MSSAThreshold("simple-loop-unswitch-memoryssa-threshold", cl::desc("Max number of memory uses to explore during " "partial unswitching analysis"), cl::init(100), cl::Hidden)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>.</p>

</div>
</div>

### UnswitchGuards {#a0986070d3233b98011a6bd838a65f1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnswitchGuards("simple-loop-unswitch-guards", cl::init(true), cl::Hidden, cl::desc("If enabled, simple loop unswitching will also consider " "llvm.experimental.guard intrinsics as unswitch candidates."))</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>.</p>

</div>
</div>

### UnswitchNumInitialUnscaledCandidates {#a49834115bcfb38ad510305e2e587f67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; UnswitchNumInitialUnscaledCandidates("unswitch-num-initial-unscaled-candidates", cl::init(8), cl::Hidden, cl::desc("Number of unswitch candidates that are ignored when calculating " "cost multiplier."))</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>.</p>

</div>
</div>

### UnswitchSiblingsToplevelDiv {#a8ec915a44f00522e05af0372fe598372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; UnswitchSiblingsToplevelDiv("unswitch-siblings-toplevel-div", cl::init(2), cl::Hidden, cl::desc("Toplevel siblings divisor for cost multiplier."))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>.</p>

</div>
</div>

### UnswitchThreshold {#a639210c26d1952e9108bcdbb0353443b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; UnswitchThreshold("unswitch-threshold", cl::init(50), cl::Hidden, cl::desc("The cost threshold for unswitching a loop."))</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>, <a href="#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a> and <a href="#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"simple-loop-unswitch"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>===- <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a> - Hoist loop-invariant control flow ------—===//</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
