---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/branchprobabilityinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BranchProbabilityInfo` Class Reference

<p>Analysis providing branch probability information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BranchProbabilityInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64e605abe55b103bc98301b4ea5c62d">LoopData</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, int &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pair of <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> and SCC <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number. <a href="#ae64e605abe55b103bc98301b4ea5c62d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffe9a9398d5a7bfdad5be7e2b8c7693">LoopEdge</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66831d8af0b5131f093589c10f8f6c84">Edge</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771cb111ac312594590e53c1f3699fda">BranchProbabilityInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18bab54d5bb7925300874713924714b">BranchProbabilityInfo</a> (const Function &amp;F, const LoopInfo &amp;LI, const TargetLibraryInfo *TLI=nullptr, DominatorTree *DT=nullptr, PostDominatorTree *PDT=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab030c39bf198b14c4420c1c5e6c16114">BranchProbabilityInfo</a> (BranchProbabilityInfo &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4567e9936d8106c79d2323c859f5ba">BranchProbabilityInfo</a> (const BranchProbabilityInfo &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96150e5ef2b3f2c2a27e3e5782b1c4c">operator=</a> (const BranchProbabilityInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55cc2c7c13985c330a592f921db5e926">operator=</a> (BranchProbabilityInfo &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41951a9cbc849c4e0f2930f594c08847">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884b41d94b6ffea3302b48b3ab14fd58">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea510110989b4372eae3d2e68fcf04d">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46502d648608aa13cb485ed4af447d88">getEdgeProbability</a> (const BasicBlock *Src, unsigned IndexInSuccessors) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an edge's probability, relative to other out-edges of the Src. <a href="#a46502d648608aa13cb485ed4af447d88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b76388f3768d895c2c1029d3356481a">getEdgeProbability</a> (const BasicBlock *Src, const BasicBlock *Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the probability of going from Src to Dst. <a href="#a8b76388f3768d895c2c1029d3356481a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c75ce4a52aef066547edde4b012e6e2">getEdgeProbability</a> (const BasicBlock *Src, const_succ_iterator Dst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2da8547348736e285afd8af9093a83d">isEdgeHot</a> (const BasicBlock *Src, const BasicBlock *Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if an edge is hot relative to other out-edges of the Src. <a href="#aa2da8547348736e285afd8af9093a83d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13ac2ed5c40e40fff6ace158e7c0cf3">printEdgeProbability</a> (raw_ostream &amp;OS, const BasicBlock *Src, const BasicBlock *Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print an edge's probability. <a href="#ae13ac2ed5c40e40fff6ace158e7c0cf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145edc209aa2f628c73c9cf860eeeb5c">setEdgeProbability</a> (const BasicBlock *Src, const SmallVectorImpl&lt; BranchProbability &gt; &amp;Probs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the raw probabilities for all edges from the given block. <a href="#a145edc209aa2f628c73c9cf860eeeb5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af095c82360c397be730c08feb78264e9">copyEdgeProbabilities</a> (BasicBlock *Src, BasicBlock *Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy outgoing edge probabilities from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Dst</span>. <a href="#af095c82360c397be730c08feb78264e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f2ab60e1bb687cc5d9999ca97d57c2">swapSuccEdgesProbabilities</a> (const BasicBlock *Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap outgoing edges probabilities for <span class="doxyComputerOutput">Src</span> with branch terminator. <a href="#aa4f2ab60e1bb687cc5d9999ca97d57c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c3911cf4abbcd272fa99a303823942">calculate</a> (const Function &amp;F, const LoopInfo &amp;LI, const TargetLibraryInfo *TLI, DominatorTree *DT, PostDominatorTree *PDT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afb8520349ae7dc725ebfbb0532dbb1">eraseBlock</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forget analysis results for the given basic block. <a href="#a0afb8520349ae7dc725ebfbb0532dbb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LoopBlock</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca755b59fa2df435452505f3dcae1f8">getLoopBlock</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to construct LoopBlock for <span class="doxyComputerOutput">BB</span>. <a href="#a6ca755b59fa2df435452505f3dcae1f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017780ee735d0b759c1b8530593eabf7">isLoopEnteringEdge</a> (const LoopEdge &amp;Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if destination block belongs to some loop and source block is either doesn't belong to any loop or belongs to a loop which is not inner relative to the destination block. <a href="#a017780ee735d0b759c1b8530593eabf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6bbca341cf397870210c81158d115f">isLoopExitingEdge</a> (const LoopEdge &amp;Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if source block belongs to some loop and destination block is either doesn't belong to any loop or belongs to a loop which is not inner relative to the source block. <a href="#afe6bbca341cf397870210c81158d115f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658ce3c0572288413fcf1b42ff2a0743">isLoopEnteringExitingEdge</a> (const LoopEdge &amp;Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Edge</span> is either enters to or exits from some loop, false in all other cases. <a href="#a658ce3c0572288413fcf1b42ff2a0743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5929134366416c3b2824423d3d300ee1">isLoopBackEdge</a> (const LoopEdge &amp;Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if source and destination blocks belongs to the same loop and destination block is loop header. <a href="#a5929134366416c3b2824423d3d300ee1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc2645eb64f8b7a7b1dd0af923e3f3e">getLoopEnterBlocks</a> (const LoopBlock &amp;LB, SmallVectorImpl&lt; BasicBlock * &gt; &amp;Enters) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd31bed756c01c430a6b05ac16490d0d">getLoopExitBlocks</a> (const LoopBlock &amp;LB, SmallVectorImpl&lt; BasicBlock * &gt; &amp;Exits) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab812769371c960e95ea5ef11785b5ba8">getEstimatedBlockWeight</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns estimated weight for <span class="doxyComputerOutput">BB</span>. <a href="#ab812769371c960e95ea5ef11785b5ba8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3598bdb59d6d992198c3a4adc33e16">getEstimatedLoopWeight</a> (const LoopData &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns estimated weight to enter <span class="doxyComputerOutput">L</span>. <a href="#a4a3598bdb59d6d992198c3a4adc33e16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad49400fea6f31ece3e185f20a505f8b">getEstimatedEdgeWeight</a> (const LoopEdge &amp;Edge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return estimated weight for <span class="doxyComputerOutput">Edge</span>. <a href="#aad49400fea6f31ece3e185f20a505f8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83f5d11cd2252ec5710f8cbd13dfdd77">getMaxEstimatedEdgeWeight</a> (const LoopBlock &amp;SrcBB, iterator_range&lt; IterT &gt; Successors) const -&gt; std::optional&lt; uint32_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterates over all edges leading from <span class="doxyComputerOutput">SrcBB</span> to <span class="doxyComputerOutput">Successors</span> and returns maximum of all estimated weights. <a href="#a83f5d11cd2252ec5710f8cbd13dfdd77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef09d0c16ec287690b611c2b6ed7abaa">updateEstimatedBlockWeight</a> (LoopBlock &amp;LoopBB, uint32_t BBWeight, SmallVectorImpl&lt; BasicBlock * &gt; &amp;BlockWorkList, SmallVectorImpl&lt; LoopBlock &gt; &amp;LoopWorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">LoopBB</span> has no estimated weight then set it to <span class="doxyComputerOutput">BBWeight</span> and return true. <a href="#aef09d0c16ec287690b611c2b6ed7abaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d8b3049d21861f1e3bd85094e831ee">propagateEstimatedBlockWeight</a> (const LoopBlock &amp;LoopBB, DominatorTree *DT, PostDominatorTree *PDT, uint32_t BBWeight, SmallVectorImpl&lt; BasicBlock * &gt; &amp;WorkList, SmallVectorImpl&lt; LoopBlock &gt; &amp;LoopWorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Starting from <span class="doxyComputerOutput">LoopBB</span> (including <span class="doxyComputerOutput">LoopBB</span> itself) propagate <span class="doxyComputerOutput">BBWeight</span> up the domination tree. <a href="#ac8d8b3049d21861f1e3bd85094e831ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5713672d2a5bd673c4889c5fd20bed08">getInitialEstimatedBlockWeight</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns block's weight encoded in the IR. <a href="#a5713672d2a5bd673c4889c5fd20bed08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7339f713a00a22f68bf56973399945">computeEestimateBlockWeight</a> (const Function &amp;F, DominatorTree *DT, PostDominatorTree *PDT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9ae7d9f89c23d6edf49e320a519ed8">calcEstimatedHeuristics</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Based on computed weights by <span class="doxyComputerOutput">computeEstimatedBlockWeight</span> set probabilities on branches. <a href="#adc9ae7d9f89c23d6edf49e320a519ed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f6661bc9a7ba6ab4e37c4f5cd23237">calcMetadataWeights</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b29c1aa15d8372a273377f01d82230">calcPointerHeuristics</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287b9de9dbecd10c727217300a115cfb">calcZeroHeuristics</a> (const BasicBlock *BB, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647e365e2b5e994ee5b3c5f2781d37c5">calcFloatingPointHeuristics</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; BasicBlockCallbackVH, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4ccdbd0181c89d5ac411263724fb8f">Handles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; Edge, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0c2cfcd81dc805fe460b627a1898ac">Probs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb5c13da8fc36f4d9d4ab1fe9d1a0c56">LastF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the last function we run over for printing. <a href="#abb5c13da8fc36f4d9d4ab1fe9d1a0c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23300e04a69aae997531ae840c7d7fa3">LI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/sccinfo">SccInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8c96b0c73d9ee35da359a7e09f5939">SccI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps information about all SCCs in a function. <a href="#afe8c96b0c73d9ee35da359a7e09f5939">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297bbfee1fbb7a2b23a0a7093b1882c3">EstimatedBlockWeight</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps mapping of a basic block to its estimated weight. <a href="#a297bbfee1fbb7a2b23a0a7093b1882c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; LoopData, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707afcbd637b0c9d886a3978aec6b719">EstimatedLoopWeight</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps mapping of a loop to estimated weight to enter the loop. <a href="#a707afcbd637b0c9d886a3978aec6b719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4a47209688ad8c4359d4bf0f020f14">getBranchProbStackProtector</a> (bool IsLikely)</td>
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

<p>Analysis providing branch probability information.</p>


<p>This is a function analysis which provides information on the relative probabilities of each "edge" in the function's CFG where such an edge is defined by a pair (PredBlock and an index in the successors). The probability of an edge from one block is always relative to the probabilities of other edges from the block. The probabilites of all edges from a block sum to exactly one (100%). We use a pair (PredBlock and an index in the successors) to uniquely identify an edge, since we can have multiple edges from Src to Dst. As an example, we can have a switch which jumps to Dst with value 0 and value 10.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> of computing branch probabilities can be logically viewed as three step process:</p>


<p>First, if there is a profile information associated with the branch then it is trivially translated to branch probabilities. There is one exception from this rule though. Probabilities for edges leading to "unreachable" blocks (blocks with the estimated weight not greater than UNREACHABLE_WEIGHT) are evaluated according to static estimation and override profile information. If no branch probabilities were calculated on this step then take the next one.</p>


<p>Second, estimate absolute execution weights for each block based on statically known information. Roots of such information are "cold", "unreachable", "noreturn" and "unwind" blocks. Those blocks get their weights set to <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a0bab6cbda2c6f1e9dd352004a6b9f393a3f7ff4daa99912d1b0c8c64340edb9fb">BlockExecWeight::COLD</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a0bab6cbda2c6f1e9dd352004a6b9f393a58fd3b3b1f27606728077423eb21d8d6">BlockExecWeight::UNREACHABLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a0bab6cbda2c6f1e9dd352004a6b9f393a25c263e3b7486f9453d37151d62ff7d1">BlockExecWeight::NORETURN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a0bab6cbda2c6f1e9dd352004a6b9f393a37b88a87188456429fa6e6c31a6d2301">BlockExecWeight::UNWIND</a> respectively. Then the weights are propagated to the other blocks up the domination line. In addition, if all successors have estimated weights set then maximum of these weights assigned to the block itself (while this is not ideal heuristic in theory it's simple and works reasonably well in most cases) and the process repeats. Once the process of weights propagation converges branch probabilities are set for all such branches that have at least one successor with the weight set. Default execution weight (<a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#a0bab6cbda2c6f1e9dd352004a6b9f393a5b39c8b553c821e7cddc6da64b5bd2ee">BlockExecWeight::DEFAULT</a>) is used for any successors which doesn't have its weight set. For loop back branches we use their weights scaled by loop trip count equal to 'LBH_TAKEN_WEIGHT/LBH_NOTTAKEN_WEIGHT'.</p>


<p>Here is a simple example demonstrating how the described algorithm works.</p>



<pre><code>     BB1
    /   \
   v     v
 BB2     BB3
/   \
</code></pre>


<p>v v ColdBB UnreachBB</p>


<p>Initially, ColdBB is associated with COLD_WEIGHT and UnreachBB with UNREACHABLE_WEIGHT. COLD_WEIGHT is set to BB2 as maximum between its successors. BB1 and BB3 has no explicit estimated weights and assumed to have DEFAULT_WEIGHT. Based on assigned weights branches will have the following probabilities: P(BB1-&gt;BB2) = COLD_WEIGHT/(COLD_WEIGHT + DEFAULT_WEIGHT) = 0xffff / (0xffff + 0xfffff) = 0.0588(5.9%) P(BB1-&gt;BB3) = DEFAULT_WEIGHT_WEIGHT/(COLD_WEIGHT + DEFAULT_WEIGHT) = 0xfffff / (0xffff + 0xfffff) = 0.941(94.1%) P(BB2-&gt;ColdBB) = COLD_WEIGHT/(COLD_WEIGHT + UNREACHABLE_WEIGHT) = 1(100%) P(BB2-&gt;UnreachBB) = UNREACHABLE_WEIGHT/(COLD_WEIGHT+UNREACHABLE_WEIGHT) = 0(0%)</p>


<p>If no branch probabilities were calculated on this step then take the next one.</p>


<p>Third, apply different kinds of local heuristics for each individual branch until first match. For example probability of a pointer to be null is estimated as PH_TAKEN_WEIGHT/(PH_TAKEN_WEIGHT + PH_NONTAKEN_WEIGHT). If no local heuristic has been matched then branch is left with no explicit probability set and assumed to have default probability.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Edge {#a66831d8af0b5131f093589c10f8f6c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BranchProbabilityInfo::Edge =  std::pair&lt;const BasicBlock *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### LoopData {#ae64e605abe55b103bc98301b4ea5c62d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BranchProbabilityInfo::LoopData =  std::pair&lt;Loop *, int&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pair of <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> and SCC <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number.</p>


<p>Used to unify handling of normal and SCC based loop representations.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### LoopEdge {#a2ffe9a9398d5a7bfdad5be7e2b8c7693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BranchProbabilityInfo::LoopEdge =  std::pair&lt;const LoopBlock &amp;, const LoopBlock &amp;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BranchProbabilityInfo() {#a771cb111ac312594590e53c1f3699fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbabilityInfo::BranchProbabilityInfo ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>Referenced by <a href="#ab030c39bf198b14c4420c1c5e6c16114">BranchProbabilityInfo</a>, <a href="#a3e4567e9936d8106c79d2323c859f5ba">BranchProbabilityInfo</a>, <a href="#a55cc2c7c13985c330a592f921db5e926">operator=</a> and <a href="#ad96150e5ef2b3f2c2a27e3e5782b1c4c">operator=</a>.</p>

</div>
</div>

### BranchProbabilityInfo() {#ad18bab54d5bb7925300874713924714b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbabilityInfo::BranchProbabilityInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT=nullptr)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>References <a href="#a54c3911cf4abbcd272fa99a303823942">calculate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### BranchProbabilityInfo() {#ab030c39bf198b14c4420c1c5e6c16114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbabilityInfo::BranchProbabilityInfo (<a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>References <a href="#a771cb111ac312594590e53c1f3699fda">BranchProbabilityInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### BranchProbabilityInfo() {#a3e4567e9936d8106c79d2323c859f5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchProbabilityInfo::BranchProbabilityInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>Reference <a href="#a771cb111ac312594590e53c1f3699fda">BranchProbabilityInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad96150e5ef2b3f2c2a27e3e5782b1c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo &amp; llvm::BranchProbabilityInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>Reference <a href="#a771cb111ac312594590e53c1f3699fda">BranchProbabilityInfo</a>.</p>

</div>
</div>

### operator=() {#a55cc2c7c13985c330a592f921db5e926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo &amp; llvm::BranchProbabilityInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>References <a href="#a771cb111ac312594590e53c1f3699fda">BranchProbabilityInfo</a>, <a href="#a884b41d94b6ffea3302b48b3ab14fd58">releaseMemory</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculate() {#a54c3911cf4abbcd272fa99a303823942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::calculate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41c4916e8090ce40598db1a8dd2a5d5d">llvm::post_order</a>, <a href="#acea510110989b4372eae3d2e68fcf04d">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#af17aeb0484c720fb1e197adf768961c7">PrintBranchProb</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ae4ed89c6d8e92b055e0561a615dcbaf6">PrintBranchProbFuncName</a>.</p>


<p>Referenced by <a href="#ad18bab54d5bb7925300874713924714b">BranchProbabilityInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityanalysis/#a16f8c5851cffc6f908a232089fc71de6">llvm::BranchProbabilityAnalysis::run</a>.</p>

</div>
</div>

### copyEdgeProbabilities() {#af095c82360c397be730c08feb78264e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::copyEdgeProbabilities (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy outgoing edge probabilities from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Dst</span>.</p>


<p>This allows to keep probabilities unset for the destination if they were unset for source.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a0afb8520349ae7dc725ebfbb0532dbb1">eraseBlock</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### eraseBlock() {#a0afb8520349ae7dc725ebfbb0532dbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::eraseBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Forget analysis results for the given basic block.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#af095c82360c397be730c08feb78264e9">copyEdgeProbabilities</a>, <a href="#a145edc209aa2f628c73c9cf860eeeb5c">setEdgeProbability</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>.</p>

</div>
</div>

### getEdgeProbability() {#a46502d648608aa13cb485ed4af447d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability BranchProbabilityInfo::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, unsigned IndexInSuccessors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an edge's probability, relative to other out-edges of the Src.</p>


<p>Get the raw edge probability for the edge.</p>


<p>This routine provides access to the fractional probability between zero (0%) and one (100%) of this edge executing, relative to other edges leaving the 'Src' block. The returned probability is never zero, and can only be one if the source block has only one successor.</p>


<p>If can't find it, return a default probability 1/N where N is the number of successors. Here an edge is specified using PredBlock and an index to the successors.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a85da2bdebeeed0bf7fdccfdfc5f1b92c">llvm::succ_size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6289e8af46c9783382b346baa020087c">findUnwindDestinations</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a02f466eae018c75689a0189cb5f29524">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeAttributes</a>, <a href="#a4c75ce4a52aef066547edde4b012e6e2">getEdgeProbability</a>, <a href="#aa2da8547348736e285afd8af9093a83d">isEdgeHot</a>, <a href="#ae13ac2ed5c40e40fff6ace158e7c0cf3">printEdgeProbability</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>.</p>

</div>
</div>

### getEdgeProbability() {#a8b76388f3768d895c2c1029d3356481a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability BranchProbabilityInfo::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the probability of going from Src to Dst.</p>


<p>Get the raw edge probability calculated for the block pair.</p>


<p>It returns the sum of all probabilities for edges from Src to Dst.</p>


<p>This returns the sum of all raw edge probabilities from Src to Dst.</p>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5684e4976198c1b64b694d3972ddf78">llvm::succ_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85da2bdebeeed0bf7fdccfdfc5f1b92c">llvm::succ_size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

### getEdgeProbability() {#a4c75ce4a52aef066547edde4b012e6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability BranchProbabilityInfo::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/namespaces/llvm/#ae21e08e18fe951a73ef0942064ef841c">const_succ_iterator</a> Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Reference <a href="#a46502d648608aa13cb485ed4af447d88">getEdgeProbability</a>.</p>

</div>
</div>

### invalidate() {#a41951a9cbc849c4e0f2930f594c08847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#aa7a1b769f9c57010cc41d9c3bb9d39c6">llvm::PreservedAnalyses::getChecker</a>.</p>

</div>
</div>

### isEdgeHot() {#aa2da8547348736e285afd8af9093a83d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::isEdgeHot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if an edge is hot relative to other out-edges of the Src.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this edge out of the source block is 'hot'. We define hot as having a relative probability &gt; 80%.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Reference <a href="#a46502d648608aa13cb485ed4af447d88">getEdgeProbability</a>.</p>


<p>Referenced by <a href="#ae13ac2ed5c40e40fff6ace158e7c0cf3">printEdgeProbability</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a732bd4cf41862afa6092c1648c02e256">llvm::SelectionDAGBuilder::shouldKeepJumpConditionsTogether</a>.</p>

</div>
</div>

### print() {#acea510110989b4372eae3d2e68fcf04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae13ac2ed5c40e40fff6ace158e7c0cf3">printEdgeProbability</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a54c3911cf4abbcd272fa99a303823942">calculate</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityprinterpass/#af8bbfa323a4917223612dff12067110b">llvm::BranchProbabilityPrinterPass::run</a>.</p>

</div>
</div>

### printEdgeProbability() {#ae13ac2ed5c40e40fff6ace158e7c0cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; BranchProbabilityInfo::printEdgeProbability (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print an edge's probability.</p>


<p>Retrieves an edge's probability similarly to</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a46502d648608aa13cb485ed4af447d88">getEdgeProbability</a>, but then prints that probability to the provided stream. That stream is then returned.</p></dd>
</dl>


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#a46502d648608aa13cb485ed4af447d88">getEdgeProbability</a> and <a href="#aa2da8547348736e285afd8af9093a83d">isEdgeHot</a>.</p>


<p>Referenced by <a href="#acea510110989b4372eae3d2e68fcf04d">print</a>.</p>

</div>
</div>

### releaseMemory() {#a884b41d94b6ffea3302b48b3ab14fd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a55cc2c7c13985c330a592f921db5e926">operator=</a>.</p>

</div>
</div>

### setEdgeProbability() {#a145edc209aa2f628c73c9cf860eeeb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::setEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt; &amp; Probs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the raw probabilities for all edges from the given block.</p>


<p>Set the edge probability for all edges at once.</p>


<p>This allows a pass to explicitly set edge probabilities for a block. It can be used when updating the CFG to update the branch probability information.</p>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a0afb8520349ae7dc725ebfbb0532dbb1">eraseBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a19c752227e02f7cb26fb47fdb36dc349">llvm::BranchProbability::getDenominator</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>.</p>

</div>
</div>

### swapSuccEdgesProbabilities() {#aa4f2ab60e1bb687cc5d9999ca97d57c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::swapSuccEdgesProbabilities (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap outgoing edges probabilities for <span class="doxyComputerOutput">Src</span> with branch terminator.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calcEstimatedHeuristics() {#adc9ae7d9f89c23d6edf49e320a519ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::calcEstimatedHeuristics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Based on computed weights by <span class="doxyComputerOutput">computeEstimatedBlockWeight</span> set probabilities on branches.</p>

<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### calcFloatingPointHeuristics() {#a647e365e2b5e994ee5b3c5f2781d37c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::calcFloatingPointHeuristics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### calcMetadataWeights() {#a18f6661bc9a7ba6ab4e37c4f5cd23237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::calcMetadataWeights (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### calcPointerHeuristics() {#a73b29c1aa15d8372a273377f01d82230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::calcPointerHeuristics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### calcZeroHeuristics() {#a287b9de9dbecd10c727217300a115cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::calcZeroHeuristics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### computeEestimateBlockWeight() {#aff7339f713a00a22f68bf56973399945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::computeEestimateBlockWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getEstimatedBlockWeight() {#ab812769371c960e95ea5ef11785b5ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; BranchProbabilityInfo::getEstimatedBlockWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns estimated weight for <span class="doxyComputerOutput">BB</span>.</p>


<p>std::nullopt if <span class="doxyComputerOutput">BB</span> has no estimated weight.</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getEstimatedEdgeWeight() {#aad49400fea6f31ece3e185f20a505f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; BranchProbabilityInfo::getEstimatedEdgeWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopEdge &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return estimated weight for <span class="doxyComputerOutput">Edge</span>.</p>


<p>Returns std::nullopt if estimated weight is unknown.</p>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getEstimatedLoopWeight() {#a4a3598bdb59d6d992198c3a4adc33e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; BranchProbabilityInfo::getEstimatedLoopWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopData &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns estimated weight to enter <span class="doxyComputerOutput">L</span>.</p>


<p>In other words it is weight of loop's header block not scaled by trip count. Returns std::nullopt if <span class="doxyComputerOutput">L</span> has no no estimated weight.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getInitialEstimatedBlockWeight() {#a5713672d2a5bd673c4889c5fd20bed08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; BranchProbabilityInfo::getInitialEstimatedBlockWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns block's weight encoded in the IR.</p>

<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getLoopBlock() {#a6ca755b59fa2df435452505f3dcae1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopBlock llvm::BranchProbabilityInfo::getLoopBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Helper to construct LoopBlock for <span class="doxyComputerOutput">BB</span>.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### getLoopEnterBlocks() {#a6cc2645eb64f8b7a7b1dd0af923e3f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::getLoopEnterBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp; LB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Enters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getLoopExitBlocks() {#acd31bed756c01c430a6b05ac16490d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::getLoopExitBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp; LB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Exits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### getMaxEstimatedEdgeWeight() {#a83f5d11cd2252ec5710f8cbd13dfdd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; BranchProbabilityInfo::getMaxEstimatedEdgeWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp; SrcBB, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IterT &gt; Successors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterates over all edges leading from <span class="doxyComputerOutput">SrcBB</span> to <span class="doxyComputerOutput">Successors</span> and returns maximum of all estimated weights.</p>


<p>If at least one edge has unknown estimated weight std::nullopt is returned.</p>


<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### isLoopBackEdge() {#a5929134366416c3b2824423d3d300ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::isLoopBackEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopEdge &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if source and destination blocks belongs to the same loop and destination block is loop header.</p>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### isLoopEnteringEdge() {#a017780ee735d0b759c1b8530593eabf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::isLoopEnteringEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopEdge &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if destination block belongs to some loop and source block is either doesn't belong to any loop or belongs to a loop which is not inner relative to the destination block.</p>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### isLoopEnteringExitingEdge() {#a658ce3c0572288413fcf1b42ff2a0743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::isLoopEnteringExitingEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopEdge &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">Edge</span> is either enters to or exits from some loop, false in all other cases.</p>

<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### isLoopExitingEdge() {#afe6bbca341cf397870210c81158d115f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::isLoopExitingEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopEdge &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if source block belongs to some loop and destination block is either doesn't belong to any loop or belongs to a loop which is not inner relative to the source block.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### propagateEstimatedBlockWeight() {#ac8d8b3049d21861f1e3bd85094e831ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchProbabilityInfo::propagateEstimatedBlockWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopBlock &amp; LoopBB, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT, uint32_t BBWeight, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; WorkList, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LoopBlock &gt; &amp; LoopWorkList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Starting from <span class="doxyComputerOutput">LoopBB</span> (including <span class="doxyComputerOutput">LoopBB</span> itself) propagate <span class="doxyComputerOutput">BBWeight</span> up the domination tree.</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### updateEstimatedBlockWeight() {#aef09d0c16ec287690b611c2b6ed7abaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BranchProbabilityInfo::updateEstimatedBlockWeight (LoopBlock &amp; LoopBB, uint32_t BBWeight, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BlockWorkList, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LoopBlock &gt; &amp; LoopWorkList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">LoopBB</span> has no estimated weight then set it to <span class="doxyComputerOutput">BBWeight</span> and return true.</p>


<p>Otherwise <span class="doxyComputerOutput">BB's</span> weight remains unchanged and false is returned. In addition all blocks/loops that might need their weight to be re-estimated are put into BlockWorkList/LoopWorkList.</p>


<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EstimatedBlockWeight {#a297bbfee1fbb7a2b23a0a7093b1882c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;const BasicBlock *, uint32_t&gt; llvm::BranchProbabilityInfo::EstimatedBlockWeight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps mapping of a basic block to its estimated weight.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### EstimatedLoopWeight {#a707afcbd637b0c9d886a3978aec6b719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;LoopData, uint32_t&gt; llvm::BranchProbabilityInfo::EstimatedLoopWeight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps mapping of a loop to estimated weight to enter the loop.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### Handles {#a0c4ccdbd0181c89d5ac411263724fb8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;BasicBlockCallbackVH, DenseMapInfo&lt;Value*&gt; &gt; llvm::BranchProbabilityInfo::Handles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### LastF {#abb5c13da8fc36f4d9d4ab1fe9d1a0c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::BranchProbabilityInfo::LastF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track the last function we run over for printing.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### LI {#a23300e04a69aae997531ae840c7d7fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo* llvm::BranchProbabilityInfo::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### Probs {#ada0c2cfcd81dc805fe460b627a1898ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Edge, BranchProbability&gt; llvm::BranchProbabilityInfo::Probs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

### SccI {#afe8c96b0c73d9ee35da359a7e09f5939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const SccInfo&gt; llvm::BranchProbabilityInfo::SccI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps information about all SCCs in a function.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBranchProbStackProtector() {#a4e4a47209688ad8c4359d4bf0f020f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::BranchProbabilityInfo::getBranchProbStackProtector (bool IsLikely)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#aaee6034264d5d0782e5d1489360730d9">llvm::BranchProbability::getCompl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">BranchProbabilityInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
