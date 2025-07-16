---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineBlockPlacement` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c69f46915104b4b42bad5b16926896b">BlockFilterSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type for a block filter set. <a href="#a2c69f46915104b4b42bad5b16926896b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7175334e09f55bf7b5fb08d9522449e">MachineBlockPlacement</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0291b83febf5c94491d76bf5236799">runOnMachineFunction</a> (MachineFunction &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a1f0291b83febf5c94491d76bf5236799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65badde897b7d4f51fc7c545538a388">allowTailDupPlacement</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237eea84de9a4035f23734cb04d32389">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a237eea84de9a4035f23734cb04d32389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb8826c90dd0b335005ad4bcec6a319">getBlockCountOrFrequency</a> (const MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get block profile count or frequency according to UseProfileCount. <a href="#aadb8826c90dd0b335005ad4bcec6a319">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009bd7be185b0d28640c95a65d3015cd">scaleThreshold</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale the DupThreshold according to basic block size. <a href="#a009bd7be185b0d28640c95a65d3015cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332bfc8fa4bd863bb875ec26f28764c9">initTailDupThreshold</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8609559711967b7ec0af133d7979c4d9">markChainSuccessors</a> (const BlockChain &amp;Chain, const MachineBasicBlock *LoopHeaderBB, const BlockFilterSet *BlockFilter=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrease the UnscheduledPredecessors count for all blocks in chain, and if the count goes to 0, add them to the appropriate work list. <a href="#a8609559711967b7ec0af133d7979c4d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa0e67ba11ea993bd3f047cb851220a">markBlockSuccessors</a> (const BlockChain &amp;Chain, const MachineBasicBlock *BB, const MachineBasicBlock *LoopHeaderBB, const BlockFilterSet *BlockFilter=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrease the UnscheduledPredecessors count for a single block, and if the count goes to 0, add them to the appropriate work list. <a href="#a7fa0e67ba11ea993bd3f047cb851220a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f747b70337f75406dd9c17e20c2903">collectViableSuccessors</a> (const MachineBasicBlock *BB, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter, SmallVector&lt; MachineBasicBlock *, 4 &gt; &amp;Successors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This helper function collects the set of successors of block <span class="doxyComputerOutput">BB</span> that are allowed to be its layout successors, and return the total branch probability of edges from <span class="doxyComputerOutput">BB</span> to those blocks. <a href="#af4f747b70337f75406dd9c17e20c2903">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd05f1814cdb465e33bbd1f8ad3acc9c">isBestSuccessor</a> (MachineBasicBlock *BB, MachineBasicBlock *Pred, BlockFilterSet *BlockFilter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b682f772067f17b5b2a9fd6450053e">findDuplicateCandidates</a> (SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;Candidates, MachineBasicBlock *BB, BlockFilterSet *BlockFilter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ae9e4e255c09f00874e3defceaaf75">repeatedlyTailDuplicateBlock</a> (MachineBasicBlock *BB, MachineBasicBlock *&amp;LPred, const MachineBasicBlock *LoopHeaderBB, BlockChain &amp;Chain, BlockFilterSet *BlockFilter, MachineFunction::iterator &amp;PrevUnplacedBlockIt, BlockFilterSet::iterator &amp;PrevUnplacedBlockInFilterIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tail duplicate <span class="doxyComputerOutput">BB</span> into (some) predecessors if profitable, repeating if it was duplicated into its chain predecessor and removed. <a href="#a65ae9e4e255c09f00874e3defceaaf75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e211e03c3ab0d21b495345984eb1b63">maybeTailDuplicateBlock</a> (MachineBasicBlock *BB, MachineBasicBlock *LPred, BlockChain &amp;Chain, BlockFilterSet *BlockFilter, MachineFunction::iterator &amp;PrevUnplacedBlockIt, BlockFilterSet::iterator &amp;PrevUnplacedBlockInFilterIt, bool &amp;DuplicatedToLPred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tail duplicate <span class="doxyComputerOutput">BB</span> into (some) predecessors if profitable. <a href="#a7e211e03c3ab0d21b495345984eb1b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a68e0308163acb4ff57c35fda2d4c0b">hasBetterLayoutPredecessor</a> (const MachineBasicBlock *BB, const MachineBasicBlock *Succ, const BlockChain &amp;SuccChain, BranchProbability SuccProb, BranchProbability RealSuccProb, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks to see if the layout candidate block <span class="doxyComputerOutput">Succ</span> has a better layout predecessor than <span class="doxyComputerOutput">BB</span>. <a href="#a3a68e0308163acb4ff57c35fda2d4c0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockAndTailDupResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed68a87de5a4e312f928382ee2d8a39">selectBestSuccessor</a> (const MachineBasicBlock *BB, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the best successor for a block. <a href="#a3ed68a87de5a4e312f928382ee2d8a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbe168d7c61f38f4c3c8e68ddc68bc0">selectBestCandidateBlock</a> (const BlockChain &amp;Chain, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;WorkList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the best block from a worklist. <a href="#a3dbe168d7c61f38f4c3c8e68ddc68bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc423946a994d1c522af1f0cdd78842">getFirstUnplacedBlock</a> (const BlockChain &amp;PlacedChain, MachineFunction::iterator &amp;PrevUnplacedBlockIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the first unplaced basic block in the entire function. <a href="#a4fc423946a994d1c522af1f0cdd78842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bb0192a595fdd2777b79e53dda7699">getFirstUnplacedBlock</a> (const BlockChain &amp;PlacedChain, BlockFilterSet::iterator &amp;PrevUnplacedBlockInFilterIt, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the first unplaced basic block among the blocks in BlockFilter. <a href="#a05bb0192a595fdd2777b79e53dda7699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4f20302361dca3c6ad9c7a0a23a254">fillWorkLists</a> (const MachineBasicBlock *MBB, SmallPtrSetImpl&lt; BlockChain * &gt; &amp;UpdatedPreds, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a basic block to the work list if it is appropriate. <a href="#acb4f20302361dca3c6ad9c7a0a23a254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ed2f04dbeb423f8b2b05d83fe373c0">buildChain</a> (const MachineBasicBlock *BB, BlockChain &amp;Chain, BlockFilterSet *BlockFilter=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c706ea3bc7f05bb86d36f275569739">canMoveBottomBlockToTop</a> (const MachineBasicBlock *BottomBlock, const MachineBasicBlock *OldTop)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff12fe20ff61e8bf79201ab31679c39">hasViableTopFallthrough</a> (const MachineBasicBlock *Top, const BlockFilterSet &amp;LoopBlockSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if there is a fallthrough to loop header Top. <a href="#a2ff12fe20ff61e8bf79201ab31679c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea1eb87358ab0ae882000fdfa36feb9">TopFallThroughFreq</a> (const MachineBasicBlock *Top, const BlockFilterSet &amp;LoopBlockSet)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d9afd96859e481b29ccc73e1b7501c">FallThroughGains</a> (const MachineBasicBlock *NewTop, const MachineBasicBlock *OldTop, const MachineBasicBlock *ExitBB, const BlockFilterSet &amp;LoopBlockSet)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cc0da9270fd9c0b3429a269a01bb08">findBestLoopTopHelper</a> (MachineBasicBlock *OldTop, const MachineLoop &amp;L, const BlockFilterSet &amp;LoopBlockSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function of findBestLoopTop. <a href="#a52cc0da9270fd9c0b3429a269a01bb08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700f6c4424f435cc11b5afabd9c115a4">findBestLoopTop</a> (const MachineLoop &amp;L, const BlockFilterSet &amp;LoopBlockSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the best loop top block for layout. <a href="#a700f6c4424f435cc11b5afabd9c115a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa49006361b1edf655176b7b8f4d974d">findBestLoopExit</a> (const MachineLoop &amp;L, const BlockFilterSet &amp;LoopBlockSet, BlockFrequency &amp;ExitFreq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the best loop exiting block for layout. <a href="#afa49006361b1edf655176b7b8f4d974d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1acc167ff314bcf89aa2028e25ffaaf2">collectLoopBlockSet</a> (const MachineLoop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect blocks in the given loop that are to be placed. <a href="#a1acc167ff314bcf89aa2028e25ffaaf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752789a7a68c3b05cf9c6a697457c0f6">buildLoopChains</a> (const MachineLoop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forms basic block chains from the natural loop structures. <a href="#a752789a7a68c3b05cf9c6a697457c0f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9447fbcd903da1f7bca306c626f7b3da">rotateLoop</a> (BlockChain &amp;LoopChain, const MachineBasicBlock *ExitingBB, BlockFrequency ExitFreq, const BlockFilterSet &amp;LoopBlockSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to rotate an exiting block to the bottom of the loop. <a href="#a9447fbcd903da1f7bca306c626f7b3da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fba9be30449ffa8970bb8aa4edb2b9">rotateLoopWithProfile</a> (BlockChain &amp;LoopChain, const MachineLoop &amp;L, const BlockFilterSet &amp;LoopBlockSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to rotate a loop based on profile data to reduce branch cost. <a href="#a48fba9be30449ffa8970bb8aa4edb2b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f22114b14e9ddeab55355f3c27acc58">buildCFGChains</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f862faa7617594bcb965034bbf4c39">optimizeBranches</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b76bc8d639056cba8c0deaa82dab8ba">alignBlocks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6e3b50fb30841d4a19f267d7ba413a">shouldTailDuplicate</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a block should be tail-duplicated to increase fallthrough opportunities. <a href="#a7d6e3b50fb30841d4a19f267d7ba413a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5410d1504b3e2a7a4a0685d8bba226">isProfitableToTailDup</a> (const MachineBasicBlock *BB, const MachineBasicBlock *Succ, BranchProbability QProb, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check the edge frequencies to see if tail duplication will increase fallthroughs. <a href="#aeb5410d1504b3e2a7a4a0685d8bba226">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314cc0aa7d21a01c59621f195b117be7">isTrellis</a> (const MachineBasicBlock *BB, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;ViableSuccs, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check for a trellis layout. <a href="#a314cc0aa7d21a01c59621f195b117be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockAndTailDupResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4e1f1116322b2fae38b312ea5604f8">getBestTrellisSuccessor</a> (const MachineBasicBlock *BB, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;ViableSuccs, BranchProbability AdjustedSumProb, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the best successor given a trellis layout. <a href="#a5d4e1f1116322b2fae38b312ea5604f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a79faa1efd30a5da08320dfb6844e4">canTailDuplicateUnplacedPreds</a> (const MachineBasicBlock *BB, MachineBasicBlock *Succ, const BlockChain &amp;Chain, const BlockFilterSet *BlockFilter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a block can tail duplicate into all unplaced predecessors. <a href="#ac0a79faa1efd30a5da08320dfb6844e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f9503d0622e93edb0a6ba39a1a83bc9">precomputeTriangleChains</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find chains of triangles to tail-duplicate where a global analysis works, but a local analysis would not find them. <a href="#a9f9503d0622e93edb0a6ba39a1a83bc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74729b845cbd9fa6bc1ad1e004e725eb">applyExtTsp</a> (bool OptForSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a post-processing step optimizing block placement. <a href="#a74729b845cbd9fa6bc1ad1e004e725eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da2ef31296d894b5114536904af573b">assignBlockOrder</a> (const std::vector&lt; const MachineBasicBlock * &gt; &amp;NewOrder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify the existing block placement in the function and adjust all jumps. <a href="#a9da2ef31296d894b5114536904af573b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b9d27f22cbc9e88e6fd93b4cbb0c67f">createCFGChainExtTsp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a single CFG chain from the current block order. <a href="#a2b9d27f22cbc9e88e6fd93b4cbb0c67f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3cba63507b6bbbb2a0132e16880431">BlockWorkList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>work lists of blocks that are ready to be laid out <a href="#aae3cba63507b6bbbb2a0132e16880431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e15aacb3f480ea24dcef7ee9bf2942">EHPadWorkList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, BlockAndTailDupResult &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787183229d5c3229b5084e4577e3083d">ComputedEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Edges that have already been computed as optimal. <a href="#a787183229d5c3229b5084e4577e3083d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441346b8c3a351fc729ba5322d76f650">F</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#a441346b8c3a351fc729ba5322d76f650">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cafd878b0393094413d5314b7f5433f">MBPI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the branch probability pass. <a href="#a1cafd878b0393094413d5314b7f5433f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper">MBFIWrapper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d3256c15bed44ceb54bd6d1e98eeac">MBFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the function-wide block frequency pass. <a href="#ae4d3256c15bed44ceb54bd6d1e98eeac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9043c382d0cd4a27bb67f8d04f51f0bd">MLI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the loop info. <a href="#a9043c382d0cd4a27bb67f8d04f51f0bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a50cdc995bbaf9976f47390525c799b">PreferredLoopExit</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Preferred loop exit. <a href="#a2a50cdc995bbaf9976f47390525c799b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be7707838427e4d20b01d1888fd1950">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the target's instruction info. <a href="#a6be7707838427e4d20b01d1888fd1950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff48bdcbafede2c75e4d99a4b8a62cb0">TLI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the target's lowering info. <a href="#aff48bdcbafede2c75e4d99a4b8a62cb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd727768855e8c4d0aec1e56ef0276d">MPDT</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the post dominator tree. <a href="#aebd727768855e8c4d0aec1e56ef0276d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf36e76dddb06c1e1ffa7510b32f1e5">PSI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657470178bb8e218eff04adbf577e575">PassConfig</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tailduplicator">TailDuplicator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a3df2e6483c164757dceb156788a11">TailDup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Duplicator used to duplicate tails during placement. <a href="#a70a3df2e6483c164757dceb156788a11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11922d600fffe2c8358b1ab5746328d">DupThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partial tail duplication threshold. <a href="#ae11922d600fffe2c8358b1ab5746328d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8891a946fba735052f70421f420e8d">TailDupSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581affb9c081f5fb1826892f66531871">UseProfileCount</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True: use block profile count to compute tail duplication cost. <a href="#a581affb9c081f5fb1826892f66531871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409c5b3292089d63a3a8afc797f7853d">ChainAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator and owner of <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> structures. <a href="#a409c5b3292089d63a3a8afc797f7853d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f0109902ee879fc0f2fb344a40ec60">BlockToChain</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> wide <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> mapping. <a href="#a73f0109902ee879fc0f2fb344a40ec60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3fc59ca71bf4817ece50eb678512a81">BlocksWithUnanalyzableExits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of basic blocks that have terminators that cannot be fully analyzed. <a href="#ad3fc59ca71bf4817ece50eb678512a81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; WeightedEdge, WeightedEdge &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984864f0c5f4ecf52a87268c077969ee">getBestNonConflictingEdges</a> (const MachineBasicBlock *BB, MutableArrayRef&lt; SmallVector&lt; WeightedEdge, 8 &gt; &gt; Edges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the best pair of non-conflicting edges. <a href="#a984864f0c5f4ecf52a87268c077969ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4944db6b12999ee0713352c27e8125e4">ID</a> = 0</td>
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


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockFilterSet {#a2c69f46915104b4b42bad5b16926896b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::BlockFilterSet =  SmallSetVector&lt;const MachineBasicBlock *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A type for a block filter set.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineBlockPlacement() {#ad7175334e09f55bf7b5fb08d9522449e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MachineBlockPlacement ()</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a4944db6b12999ee0713352c27e8125e4">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3e08655b0654029c7cf037651c8d7d6">llvm::initializeMachineBlockPlacementPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowTailDupPlacement() {#ad65badde897b7d4f51fc7c545538a388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::allowTailDupPlacement ()</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#abf71e6f582691ae8bdf8ed170fb11ae6">TailDupPlacement</a>.</p>


<p>Referenced by <a href="#a1f0291b83febf5c94491d76bf5236799">runOnMachineFunction</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a237eea84de9a4035f23734cb04d32389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#abf71e6f582691ae8bdf8ed170fb11ae6">TailDupPlacement</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a1f0291b83febf5c94491d76bf5236799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="#ad65badde897b7d4f51fc7c545538a388">allowTailDupPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a956f6faccd85fe2a75302e0ac3ecc606">ApplyExtTspForSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2dee051dfc0746e4fbf6e26175ece121">llvm::ApplyExtTspWithoutProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a84ae0b35deb4cbcffc27c3d52a781fca">BranchFoldPlacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4599fe5d1385154f1bfbc41a10495c5">llvm::EnableExtTspBlockPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a1160412b923427430e8bf4c819d79a93">ExtTspBlockPlacementMaxBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0bf055834b973decc2477a8061624ffa49315903a2559d882f356ae28a455556">llvm::GVDT_None</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp/#a8884a3765a9cdbc730400587d4a3192c">hasProfileData</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac85349aab432e6b7d8b2e8926048a6de">llvm::MachineFunction::RenumberBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#ad1fed248fc2af534bd094b35c9f0c64b">RenumberBlocksBeforeView</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa276e49983e93afa359ec83ad71ccadc">llvm::TargetMachine::requiresStructuredCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a7d2ce2106f9f7cf8f45c7c3c116ef43d">llvm::MachineFunction::size</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a73423bf857429f170a6355ae20e1d798">TailMergeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6391a34afa5b4ed1a5e556a8cc4d971b">llvm::ViewBlockFreqFuncName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7cc8a419725f3a9ce1d23c2db21ea143">llvm::ViewBlockLayoutWithBFI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### alignBlocks() {#a0b76bc8d639056cba8c0deaa82dab8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::alignBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### applyExtTsp() {#a74729b845cbd9fa6bc1ad1e004e725eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::applyExtTsp (bool OptForSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply a post-processing step optimizing block placement.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### assignBlockOrder() {#a9da2ef31296d894b5114536904af573b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::assignBlockOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; NewOrder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modify the existing block placement in the function and adjust all jumps.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### buildCFGChains() {#a0f22114b14e9ddeab55355f3c27acc58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::buildCFGChains ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### buildChain() {#a66ed2f04dbeb423f8b2b05d83fe373c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::buildChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### buildLoopChains() {#a752789a7a68c3b05cf9c6a697457c0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::buildLoopChains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Forms basic block chains from the natural loop structures.</p>


<p>These chains are designed to preserve the existing <em>structure</em> of the code as much as possible. We can then stitch the chains together in a way which both preserves the topological structure and minimizes taken conditional branches.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### canMoveBottomBlockToTop() {#a94c706ea3bc7f05bb86d36f275569739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::canMoveBottomBlockToTop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BottomBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * OldTop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### canTailDuplicateUnplacedPreds() {#ac0a79faa1efd30a5da08320dfb6844e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::canTailDuplicateUnplacedPreds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if a block can tail duplicate into all unplaced predecessors.</p>


<p>When the option <a href="#ad65badde897b7d4f51fc7c545538a388">allowTailDupPlacement()</a> is on, this method checks if the fallthrough candidate block <span class="doxyComputerOutput">Succ</span> (of block <span class="doxyComputerOutput">BB</span>) can be tail-duplicated into all of its unplaced, unfiltered predecessors, that are not BB.</p>


<p>Filters based on loop.</p>


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### collectLoopBlockSet() {#a1acc167ff314bcf89aa2028e25ffaaf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockPlacement::BlockFilterSet MachineBlockPlacement::collectLoopBlockSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect blocks in the given loop that are to be placed.</p>


<p>When profile data is available, exclude cold blocks from the returned set; otherwise, collect all blocks in the loop.</p>


<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### collectViableSuccessors() {#af4f747b70337f75406dd9c17e20c2903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability MachineBlockPlacement::collectViableSuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt; &amp; Successors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This helper function collects the set of successors of block <span class="doxyComputerOutput">BB</span> that are allowed to be its layout successors, and return the total branch probability of edges from <span class="doxyComputerOutput">BB</span> to those blocks.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### createCFGChainExtTsp() {#a2b9d27f22cbc9e88e6fd93b4cbb0c67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::createCFGChainExtTsp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a single CFG chain from the current block order.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### FallThroughGains() {#a48d9afd96859e481b29ccc73e1b7501c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency MachineBlockPlacement::FallThroughGains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * OldTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ExitBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### fillWorkLists() {#acb4f20302361dca3c6ad9c7a0a23a254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::fillWorkLists (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> * &gt; &amp; UpdatedPreds, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a basic block to the work list if it is appropriate.</p>


<p>If the optional parameter BlockFilter is provided, only MBB present in the set will be added to the worklist. If nullptr is provided, no filtering occurs.</p>


<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### findBestLoopExit() {#afa49006361b1edf655176b7b8f4d974d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::findBestLoopExit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp; ExitFreq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the best loop exiting block for layout.</p>


<p>This routine implements the logic to analyze the loop looking for the best block to layout at the top of the loop. Typically this is done to maximize fallthrough opportunities.</p>


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### findBestLoopTop() {#a700f6c4424f435cc11b5afabd9c115a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::findBestLoopTop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the best loop top block for layout.</p>


<p>This function iteratively calls findBestLoopTopHelper, until no new better BB can be found.</p>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### findBestLoopTopHelper() {#a52cc0da9270fd9c0b3429a269a01bb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::findBestLoopTopHelper (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * OldTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function of findBestLoopTop.</p>


<p>Find the best loop top block from predecessors of old top.</p>


<p>Look for a block which is strictly better than the old top for laying out before the old top of the loop. This looks for only two patterns:</p>



<pre><code>1. a block has only one successor, the old loop top

   Because such a block will always result in an unconditional jump,
   rotating it in front of the old top is always profitable.

2. a block has two successors, one is old top, another is exit
   and it has more than one predecessors

   If it is below one of its predecessors P, only P can fall through to
   it, all other predecessors need a jump to it, and another conditional
   jump to loop header. If it is moved before loop header, all its
   predecessors jump to it, then fall through to loop header. So all its
   predecessors except P can reduce one taken branch.
   At the same time, move it before old top increases the taken branch
   to loop exit block, so the reduced taken branch will be compared with
   the increased taken branch to the loop exit block.
</code></pre>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### findDuplicateCandidates() {#ae7b682f772067f17b5b2a9fd6450053e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::findDuplicateCandidates (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Candidates, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### getBestTrellisSuccessor() {#a5d4e1f1116322b2fae38b312ea5604f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockPlacement::BlockAndTailDupResult MachineBlockPlacement::getBestTrellisSuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; ViableSuccs, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> AdjustedSumProb, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the best successor given a trellis layout.</p>


<p>Get the best successor from <span class="doxyComputerOutput">BB</span> based on <span class="doxyComputerOutput">BB</span> being part of a trellis.</p>


<p>We only handle trellises with 2 successors, so the algorithm is straightforward: Find the best pair of edges that don't conflict. We find the best incoming edge for each successor in the trellis. If those conflict, we consider which of them should be replaced with the second best. Upon return the two best edges will be in <span class="doxyComputerOutput">BestEdges</span>. If one of the edges comes from <span class="doxyComputerOutput">BB</span>, it will be in <span class="doxyComputerOutput">BestEdges</span>[0]</p>


<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### getBlockCountOrFrequency() {#aadb8826c90dd0b335005ad4bcec6a319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::getBlockCountOrFrequency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Get block profile count or frequency according to UseProfileCount.</p>


<p>The return value is used to model tail duplication cost.</p>


<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### getFirstUnplacedBlock() {#a4fc423946a994d1c522af1f0cdd78842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::getFirstUnplacedBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; PlacedChain, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aaba82c71ffdca966cad10eae0992fff9">MachineFunction::iterator</a> &amp; PrevUnplacedBlockIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the first unplaced basic block in the entire function.</p>


<p>This routine is called when we are unable to use the CFG to walk through all of the basic blocks and form a chain due to unnatural loops in the CFG. We walk through the function's blocks in order, starting from the LastUnplacedBlockIt. We update this iterator on each call to avoid re-scanning the entire sequence on repeated calls to this routine.</p>


<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### getFirstUnplacedBlock() {#a05bb0192a595fdd2777b79e53dda7699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::getFirstUnplacedBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; PlacedChain, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a813fd00ac7e5e3261ffe67f9322a5480">BlockFilterSet::iterator</a> &amp; PrevUnplacedBlockInFilterIt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the first unplaced basic block among the blocks in BlockFilter.</p>


<p>This is similar to getFirstUnplacedBlock for the entire function, but since the size of BlockFilter is typically far less than the number of blocks in the entire function, iterating through the BlockFilter is more efficient. When processing the entire funciton, using the version without BlockFilter has a complexity of #(loops in function) * #(blocks in function), while this version has a complexity of sum(#(loops in block) foreach block in function) which is always smaller. For long function mostly sequential in structure, the complexity is amortized to 1 * #(blocks in function).</p>


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### hasBetterLayoutPredecessor() {#a3a68e0308163acb4ff57c35fda2d4c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::hasBetterLayoutPredecessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; SuccChain, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> SuccProb, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> RealSuccProb, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks to see if the layout candidate block <span class="doxyComputerOutput">Succ</span> has a better layout predecessor than <span class="doxyComputerOutput">BB</span>.</p>


<p>If yes, returns true. <span class="doxyComputerOutput">SuccProb:</span> The probability adjusted for only remaining blocks. Only used for logging <span class="doxyComputerOutput">RealSuccProb:</span> The un-adjusted probability. <span class="doxyComputerOutput">Chain:</span> The chain that BB belongs to and Succ is being considered for. <span class="doxyComputerOutput">BlockFilter:</span> if non-null, the set of blocks that make up the loop being considered</p>


<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### hasViableTopFallthrough() {#a2ff12fe20ff61e8bf79201ab31679c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::hasViableTopFallthrough (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Top, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if there is a fallthrough to loop header Top.</p>


<ol class="doxyList" type="1">
<li>Look for a Pred that can be layout before Top.</li>
<li>Check if Top is the most possible successor of Pred.</li>
</ol>

<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### initTailDupThreshold() {#a332bfc8fa4bd863bb875ec26f28764c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::initTailDupThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### isBestSuccessor() {#abd05f1814cdb465e33bbd1f8ad3acc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::isBestSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### isProfitableToTailDup() {#aeb5410d1504b3e2a7a4a0685d8bba226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::isProfitableToTailDup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> QProb, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check the edge frequencies to see if tail duplication will increase fallthroughs.</p>


<p>It only makes sense to call this function when <span class="doxyComputerOutput">Succ</span> would not be chosen otherwise. Tail duplication of <span class="doxyComputerOutput">Succ</span> is always locally profitable if we would have picked <span class="doxyComputerOutput">Succ</span> without considering duplication.</p>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### isTrellis() {#a314cc0aa7d21a01c59621f195b117be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::isTrellis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; ViableSuccs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check for a trellis layout.</p>


<p><span class="doxyComputerOutput">BB</span> is the upper part of a trellis if its successors form the lower part of a trellis. A successor set S forms the lower part of a trellis if all of the predecessors of S are either in S or have all of S as successors. We ignore trellises where BB doesn't have 2 successors because for fewer than 2, it's trivial, and for 3 or greater they are very uncommon and complex to compute optimally. Allowing edges within S is not strictly a trellis, but the same algorithm works, so we allow it.</p>


<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### markBlockSuccessors() {#a7fa0e67ba11ea993bd3f047cb851220a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::markBlockSuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopHeaderBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decrease the UnscheduledPredecessors count for a single block, and if the count goes to 0, add them to the appropriate work list.</p>


<p>Mark a single block's successors as having one fewer preds.</p>


<p>Under normal circumstances, this is only called by markChainSuccessors, but if a block that was to be placed is completely tail-duplicated away, and was duplicated into the chain end, we need to redo markBlockSuccessors for just that block.</p>


<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### markChainSuccessors() {#a8609559711967b7ec0af133d7979c4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::markChainSuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopHeaderBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decrease the UnscheduledPredecessors count for all blocks in chain, and if the count goes to 0, add them to the appropriate work list.</p>


<p>Mark a chain's successors as having one fewer preds.</p>


<p>When a chain is being merged into the "placed" chain, this routine will quickly walk the successors of each block in the chain and mark them as having one fewer active predecessor. It also adds any successors of this chain which reach the zero-predecessor state to the appropriate worklist.</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### maybeTailDuplicateBlock() {#a7e211e03c3ab0d21b495345984eb1b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::maybeTailDuplicateBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LPred, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aaba82c71ffdca966cad10eae0992fff9">MachineFunction::iterator</a> &amp; PrevUnplacedBlockIt, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a813fd00ac7e5e3261ffe67f9322a5480">BlockFilterSet::iterator</a> &amp; PrevUnplacedBlockInFilterIt, bool &amp; DuplicatedToLPred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tail duplicate <span class="doxyComputerOutput">BB</span> into (some) predecessors if profitable.</p>


<p><span class="doxyComputerOutput">BB</span> - Basic block that may be duplicated <span class="doxyComputerOutput">LPred</span> - Chosen layout predecessor of <span class="doxyComputerOutput">BB</span> <span class="doxyComputerOutput">Chain</span> - Chain to which <span class="doxyComputerOutput">LPred</span> belongs, and <span class="doxyComputerOutput">BB</span> will belong. <span class="doxyComputerOutput">BlockFilter</span> - Set of blocks that belong to the loop being laid out. Used to identify which blocks to update predecessor counts. <span class="doxyComputerOutput">PrevUnplacedBlockIt</span> - Iterator pointing to the last block that was chosen in the given order due to unnatural CFG only needed if <span class="doxyComputerOutput">BB</span> is removed and <span class="doxyComputerOutput">PrevUnplacedBlockIt</span> pointed to <span class="doxyComputerOutput">BB</span>. <span class="doxyComputerOutput">DuplicatedToLPred</span> - True if the block was duplicated into LPred.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True if the block was duplicated into all preds and removed.</p></dd>
</dl>


<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### optimizeBranches() {#a45f862faa7617594bcb965034bbf4c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::optimizeBranches ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### precomputeTriangleChains() {#a9f9503d0622e93edb0a6ba39a1a83bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::precomputeTriangleChains ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find chains of triangles to tail-duplicate where a global analysis works, but a local analysis would not find them.</p>


<p>Find chains of triangles where we believe it would be profitable to tail-duplicate them all, but a local analysis would not find them.</p>


<p>There are 3 ways this can be profitable: 1) The post-dominators marked 50% are actually taken 55% (This shrinks with longer chains) 2) The chains are statically correlated. Branch probabilities have a very U-shaped distribution. [<a href="http://nrs.harvard.edu/urn-3:HUL.InstRepos:24015805">http://nrs.harvard.edu/urn-3:HUL.InstRepos:24015805</a>] If the branches in a chain are likely to be from the same side of the distribution as their predecessor, but are independent at runtime, this transformation is profitable. (Because the cost of being wrong is a small fixed cost, unlike the standard triangle layout where the cost of being wrong scales with the # of triangles.) 3) The chains are dynamically correlated. If the probability that a previous branch was taken positively influences whether the next branch will be taken We believe that 2 and 3 are common enough to justify the small margin in 1.</p>


<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### repeatedlyTailDuplicateBlock() {#a65ae9e4e255c09f00874e3defceaaf75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::repeatedlyTailDuplicateBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; LPred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopHeaderBB, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aaba82c71ffdca966cad10eae0992fff9">MachineFunction::iterator</a> &amp; PrevUnplacedBlockIt, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a813fd00ac7e5e3261ffe67f9322a5480">BlockFilterSet::iterator</a> &amp; PrevUnplacedBlockInFilterIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tail duplicate <span class="doxyComputerOutput">BB</span> into (some) predecessors if profitable, repeating if it was duplicated into its chain predecessor and removed.</p>


<p><span class="doxyComputerOutput">BB</span> - Basic block that may be duplicated.</p>


<p><span class="doxyComputerOutput">LPred</span> - Chosen layout predecessor of <span class="doxyComputerOutput">BB</span>. Updated to be the chain end if LPred is removed. <span class="doxyComputerOutput">Chain</span> - Chain to which <span class="doxyComputerOutput">LPred</span> belongs, and <span class="doxyComputerOutput">BB</span> will belong. <span class="doxyComputerOutput">BlockFilter</span> - Set of blocks that belong to the loop being laid out. Used to identify which blocks to update predecessor counts. <span class="doxyComputerOutput">PrevUnplacedBlockIt</span> - Iterator pointing to the last block that was chosen in the given order due to unnatural CFG only needed if <span class="doxyComputerOutput">BB</span> is removed and <span class="doxyComputerOutput">PrevUnplacedBlockIt</span> pointed to <span class="doxyComputerOutput">BB</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">BB</span> was removed.</p></dd>
</dl>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### rotateLoop() {#a9447fbcd903da1f7bca306c626f7b3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::rotateLoop (<a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; LoopChain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ExitingBB, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> ExitFreq, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to rotate an exiting block to the bottom of the loop.</p>


<p>Once we have built a chain, try to rotate it to line up the hot exit block with fallthrough out of the loop if doing so doesn't introduce unnecessary branches. For example, if the loop has fallthrough into its header and out of its bottom already, don't rotate it.</p>


<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### rotateLoopWithProfile() {#a48fba9be30449ffa8970bb8aa4edb2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockPlacement::rotateLoopWithProfile (<a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; LoopChain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to rotate a loop based on profile data to reduce branch cost.</p>


<p>With profile data, we can determine the cost in terms of missed fall through opportunities when rotating a loop chain and select the best rotation. Basically, there are three kinds of cost to consider for each rotation:</p>


<ol class="doxyList" type="1">
<li>The possibly missed fall through edge (if it exists) from BB out of the loop to the loop header.</li>
<li>The possibly missed fall through edges (if they exist) from the loop exits to BB out of the loop.</li>
<li>The missed fall through edge (if it exists) from the last BB to the first BB in the loop chain. Therefore, the cost for a given rotation is the sum of costs listed above. We select the best rotation with the smallest cost.</li>
</ol>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### scaleThreshold() {#a009bd7be185b0d28640c95a65d3015cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency MachineBlockPlacement::scaleThreshold (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scale the DupThreshold according to basic block size.</p>

<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### selectBestCandidateBlock() {#a3dbe168d7c61f38f4c3c8e68ddc68bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBlockPlacement::selectBestCandidateBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; WorkList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select the best block from a worklist.</p>


<p>This looks through the provided worklist as a list of candidate basic blocks and select the most profitable one to place. The definition of profitable only really makes sense in the context of a loop. This returns the most frequently visited block in the worklist, which in the case of a loop, is the one most desirable to be physically close to the rest of the loop body in order to improve i-cache behavior.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The best block found, or null if none are viable.</p></dd>
</dl>


<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### selectBestSuccessor() {#a3ed68a87de5a4e312f928382ee2d8a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockPlacement::BlockAndTailDupResult MachineBlockPlacement::selectBestSuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> * BlockFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select the best successor for a block.</p>


<p>This looks across all successors of a particular block and attempts to select the "best" one to be the layout successor. It only considers direct successors which also pass the block filter. It will attempt to avoid breaking CFG structure, but cave and break such structures in the case of very hot successor edges.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The best successor block found, or null if none are viable, along with a boolean indicating if tail duplication is necessary.</p></dd>
</dl>


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### shouldTailDuplicate() {#a7d6e3b50fb30841d4a19f267d7ba413a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockPlacement::shouldTailDuplicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if a block should be tail-duplicated to increase fallthrough opportunities.</p>


<p>Check if a block should be tail duplicated to increase fallthrough opportunities.</p>


<p><span class="doxyComputerOutput">BB</span> Block to check.</p>


<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TopFallThroughFreq() {#acea1eb87358ab0ae882000fdfa36feb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency MachineBlockPlacement::TopFallThroughFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Top, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">BlockFilterSet</a> &amp; LoopBlockSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlocksWithUnanalyzableExits {#ad3fc59ca71bf4817ece50eb678512a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineBasicBlock *, 4&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::BlocksWithUnanalyzableExits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of basic blocks that have terminators that cannot be fully analyzed.</p>


<p>These basic blocks cannot be re-ordered safely by <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement">MachineBlockPlacement</a>, and we must preserve physical layout of these blocks and their successors through the pass.</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### BlockToChain {#a73f0109902ee879fc0f2fb344a40ec60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, BlockChain *&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::BlockToChain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> wide <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> mapping.</p>


<p>This mapping allows efficiently moving from any given basic block to the <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> it participates in, if any. We use it to, among other things, allow implicitly defining edges between chains as the existing edges between basic blocks.</p>


<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### BlockWorkList {#aae3cba63507b6bbbb2a0132e16880431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 16&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::BlockWorkList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>work lists of blocks that are ready to be laid out</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ChainAllocator {#a409c5b3292089d63a3a8afc797f7853d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;BlockChain&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::ChainAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator and owner of <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> structures.</p>


<p>We build BlockChains lazily while processing the loop structure of a function. To reduce malloc traffic, we allocate them using this slab-like allocator, and destroy them after the pass completes. An important guarantee is that this allocator produces stable pointers to the chains.</p>


<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### ComputedEdges {#a787183229d5c3229b5084e4577e3083d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, BlockAndTailDupResult&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::ComputedEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Edges that have already been computed as optimal.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### DupThreshold {#ae11922d600fffe2c8358b1ab5746328d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::DupThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partial tail duplication threshold.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### EHPadWorkList {#a78e15aacb3f480ea24dcef7ee9bf2942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 16&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::EHPadWorkList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### F {#a441346b8c3a351fc729ba5322d76f650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::F = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MBFI {#ae4d3256c15bed44ceb54bd6d1e98eeac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MBFIWrapper&gt; anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the function-wide block frequency pass.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MBPI {#a1cafd878b0393094413d5314b7f5433f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MBPI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the branch probability pass.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MLI {#a9043c382d0cd4a27bb67f8d04f51f0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the loop info.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### MPDT {#aebd727768855e8c4d0aec1e56ef0276d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::MPDT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the post dominator tree.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### PassConfig {#a657470178bb8e218eff04adbf577e575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::PassConfig = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### PreferredLoopExit {#a2a50cdc995bbaf9976f47390525c799b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::PreferredLoopExit = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Preferred loop exit.</p>


<p>Member variable for convenience. It may be removed by duplication deep in the call stack.</p>


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### PSI {#a0bf36e76dddb06c1e1ffa7510b32f1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::PSI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TailDup {#a70a3df2e6483c164757dceb156788a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailDuplicator anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::TailDup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Duplicator used to duplicate tails during placement.</p>


<p>Placement decisions can open up new tail duplication opportunities, but since tail duplication affects placement decisions of later blocks, it must be done inline.</p>


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TailDupSize {#ace8891a946fba735052f70421f420e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::TailDupSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TII {#a6be7707838427e4d20b01d1888fd1950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the target's instruction info.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### TLI {#aff48bdcbafede2c75e4d99a4b8a62cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLoweringBase* anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the target's lowering info.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### UseProfileCount {#a581affb9c081f5fb1826892f66531871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::UseProfileCount = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True: use block profile count to compute tail duplication cost.</p>


<p>False: use block frequency to compute tail duplication cost.</p>


<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getBestNonConflictingEdges() {#a984864f0c5f4ecf52a87268c077969ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MachineBlockPlacement::WeightedEdge, MachineBlockPlacement::WeightedEdge &gt; MachineBlockPlacement::getBestNonConflictingEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; WeightedEdge, 8 &gt; &gt; Edges)</td>
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

<p>Get the best pair of non-conflicting edges.</p>


<p>Pick the highest total weight pair of edges that can both be laid out.</p>


<p>The edges in <span class="doxyComputerOutput">Edges</span>[0] are assumed to have a different destination than the edges in <span class="doxyComputerOutput">Edges</span>[1]. Simple counting shows that the best pair is either the individual highest weight edges to the 2 different destinations, or in case of a conflict, one of them should be replaced with a 2nd best edge.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4944db6b12999ee0713352c27e8125e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char MachineBlockPlacement::ID = 0</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="#ad7175334e09f55bf7b5fb08d9522449e">MachineBlockPlacement</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
