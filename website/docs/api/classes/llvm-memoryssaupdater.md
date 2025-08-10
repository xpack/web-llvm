---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssaupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemorySSAUpdater` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSAUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">llvm/Analysis/MemorySSAUpdater.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e482c216b0c69891fc5ea7f090c77c1">MemorySSAUpdater</a> (MemorySSA *MSSA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fc5eae685ef3e2dce4403a75d5ff2f">insertDef</a> (MemoryDef *Def, bool RenameUses=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a definition into the <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> IR. <a href="#a21fc5eae685ef3e2dce4403a75d5ff2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab9d33dbeb44b5ba49ab27201e6bd76">insertUse</a> (MemoryUse *Use, bool RenameUses=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4953231268ee21e95c3740e51ab37a96">removeEdge</a> (BasicBlock *From, BasicBlock *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> in <span class="doxyComputerOutput">To</span> following an edge deletion between <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>. <a href="#a4953231268ee21e95c3740e51ab37a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95eeaea882b3c388420da771fe488bbc">removeDuplicatePhiEdgesBetween</a> (const BasicBlock *From, const BasicBlock *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> in <span class="doxyComputerOutput">To</span> to have a single incoming edge from <span class="doxyComputerOutput">From</span>, following a CFG change that replaced multiple edges (switch) with a direct branch. <a href="#a95eeaea882b3c388420da771fe488bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989bdd9e36b5327a04ad8db2a7014741">updatePhisWhenInsertingUniqueBackedgeBlock</a> (BasicBlock *LoopHeader, BasicBlock *LoopPreheader, BasicBlock *BackedgeBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> when inserting a unique backedge block for a loop. <a href="#a989bdd9e36b5327a04ad8db2a7014741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667d41d0d3b12af17ccc6c99e3d51e5b">updateForClonedLoop</a> (const LoopBlocksRPO &amp;LoopBlocks, ArrayRef&lt; BasicBlock * &gt; ExitBlocks, const ValueToValueMapTy &amp;VM, bool IgnoreIncomingWithNoClones=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> after a loop was cloned, given the blocks in RPO order, the exit blocks and a 1:1 mapping of all blocks and instructions cloned. <a href="#a667d41d0d3b12af17ccc6c99e3d51e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b4596999393cfa1b3c077caa0f2ca0">updateForClonedBlockIntoPred</a> (BasicBlock *BB, BasicBlock *P1, const ValueToValueMapTy &amp;VM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3964d6e7884c21d8118699062c91df">updateExitBlocksForClonedLoop</a> (ArrayRef&lt; BasicBlock * &gt; ExitBlocks, const ValueToValueMapTy &amp;VMap, DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update phi nodes in exit block successors following cloning. <a href="#aeb3964d6e7884c21d8118699062c91df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37bf24102618a2d55fa8ab1273dac87">updateExitBlocksForClonedLoop</a> (ArrayRef&lt; BasicBlock * &gt; ExitBlocks, ArrayRef&lt; std::unique_ptr&lt; ValueToValueMapTy &gt; &gt; VMaps, DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89ca302de455d3971f751c8d1a5bd58">applyUpdates</a> (ArrayRef&lt; CFGUpdate &gt; Updates, DominatorTree &amp;DT, bool UpdateDTFirst=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply CFG updates, analogous with the DT edge updates. <a href="#ad89ca302de455d3971f751c8d1a5bd58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0404328e9e4f5d3c565daabf46fffac">applyInsertUpdates</a> (ArrayRef&lt; CFGUpdate &gt; Updates, DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply CFG insert updates, analogous with the DT edge updates. <a href="#ac0404328e9e4f5d3c565daabf46fffac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58e16a1d7ebc8f202ae2f8037b42df6">moveBefore</a> (MemoryUseOrDef *What, MemoryUseOrDef *Where)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d537a2dd5afbd1eba9a402cda94e067">moveAfter</a> (MemoryUseOrDef *What, MemoryUseOrDef *Where)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26e0fb4a78dc439a03ac42c4ba6e674">moveToPlace</a> (MemoryUseOrDef *What, BasicBlock *BB, MemorySSA::InsertionPlace Where)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7518e6d6d74227a56b36eb88cfe26e6">moveAllAfterSpliceBlocks</a> (BasicBlock *From, BasicBlock *To, Instruction *Start)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">From</span> block was spliced into <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>. <a href="#aa7518e6d6d74227a56b36eb88cfe26e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11d36d6d1f06cdf18a0333eab22f381">moveAllAfterMergeBlocks</a> (BasicBlock *From, BasicBlock *To, Instruction *Start)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">From</span> block was merged into <span class="doxyComputerOutput">To</span>. <a href="#ae11d36d6d1f06cdf18a0333eab22f381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b63bcaa1f6638b608f911cd04341e2">wireOldPredecessorsToNewImmediatePredecessor</a> (BasicBlock *Old, BasicBlock *New, ArrayRef&lt; BasicBlock * &gt; Preds, bool IdenticalEdgesWereMerged=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A new empty <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> (New) now branches directly to Old. <a href="#ae6b63bcaa1f6638b608f911cd04341e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23ba05c48e8be4a29c36d83deba9146">createMemoryAccessInBB</a> (Instruction *I, MemoryAccess *Definition, const BasicBlock *BB, MemorySSA::InsertionPlace Point, bool CreationMustSucceed=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> at a specified point in a block. <a href="#ab23ba05c48e8be4a29c36d83deba9146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c21c2f4d41d5c6f6807992d60347bbd">createMemoryAccessBefore</a> (Instruction *I, MemoryAccess *Definition, MemoryUseOrDef *InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> before an existing <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>. <a href="#a1c21c2f4d41d5c6f6807992d60347bbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9a0bb25aae89d274ee9ae7dd0cf9b2">createMemoryAccessAfter</a> (Instruction *I, MemoryAccess *Definition, MemoryAccess *InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> after an existing <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>. <a href="#acf9a0bb25aae89d274ee9ae7dd0cf9b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf78af37d56a9b72a49c65428210758">removeMemoryAccess</a> (MemoryAccess *, bool OptimizePhis=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> from <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, including updating all definitions and uses. <a href="#abcf78af37d56a9b72a49c65428210758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef87bd57ab712a0403630d15fa4b22b1">removeMemoryAccess</a> (const Instruction *I, bool OptimizePhis=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> for a given instruction, if a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> exists. <a href="#aef87bd57ab712a0403630d15fa4b22b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c15073f16693ebc44c2410986cacec">removeBlocks</a> (const SmallSetVector&lt; BasicBlock *, 8 &gt; &amp;DeadBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all MemoryAcceses in a set of BasicBlocks about to be deleted. <a href="#aa0c15073f16693ebc44c2410986cacec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94cd9c4d5114d65e1cd802c23c080326">changeToUnreachable</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> I will be changed to an unreachable. <a href="#a94cd9c4d5114d65e1cd802c23c080326">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a350909e784d6fa43181a72de61529">getMemorySSA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get handle on <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>. <a href="#a01a350909e784d6fa43181a72de61529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class WhereType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82eaf626a82d702f178488928bec7ac5">moveTo</a> (MemoryUseOrDef *What, BasicBlock *BB, WhereType Where)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0807a4b0620fc5751d47a837b9644f8">moveAllAccesses</a> (BasicBlock *From, BasicBlock *To, Instruction *Start)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90928b62464543902606518cb0075cde">getPreviousDef</a> (MemoryAccess *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c6187146a37eb5a20853f8af57f120">getPreviousDefInBlock</a> (MemoryAccess *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1abb25c12bc099ce196be9fe37a332">getPreviousDefFromEnd</a> (BasicBlock *, DenseMap&lt; BasicBlock *, TrackingVH&lt; MemoryAccess &gt; &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc410c1612a6a2e01d49463ea7efb980">getPreviousDefRecursive</a> (BasicBlock *, DenseMap&lt; BasicBlock *, TrackingVH&lt; MemoryAccess &gt; &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d16b4de480725c1719afbbbf86b35b">recursePhi</a> (MemoryAccess *Phi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc470cb4c7d3d5f5ac1a6bdd0f37adf">tryRemoveTrivialPhi</a> (MemoryPhi *Phi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RangeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a401e5bf2c01433de9ff40c40c7513285">tryRemoveTrivialPhi</a> (MemoryPhi *Phi, RangeType &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add54bbb822619c068f73663829c3fcee">tryRemoveTrivialPhis</a> (ArrayRef&lt; WeakVH &gt; UpdatedPHIs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d3cef24536ed24b45c988605065618">fixupDefs</a> (const SmallVectorImpl&lt; WeakVH &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf386b3282c97b1015397634ffa262d">cloneUsesAndDefs</a> (BasicBlock *BB, BasicBlock *NewBB, const ValueToValueMapTy &amp;VMap, PhiToDefMap &amp;MPhiMap, function_ref&lt; bool(BasicBlock *)&gt; IsInClonedRegion, bool CloneWasSimplified=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone all uses and defs from BB to NewBB given a 1:1 map of all instructions and blocks cloned, and a map of <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> : Definition (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> Phi or Def). <a href="#acaf386b3282c97b1015397634ffa262d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Iter&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba24128851bc99406f6fc386f77f0ab3">privateUpdateExitBlocksForClonedLoop</a> (ArrayRef&lt; BasicBlock * &gt; ExitBlocks, Iter ValuesBegin, Iter ValuesEnd, DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf5b17d0ec6b99f1a35d572c16a06c8">applyInsertUpdates</a> (ArrayRef&lt; CFGUpdate &gt;, DominatorTree &amp;DT, const GraphDiff&lt; BasicBlock * &gt; *GD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647bf08692fa64309fa50454a5d43e40">MSSA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab448c38bbad34f54708530a14d0a44f1">InsertedPHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We use <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> rather than a costly deletion to deal with dangling pointers. <a href="#ab448c38bbad34f54708530a14d0a44f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b23dcba09de6c3382d0d5c47cbe1ed5">VisitedBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50ef08018bf1d4476a935f86df43b59">NonOptPhis</a></td>
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


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemorySSAUpdater() {#a9e482c216b0c69891fc5ea7f090c77c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSAUpdater::MemorySSAUpdater (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * MSSA)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyInsertUpdates() {#ac0404328e9e4f5d3c565daabf46fffac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::applyInsertUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad36a34c7861d9ae3601c3c818d43ca2f">CFGUpdate</a> &gt; Updates, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply CFG insert updates, analogous with the DT edge updates.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Reference <a href="#ac0404328e9e4f5d3c565daabf46fffac">applyInsertUpdates</a>.</p>


<p>Referenced by <a href="#ac0404328e9e4f5d3c565daabf46fffac">applyInsertUpdates</a>, <a href="#ad89ca302de455d3971f751c8d1a5bd58">applyUpdates</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### applyUpdates() {#ad89ca302de455d3971f751c8d1a5bd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::applyUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad36a34c7861d9ae3601c3c818d43ca2f">CFGUpdate</a> &gt; Updates, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, bool UpdateDTFirst=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply CFG updates, analogous with the DT edge updates.</p>


<p>By default, the DT is assumed to be already up to date. If UpdateDTFirst is true, first update the DT with the same updates.</p>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="#ac0404328e9e4f5d3c565daabf46fffac">applyInsertUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a470b5b573c7915fe13bd529b22c9adbc">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Delete</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a4953231268ee21e95c3740e51ab37a96">removeEdge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### changeToUnreachable() {#a94cd9c4d5114d65e1cd802c23c080326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::changeToUnreachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> I will be changed to an unreachable.</p>


<p>Remove all accesses in I's block that follow I (inclusive), and update the Phis in the blocks' successors.</p>


<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a95eeaea882b3c388420da771fe488bbc">removeDuplicatePhiEdgesBetween</a>, <a href="#abcf78af37d56a9b72a49c65428210758">removeMemoryAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>.</p>

</div>
</div>

### createMemoryAccessAfter() {#acf9a0bb25aae89d274ee9ae7dd0cf9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryUseOrDef * MemorySSAUpdater::createMemoryAccessAfter (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Definition, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> after an existing <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>.</p>


<p>See <a href="#ab23ba05c48e8be4a29c36d83deba9146">createMemoryAccessInBB()</a> for usage details.</p>


<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#af9653b051f47859d60d83527d0460e87">llvm::MemoryAccess::getIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a5e2cdb7da821f277764240569336bd07">anonymous{DeadStoreElimination.cpp}::DSEState::tryFoldIntoCalloc</a>.</p>

</div>
</div>

### createMemoryAccessBefore() {#a1c21c2f4d41d5c6f6807992d60347bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryUseOrDef * MemorySSAUpdater::createMemoryAccessBefore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Definition, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> before an existing <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>.</p>


<p>See <a href="#ab23ba05c48e8be4a29c36d83deba9146">createMemoryAccessInBB()</a> for usage details.</p>


<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#af9653b051f47859d60d83527d0460e87">llvm::MemoryAccess::getIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### createMemoryAccessInBB() {#ab23ba05c48e8be4a29c36d83deba9146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::createMemoryAccessInBB (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Definition, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5">MemorySSA::InsertionPlace</a> Point, bool CreationMustSucceed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> at a specified point in a block.</p>


<p>When used by itself, this method will only insert the new <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> into the access list, but not make any other changes, such as inserting MemoryPHI nodes, or updating users to point to the new <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>. You must specify a correct Definition in this case.</p>


<p>Usually, this API is instead combined with <a href="#a9ab9d33dbeb44b5ba49ab27201e6bd76">insertUse()</a> or <a href="#a21fc5eae685ef3e2dce4403a75d5ff2f">insertDef()</a>, which will perform all the necessary MSSA updates. If these APIs are used, then nullptr can be used as Definition, as the correct defining access will be automatically determined.</p>


<p>Note: If a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> already exists for I, this function will make it inaccessible and it <em>must</em> have removeMemoryAccess called on it.</p>


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1414 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>.</p>

</div>
</div>

### getMemorySSA() {#a01a350909e784d6fa43181a72de61529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA * llvm::MemorySSAUpdater::getMemorySSA ()</td>
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

<p>Get handle on <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-licm-cpp-/#af11bb20a72885fc6999bfbcb21bd39fe">anonymous{LICM.cpp}::isOnlyMemoryAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-licm-cpp-/#a9d7f9cdd2e085f1453ac2f3186255fdc">anonymous{LICM.cpp}::isReadOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad30fb60072e2996200ea591628e33c5a">llvm::sinkRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### insertDef() {#a21fc5eae685ef3e2dce4403a75d5ff2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::insertDef (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * Def, bool RenameUses=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a definition into the <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> IR.</p>


<p>RenameUses will rename any use below the new def block (and any inserted phis). RenameUses should be set to true if the definition may cause new aliases for loads below it. This is not the case for hoisting or sinking or other forms of code <em>movement</em>. It <em>is</em> the case for straight code insertion. For example: store a if (foo) { } load a</p>


<p>Moving the store into the if block, and calling insertDef, does not require RenameUses. However, changing it to: store a if (foo) { store b } load a Where a mayalias b, <em>does</em> require RenameUses be set to true.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7e8dad1701aa6445be4a29f654b0473c">llvm::Value::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a9180c82ceffac7e5586cc2d6f368f996">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setDefiningBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afd7c135e18f2d7253d4f8545cd7b1756">llvm::SmallSet&lt; T, N, C &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a5e2cdb7da821f277764240569336bd07">anonymous{DeadStoreElimination.cpp}::DSEState::tryFoldIntoCalloc</a>.</p>

</div>
</div>

### insertUse() {#a9ab9d33dbeb44b5ba49ab27201e6bd76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::insertUse (<a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a> * Use, bool RenameUses=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>.</p>

</div>
</div>

### moveAfter() {#a2d537a2dd5afbd1eba9a402cda94e067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * What, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * Where)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#af9653b051f47859d60d83527d0460e87">llvm::MemoryAccess::getIterator</a>.</p>

</div>
</div>

### moveAllAfterMergeBlocks() {#ae11d36d6d1f06cdf18a0333eab22f381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveAllAfterMergeBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Start)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">From</span> block was merged into <span class="doxyComputerOutput">To</span>.</p>


<p>There is a CFG edge from <span class="doxyComputerOutput">To</span> to <span class="doxyComputerOutput">From</span>.<span class="doxyComputerOutput">To</span> still branches to <span class="doxyComputerOutput">From</span>, but all instructions were moved and <span class="doxyComputerOutput">From</span> is now an empty block; <span class="doxyComputerOutput">From</span> is about to be deleted. Move all accesses from <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">To</span> starting at instruction <span class="doxyComputerOutput">Start</span>. <span class="doxyComputerOutput">To</span> may have multiple successors, <span class="doxyComputerOutput">From</span> has a single predecessor. <span class="doxyComputerOutput">From</span> may have successors with MPhi nodes, replace their incoming block with <span class="doxyComputerOutput">To</span>. |---—| |---—|</p>


<table class="doxyTable">
<tr>
<th>To</th>
<th></th>
<th>To</th>
</tr>
<tr>
<td></td>
<td>=&gt;</td>
<td></td>
</tr>
</table>

<p>\/ | | |---—| | | &lt;- Start | From | | | |---—| |---—|</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a74aa9daea070e2ad3394a3ec58b7316a">llvm::BasicBlock::getUniquePredecessor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>.</p>

</div>
</div>

### moveAllAfterSpliceBlocks() {#aa7518e6d6d74227a56b36eb88cfe26e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveAllAfterSpliceBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Start)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">From</span> block was spliced into <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>.</p>


<p>There is a CFG edge from <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">To</span>. Move all accesses from <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">To</span> starting at instruction <span class="doxyComputerOutput">Start</span>. <span class="doxyComputerOutput">To</span> is newly created BB, so empty of MemorySSA::MemoryAccesses. Edges are already updated, so successors of <span class="doxyComputerOutput">To</span> with MPhi nodes need to update incoming block. |---—| |---—|</p>


<table class="doxyTable">
<tr>
<th>From</th>
<th></th>
<th>From</th>
</tr>
<tr>
<td></td>
<td colspan="2"></td>
</tr>
</table>

<p>| | =&gt; \/ | | |---—| &lt;- Start | | | To | |---—| |---—|</p>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>.</p>

</div>
</div>

### moveBefore() {#af58e16a1d7ebc8f202ae2f8037b42df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * What, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * Where)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#af9653b051f47859d60d83527d0460e87">llvm::MemoryAccess::getIterator</a>.</p>


<p>Referenced by <a href="#ae26e0fb4a78dc439a03ac42c4ba6e674">moveToPlace</a>.</p>

</div>
</div>

### moveToPlace() {#ae26e0fb4a78dc439a03ac42c4ba6e674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveToPlace (<a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * What, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5">MemorySSA::InsertionPlace</a> Where)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5a7806c120eb87aea9fbb52fed327e09de">llvm::MemorySSA::BeforeTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5a542e7b754a1b868794fa2f47256a1d97">llvm::MemorySSA::End</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a> and <a href="#af58e16a1d7ebc8f202ae2f8037b42df6">moveBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>.</p>

</div>
</div>

### removeBlocks() {#aa0c15073f16693ebc44c2410986cacec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::removeBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt; &amp; DeadBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all MemoryAcceses in a set of BasicBlocks about to be deleted.</p>


<p>Assumption we make here: all uses of deleted defs and phi must either occur in blocks about to be deleted (thus will be deleted as well), or they occur in phis that will simply lose an incoming value. Deleted blocks still have successor info, but their predecessor edges and Phi nodes may already be updated. Instructions in DeadBlocks should be deleted after this call.</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>.</p>

</div>
</div>

### removeDuplicatePhiEdgesBetween() {#a95eeaea882b3c388420da771fe488bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::removeDuplicatePhiEdgesBetween (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> in <span class="doxyComputerOutput">To</span> to have a single incoming edge from <span class="doxyComputerOutput">From</span>, following a CFG change that replaced multiple edges (switch) with a direct branch.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#a94cd9c4d5114d65e1cd802c23c080326">changeToUnreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### removeEdge() {#a4953231268ee21e95c3740e51ab37a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::removeEdge (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> in <span class="doxyComputerOutput">To</span> following an edge deletion between <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>.</p>


<p>If <span class="doxyComputerOutput">To</span> becomes unreachable, a call to removeBlocks should be made.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Referenced by <a href="#ad89ca302de455d3971f751c8d1a5bd58">applyUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### removeMemoryAccess() {#abcf78af37d56a9b72a49c65428210758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::removeMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, bool OptimizePhis=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> from <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, including updating all definitions and uses.</p>


<p>This should be called when a memory instruction that has a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> associated with it is erased from the program. For example, if a store or load is simply erased (not replaced), removeMemoryAccess should be called on the <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> for that store/load.</p>


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a9c50882381abd28ec385bec769b8928b">llvm::SetVector&lt; T, Vector, Set, N &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a889cc0df630d4b01e12d359517e26670">llvm::SetVector&lt; T, Vector, Set, N &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab978072498608d7bd344804926c2a91a">llvm::Value::hasValueHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#af38807ff8788bf371c9e216dd5ac6206">onlySingleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a413abcab8dbc3900fc2fde96a5d8fca6">llvm::Value::use_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#abb87e6d5ed7ded2ccd8acac49caf22ab">llvm::ValueHandleBase::ValueIsRAUWd</a>.</p>


<p>Referenced by <a href="#a94cd9c4d5114d65e1cd802c23c080326">changeToUnreachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-guardwidening-cpp-/#a6d418914e8b20f42ccd313fd4f1f2585">anonymous{GuardWidening.cpp}::eliminateGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#ab0cfc793d55940eac67854827dd365e9">eraseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1de454f8f11d343f01bde5f057af057e">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="#aef87bd57ab712a0403630d15fa4b22b1">removeMemoryAccess</a> and <a href="#a667d41d0d3b12af17ccc6c99e3d51e5b">updateForClonedLoop</a>.</p>

</div>
</div>

### removeMemoryAccess() {#aef87bd57ab712a0403630d15fa4b22b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemorySSAUpdater::removeMemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool OptimizePhis=false)</td>
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

<p>Remove <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> for a given instruction, if a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> exists.</p>


<p>This should be called when an instruction (load/store) is deleted from the program.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#abcf78af37d56a9b72a49c65428210758">removeMemoryAccess</a>.</p>

</div>
</div>

### updateExitBlocksForClonedLoop() {#aeb3964d6e7884c21d8118699062c91df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::updateExitBlocksForClonedLoop (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update phi nodes in exit block successors following cloning.</p>


<p>Exit blocks that were not cloned don't have additional predecessors added.</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### updateExitBlocksForClonedLoop() {#ae37bf24102618a2d55fa8ab1273dac87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::updateExitBlocksForClonedLoop (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &gt; &gt; VMaps, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### updateForClonedBlockIntoPred() {#ad7b4596999393cfa1b3c077caa0f2ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::updateForClonedBlockIntoPred (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * P1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### updateForClonedLoop() {#a667d41d0d3b12af17ccc6c99e3d51e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::updateForClonedLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopblocksrpo">LoopBlocksRPO</a> &amp; LoopBlocks, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VM, bool IgnoreIncomingWithNoClones=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> after a loop was cloned, given the blocks in RPO order, the exit blocks and a 1:1 mapping of all blocks and instructions cloned.</p>


<p>This involves duplicating all defs and uses in the cloned blocks Updating phi nodes in exit block successors is done separately.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#afebe38e4f4ade382a8e857b27cd990a2">llvm::SetVector&lt; T, Vector, Set, N &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#ac59d7eb34d6eb5a384a90489cd5dc7bc">getNewDefiningAccessForClone</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#af38807ff8788bf371c9e216dd5ac6206">onlySingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e549d97549636a7f08779d5cd98540">llvm::pred_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2103c335fa6ab933312c3871c82b0106">llvm::pred_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a7a59feca56f2ecfe5c74d6c04b0c45c7">ProcessBlock</a> and <a href="#abcf78af37d56a9b72a49c65428210758">removeMemoryAccess</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### updatePhisWhenInsertingUniqueBackedgeBlock() {#a989bdd9e36b5327a04ad8db2a7014741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::updatePhisWhenInsertingUniqueBackedgeBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopHeader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopPreheader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BackedgeBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> when inserting a unique backedge block for a loop.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>.</p>

</div>
</div>

### wireOldPredecessorsToNewImmediatePredecessor() {#ae6b63bcaa1f6638b608f911cd04341e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; Preds, bool IdenticalEdgesWereMerged=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A new empty <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> (New) now branches directly to Old.</p>


<p>Some of Old's predecessors (Preds) are now branching to New instead of Old. If New is the only predecessor, move Old's Phi, if present, to New. Otherwise, add a new Phi in New with appropriate incoming values, and update the incoming values in Old's Phi node too, if present.</p>


<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ab9945ed381faa9dbee65a92e6225768d">llvm::MemoryPhi::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5ad02ebd2ab52855a8e9fb8082c9530085">llvm::MemorySSA::Beginning</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a526630ff85b48f29ac5b4c519c6c2243">llvm::BasicBlock::hasNPredecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f211484edf604716a6c80030b0a0375">llvm::pred_size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyInsertUpdates() {#a3bf5b17d0ec6b99f1a35d572c16a06c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::applyInsertUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad36a34c7861d9ae3601c3c818d43ca2f">CFGUpdate</a> &gt; Updates, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; * GD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### cloneUsesAndDefs() {#acaf386b3282c97b1015397634ffa262d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::cloneUsesAndDefs (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/namespaces/llvm/#a14697ded10a20f6938ae56ed208f0913">PhiToDefMap</a> &amp; MPhiMap, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt; IsInClonedRegion, bool CloneWasSimplified=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone all uses and defs from BB to NewBB given a 1:1 map of all instructions and blocks cloned, and a map of <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> : Definition (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> Phi or Def).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VMap</td>
<td class="doxyParamItemDescription"><p>Maps old instructions to cloned instructions and old blocks to cloned blocks</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MPhiMap, is</td>
<td class="doxyParamItemDescription"><p>created in the caller of this private method, and maps existing MemoryPhis to new definitions that new MemoryAccesses must point to. These definitions may not necessarily be MemoryPhis themselves, they may be MemoryDefs. As such, the map is between MemoryPhis and MemoryAccesses, where the MemoryAccesses may be MemoryPhis or MemoryDefs and not MemoryUses.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsInClonedRegion</td>
<td class="doxyParamItemDescription"><p>Determines whether a basic block was cloned. References to accesses outside the cloned region will not be remapped.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CloneWasSimplified</td>
<td class="doxyParamItemDescription"><p>If false, the clone was exact. Otherwise, assume that the clone involved simplifications that may have: (1) turned a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a> into an instruction that <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> has no representation for, or (2) turned a <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> into a <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a> or an instruction that <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> has no representation for. No other cases are supported.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### fixupDefs() {#aa7d3cef24536ed24b45c988605065618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::fixupDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &gt; &amp; Vars)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### getPreviousDef() {#a90928b62464543902606518cb0075cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::getPreviousDef (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### getPreviousDefFromEnd() {#a6f1abb25c12bc099ce196be9fe37a332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::getPreviousDefFromEnd (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> &gt; &gt; &amp; CachedPreviousDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### getPreviousDefInBlock() {#a89c6187146a37eb5a20853f8af57f120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::getPreviousDefInBlock (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### getPreviousDefRecursive() {#afc410c1612a6a2e01d49463ea7efb980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::getPreviousDefRecursive (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> &gt; &gt; &amp; CachedPreviousDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### moveAllAccesses() {#aa0807a4b0620fc5751d47a837b9644f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveAllAccesses (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Start)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### moveTo() {#a82eaf626a82d702f178488928bec7ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class WhereType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::moveTo (<a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * What, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, WhereType Where)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### privateUpdateExitBlocksForClonedLoop() {#aba24128851bc99406f6fc386f77f0ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Iter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::privateUpdateExitBlocksForClonedLoop (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; ExitBlocks, Iter ValuesBegin, Iter ValuesEnd, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### recursePhi() {#af2d16b4de480725c1719afbbbf86b35b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::recursePhi (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### tryRemoveTrivialPhi() {#afcc470cb4c7d3d5f5ac1a6bdd0f37adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::tryRemoveTrivialPhi (<a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### tryRemoveTrivialPhi() {#a401e5bf2c01433de9ff40c40c7513285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RangeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSAUpdater::tryRemoveTrivialPhi (<a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> * Phi, RangeType &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

### tryRemoveTrivialPhis() {#add54bbb822619c068f73663829c3fcee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSAUpdater::tryRemoveTrivialPhis (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &gt; UpdatedPHIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>, definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InsertedPHIs {#ab448c38bbad34f54708530a14d0a44f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WeakVH, 16&gt; llvm::MemorySSAUpdater::InsertedPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We use <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> rather than a costly deletion to deal with dangling pointers.</p>


<p>MemoryPhis are created eagerly and sometimes get zapped shortly afterwards.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>

</div>
</div>

### MSSA {#a647bf08692fa64309fa50454a5d43e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* llvm::MemorySSAUpdater::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>

</div>
</div>

### NonOptPhis {#ad50ef08018bf1d4476a935f86df43b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;AssertingVH&lt;MemoryPhi&gt;, 8&gt; llvm::MemorySSAUpdater::NonOptPhis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>

</div>
</div>

### VisitedBlocks {#a8b23dcba09de6c3382d0d5c47cbe1ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 8&gt; llvm::MemorySSAUpdater::VisitedBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">MemorySSAUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp">MemorySSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
