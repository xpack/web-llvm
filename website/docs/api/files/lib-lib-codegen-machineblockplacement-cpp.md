---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machineblockplacement-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachineBlockPlacement.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-h">BranchFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/mbfiwrapper-h">llvm/CodeGen/MBFIWrapper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">llvm/CodeGen/MachinePostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinesizeopts-h">llvm/CodeGen/MachineSizeOpts.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">llvm/CodeGen/TailDuplicator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/printpasses-h">llvm/IR/PrintPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">llvm/Support/BlockFrequency.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">llvm/Transforms/Utils/CodeLayout.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machineblockplacement-cpp-">anonymous{MachineBlockPlacement.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A chain of blocks which will be laid out contiguously. <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement">MachineBlockPlacement</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineblockplacement-cpp-/machineblockplacement/blockandtaildupresult">BlockAndTailDupResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pair struct containing basic block and taildup profitability. <a href="/web-llvm/docs/api/structs/anonymous-machineblockplacement-cpp-/machineblockplacement/blockandtaildupresult/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineblockplacement-cpp-/machineblockplacement/weightededge">WeightedEdge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> struct containing edge weight and the edge. <a href="/web-llvm/docs/api/structs/anonymous-machineblockplacement-cpp-/machineblockplacement/weightededge/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats">MachineBlockPlacementStats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass to compute block placement statistics. <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05af0aa86e2b12cf42ab78461b937cd">STATISTIC</a> (NumCondBranches, "Number of conditional branches")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b86f72bc30eb2255f4c0a22ffab9d3d">STATISTIC</a> (NumUncondBranches, "Number of unconditional branches")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d61a27d105b8e831a92e20acdeca10">STATISTIC</a> (CondBranchTakenFreq, "Potential frequency of taking conditional branches")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eeb8d383eae14ff1d8952fe471fb841">STATISTIC</a> (UncondBranchTakenFreq, "Potential frequency of taking unconditional branches")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d0eea634133a91f99ee833a4d073ef">INITIALIZE_PASS_BEGIN</a> (MachineBlockPlacement, DEBUG_TYPE, "Branch Probability Basic Block Placement", false, false) INITIALIZE_PASS_END(MachineBlockPlacement</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Branch Probability Basic Block static false <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9ee7f9ffc036496a8663335da175fa">getBlockName</a> (const MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to print the name of a MBB. <a href="#a8f9ee7f9ffc036496a8663335da175fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a894de03271c0ccc991e40f4cdd2623">getAdjustedProbability</a> (BranchProbability OrigProb, BranchProbability AdjustedSumProb)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The helper function returns the branch probability that is adjusted or normalized over the new total <span class="doxyComputerOutput">AdjustedSumProb</span>. <a href="#a0a894de03271c0ccc991e40f4cdd2623">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20068697df3d13ab12e09852d99b7f7">hasSameSuccessors</a> (MachineBasicBlock &amp;BB, SmallPtrSetImpl&lt; const MachineBasicBlock * &gt; &amp;Successors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">BB</span> has exactly the successors in <span class="doxyComputerOutput">Successors</span>. <a href="#ab20068697df3d13ab12e09852d99b7f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73743365177645c3db889f210cd5ad1d">greaterWithBias</a> (BlockFrequency A, BlockFrequency B, BlockFrequency EntryFreq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare 2 <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a>'s with a small penalty for <span class="doxyComputerOutput">A</span>. <a href="#a73743365177645c3db889f210cd5ad1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a> (const MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac20133598c564acc81e5abadc5a1d637">countMBBInstruction</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace73c7d6fee046409626ebb1799d0454">INITIALIZE_PASS_BEGIN</a> (MachineBlockPlacementStats, "block-placement-stats", "Basic Block Placement Stats", false, false) INITIALIZE_PASS_END(MachineBlockPlacementStats</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1e40c7ec4c37b42f76da67c75e638d">AlignAllBlock</a>("align-all-blocks", cl::desc("Force the alignment of all blocks in the function in log2 format " "(e.g 4 means align on 16B boundaries)."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbf76303569b68b0d3719627c88e9fe">AlignAllNonFallThruBlocks</a>("align-all-nofallthru-blocks", cl::desc("Force the alignment of all blocks that have no fall-through " "predecessors (i.e. don't add nops that are executed). In log2 " "format (e.g 4 means align on 16B boundaries)."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7713277c884a7bf39711c1c0d6cf9c26">MaxBytesForAlignmentOverride</a>("max-bytes-for-alignment", cl::desc("Forces the maximum bytes allowed to be emitted when padding for " "alignment"), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41cd121b4df30e5c0dc17f0c479e843a">ExitBlockBias</a>("block-placement-exit-block-bias", cl::desc("Block frequency percentage a loop exit block needs " "over the original exit to be considered the new exit."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba0c508ce2e626b58485ceb28068cf1">LoopToColdBlockRatio</a>("loop-to-cold-block-ratio", cl::desc("Outline loop blocks from loop chain if (frequency of loop) / " "(frequency of block) is greater than this ratio"), cl::init(5), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ede40cd3f6f158cb8cbbc9de3844d98">ForceLoopColdBlock</a>("force-loop-cold-block", cl::desc("Force outlining cold blocks from loops."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d30337c58d278817264718434f122ca">PreciseRotationCost</a>("precise-rotation-cost", cl::desc("Model the cost of loop rotation more " "precisely by using profile data."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71e7939345cee7ef0596b40d1ad068b">ForcePreciseRotationCost</a>("force-precise-rotation-cost", cl::desc("Force the use of precise cost " "loop rotation strategy."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fe07dfba15c73225c8ca4cd720049d">MisfetchCost</a>("misfetch-cost", cl::desc("Cost that models the probabilistic risk of an instruction " "misfetch due to a jump comparing to falling through, whose cost " "is zero."), cl::init(1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b387cbb4c16dbf0558135dd26ddfd0">JumpInstCost</a>("jump-inst-cost", cl::desc("Cost of jump instructions."), cl::init(1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf71e6f582691ae8bdf8ed170fb11ae6">TailDupPlacement</a>("tail-dup-placement", cl::desc("Perform tail duplication during placement. " "Creates more fallthrough opportunities in " "outline branches."), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ae0b35deb4cbcffc27c3d52a781fca">BranchFoldPlacement</a>("branch-fold-placement", cl::desc("Perform branch folding during placement. " "Reduces code size."), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707021480bba6c165b873f9e238859c5">TailDupPlacementThreshold</a>("tail-dup-placement-threshold", cl::desc("Instruction cutoff for tail duplication during layout. " "Tail merging during layout is forced to have a threshold " "that won't conflict."), cl::init(2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8acb8291add6a055468711f701e78d">TailDupPlacementAggressiveThreshold</a>("tail-dup-placement-aggressive-threshold", cl::desc("Instruction cutoff for aggressive tail duplication during " "layout. Used at -O3. Tail merging during layout is forced to " "have a threshold that won't conflict."), cl::init(4), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7344284dac6ba9b8e48d9be67c954bfc">TailDupPlacementPenalty</a>("tail-dup-placement-penalty", cl::desc("Cost penalty for blocks that can avoid breaking CFG by copying. " "Copying can increase fallthrough, but it also increases icache " "pressure. This parameter controls the penalty to account for that. " "Percent as integer."), cl::init(2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84dfb254ed1062bc06a43d2365974bd2">TailDupProfilePercentThreshold</a>("tail-dup-profile-percent-threshold", cl::desc("If profile count information is used in tail duplication cost " "model, the gained fall through number from tail duplication " "should be at least this percent of hot count."), cl::init(50), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac66559c601e390e9477131019ee0ca">TriangleChainCount</a>("triangle-chain-count", cl::desc("Number of triangle-shaped-CFG's that need to be in a row for the " "triangle tail duplication heuristic to kick in. 0 to disable."), cl::init(2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1fed248fc2af534bd094b35c9f0c64b">RenumberBlocksBeforeView</a>("renumber-blocks-before-view", cl::desc("If true, basic blocks are re-numbered before MBP layout is printed " "into a dot graph. Only used when a function is being printed."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1160412b923427430e8bf4c819d79a93">ExtTspBlockPlacementMaxBlocks</a>("ext-tsp-block-placement-max-blocks", cl::desc("Maximum number of basic blocks in a function to run ext-TSP " "block placement."), cl::init(UINT_MAX), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956f6faccd85fe2a75302e0ac3ecc606">ApplyExtTspForSize</a>("apply-ext-tsp-for-size", cl::init(false), cl::Hidden, cl::desc("Use ext-tsp for size-aware block placement."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Branch Probability Basic Block</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10783a549bfb83fd142ae4e645a283ef">Placement</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Branch Probability Basic Block</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b3a35dc5c2cb6840ae523bc8d1902a">false</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> placement</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971b2fc3751cade0a6b2f76c92774317">stats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> placement Basic Block <a href="#a10783a549bfb83fd142ae4e645a283ef">Placement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086f939e29b718dc5a01e4bcfe6af2a1">Stats</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"block-placement"</td>
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

### countMBBInstruction() {#ac20133598c564acc81e5abadc5a1d637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t countMBBInstruction (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 3272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getAdjustedProbability() {#a0a894de03271c0ccc991e40f4cdd2623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability getAdjustedProbability (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> OrigProb, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> AdjustedSumProb)</td>
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

<p>The helper function returns the branch probability that is adjusted or normalized over the new total <span class="doxyComputerOutput">AdjustedSumProb</span>.</p>

<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a7be5759bf75c903d1695fa97eca6f139">llvm::BranchProbability::getNumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a56e1b2d1999aadf4c513caee1ce5275b">llvm::BranchProbability::getOne</a>.</p>

</div>
</div>

### getBlockName() {#a8f9ee7f9ffc036496a8663335da175fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Branch Probability Basic Block static false std::string getBlockName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Helper to print the name of a MBB.</p>


<p>Only used by debug logging.</p>


<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aedf6cb1135961f41f39dc58ca8576123">llvm::MachineBasicBlock::getName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

### getLayoutSuccessorProbThreshold() {#a3d135a8abf70dc93455708cc087cc0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability getLayoutSuccessorProbThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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



<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9084ce2576fad285c1c0dc1e165dd4b6">llvm::Function::hasProfileData</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4de1c8a569d0350e16d8c5e0746d5bbf">llvm::ProfileLikelyProb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75dea20875e2199efbf65662db1234d8">llvm::StaticLikelyProb</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>

</div>
</div>

### greaterWithBias() {#a73743365177645c3db889f210cd5ad1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool greaterWithBias (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> A, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> B, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> EntryFreq)</td>
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

<p>Compare 2 <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a>'s with a small penalty for <span class="doxyComputerOutput">A</span>.</p>


<p>In order to be conservative, we apply a X% penalty to account for increased icache pressure and static heuristics. For small frequencies we use only the numerators to improve accuracy. For simplicity, we assume the penalty is less than 100% TODO(iteratee): <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> 64-bit fixed point edge frequencies everywhere.</p>


<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a7344284dac6ba9b8e48d9be67c954bfc">TailDupPlacementPenalty</a>.</p>

</div>
</div>

### hasSameSuccessors() {#ab20068697df3d13ab12e09852d99b7f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSameSuccessors (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Successors)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">BB</span> has exactly the successors in <span class="doxyComputerOutput">Successors</span>.</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#aa4d0eea634133a91f99ee833a4d073ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (MachineBlockPlacement, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Branch Probability Basic Block Placement", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ace73c7d6fee046409626ebb1799d0454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (MachineBlockPlacementStats, "block-placement-stats", "Basic Block <a href="#a10783a549bfb83fd142ae4e645a283ef">Placement</a> Stats", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3809 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### STATISTIC() {#ad05af0aa86e2b12cf42ab78461b937cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCondBranches, "Number of conditional branches")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a0b86f72bc30eb2255f4c0a22ffab9d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumUncondBranches, "Number of unconditional branches")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ad2d61a27d105b8e831a92e20acdeca10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (CondBranchTakenFreq, "Potential frequency of taking conditional branches")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a6eeb8d383eae14ff1d8952fe471fb841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (UncondBranchTakenFreq, "Potential frequency of taking unconditional branches")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AlignAllBlock {#a1f1e40c7ec4c37b42f76da67c75e638d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; AlignAllBlock("align-all-blocks", cl::desc("Force the alignment of all blocks in the function in log2 format " "(e.g 4 means align on 16B boundaries)."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### AlignAllNonFallThruBlocks {#a4dbf76303569b68b0d3719627c88e9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; AlignAllNonFallThruBlocks("align-all-nofallthru-blocks", cl::desc("Force the alignment of all blocks that have no fall-through " "predecessors (i.e. don't add nops that are executed). In log2 " "format (e.g 4 means align on 16B boundaries)."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ApplyExtTspForSize {#a956f6faccd85fe2a75302e0ac3ecc606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ApplyExtTspForSize("apply-ext-tsp-for-size", cl::init(false), cl::Hidden, cl::desc("Use ext-tsp for size-aware block placement."))</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

### BranchFoldPlacement {#a84ae0b35deb4cbcffc27c3d52a781fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; BranchFoldPlacement("branch-fold-placement", cl::desc("Perform branch folding during placement. " "Reduces code size."), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ExitBlockBias {#a41cd121b4df30e5c0dc17f0c479e843a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ExitBlockBias("block-placement-exit-block-bias", cl::desc("Block frequency percentage a loop exit block needs " "over the original exit to be considered the new exit."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ExtTspBlockPlacementMaxBlocks {#a1160412b923427430e8bf4c819d79a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ExtTspBlockPlacementMaxBlocks("ext-tsp-block-placement-max-blocks", cl::desc("Maximum number of basic blocks in a function to run ext-TSP " "block placement."), cl::init(UINT_MAX), cl::Hidden)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

### false {#a80b3a35dc5c2cb6840ae523bc8d1902a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block placement Basic Block Placement false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ForceLoopColdBlock {#a3ede40cd3f6f158cb8cbbc9de3844d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceLoopColdBlock("force-loop-cold-block", cl::desc("Force outlining cold blocks from loops."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ForcePreciseRotationCost {#ae71e7939345cee7ef0596b40d1ad068b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForcePreciseRotationCost("force-precise-rotation-cost", cl::desc("Force the use of precise cost " "loop rotation strategy."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### JumpInstCost {#a72b387cbb4c16dbf0558135dd26ddfd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; JumpInstCost("jump-inst-cost", cl::desc("Cost of jump instructions."), cl::init(1), cl::Hidden)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### LoopToColdBlockRatio {#acba0c508ce2e626b58485ceb28068cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; LoopToColdBlockRatio("loop-to-cold-block-ratio", cl::desc("Outline loop blocks from loop chain if (frequency of loop) / " "(frequency of block) is greater than this ratio"), cl::init(5), cl::Hidden)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MaxBytesForAlignmentOverride {#a7713277c884a7bf39711c1c0d6cf9c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxBytesForAlignmentOverride("max-bytes-for-alignment", cl::desc("Forces the maximum bytes allowed to be emitted when padding for " "alignment"), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MisfetchCost {#a75fe07dfba15c73225c8ca4cd720049d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MisfetchCost("misfetch-cost", cl::desc("Cost that models the probabilistic risk of an instruction " "misfetch due to a jump comparing to falling through, whose cost " "is zero."), cl::init(1), cl::Hidden)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### Placement {#a10783a549bfb83fd142ae4e645a283ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Branch Probability Basic Block Placement</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#aa791c4b3d0582a90ae8059dfa4598a9c">getFinalPlacementForEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a99ca361384a0bc6e5fe805b3050ced95">llvm::dwarf_linker::parallel::DependencyTracker::markDIEEntryAsKeptRec</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a29d892081e6d10f999dcf96f7a1b4729">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::setPlacement</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#aafd1866158f770ae45b007771e01ab0c">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::setPlacementIfUnset</a>.</p>

</div>
</div>

### PreciseRotationCost {#a0d30337c58d278817264718434f122ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PreciseRotationCost("precise-rotation-cost", cl::desc("Model the cost of loop rotation more " "precisely by using profile data."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### RenumberBlocksBeforeView {#ad1fed248fc2af534bd094b35c9f0c64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RenumberBlocksBeforeView("renumber-blocks-before-view", cl::desc( "If true, basic blocks are re-numbered before MBP layout is printed " "into a dot graph. Only used when a function is being printed."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>.</p>

</div>
</div>

### stats {#a971b2fc3751cade0a6b2f76c92774317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block placement stats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3813 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/ifordering/#adc0a9f87603bb0eee34a2246e6cea0d5">anonymous{HexagonGenInsert.cpp}::IFOrdering::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae6278b2864893c2bc2d86b5d6d9f2d51">rpmalloc_global_statistics</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#acb3289e60a1c405dbb154dce3f3d6c7a">rpmalloc_thread_statistics</a>.</p>

</div>
</div>

### Stats {#a086f939e29b718dc5a01e4bcfe6af2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block placement Basic Block Placement Stats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3814 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a1514e3ae4b6c55b9394b3271c4f06a6f">llvm::pdb::PDBSymbol::dumpChildStats</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ad7bfd8da79e55bf6a2b2ac4955b7f95d">dumpImportListForModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a8acf25125313b0e6333bb7fa3f4404f6">dumpIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54f0d8daf79208268f6bf031ce65b16a">llvm::exportDebugifyStats</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#af9754e1fdb25b2a1a60d2f748502e0f6">llvm::pdb::PDBSymbol::getChildStats</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae2ec74907c63d71091e1cea5af241927">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a1f8ac6e7a5b51acc2226820842e95107">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#aeaad4f1a2df47f25ea7e274d175c1b4e">llvm::BitcodeAnalyzer::printStats</a>.</p>

</div>
</div>

### TailDupPlacement {#abf71e6f582691ae8bdf8ed170fb11ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; TailDupPlacement("tail-dup-placement", cl::desc("Perform tail duplication during placement. " "Creates more fallthrough opportunities in " "outline branches."), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#ad65badde897b7d4f51fc7c545538a388">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::allowTailDupPlacement</a> and <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a237eea84de9a4035f23734cb04d32389">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::getAnalysisUsage</a>.</p>

</div>
</div>

### TailDupPlacementAggressiveThreshold {#adc8acb8291add6a055468711f701e78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TailDupPlacementAggressiveThreshold("tail-dup-placement-aggressive-threshold", cl::desc("Instruction cutoff for aggressive tail duplication during " "layout. Used at -O3. Tail merging during layout is forced to " "have a threshold that won't conflict."), cl::init(4), cl::Hidden)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TailDupPlacementPenalty {#a7344284dac6ba9b8e48d9be67c954bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TailDupPlacementPenalty("tail-dup-placement-penalty", cl::desc( "Cost penalty for blocks that can avoid breaking CFG by copying. " "Copying can increase fallthrough, but it also increases icache " "pressure. This parameter controls the penalty to account for that. " "Percent as integer."), cl::init(2), cl::Hidden)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="#a73743365177645c3db889f210cd5ad1d">greaterWithBias</a>.</p>

</div>
</div>

### TailDupPlacementThreshold {#a707021480bba6c165b873f9e238859c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TailDupPlacementThreshold("tail-dup-placement-threshold", cl::desc("Instruction cutoff for tail duplication during layout. " "Tail merging during layout is forced to have a threshold " "that won't conflict."), cl::init(2), cl::Hidden)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TailDupProfilePercentThreshold {#a84dfb254ed1062bc06a43d2365974bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TailDupProfilePercentThreshold("tail-dup-profile-percent-threshold", cl::desc("If profile count information is used in tail duplication cost " "model, the gained fall through number from tail duplication " "should be at least this percent of hot count."), cl::init(50), cl::Hidden)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TriangleChainCount {#a8ac66559c601e390e9477131019ee0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TriangleChainCount("triangle-chain-count", cl::desc("Number of triangle-shaped-CFG's that need to be in a row for the " "triangle tail duplication heuristic to kick in. 0 to disable."), cl::init(2), cl::Hidden)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"block-placement"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
