---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorydependenceresults
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemoryDependenceResults` Class

<p>Provides a lazy, caching interface for making common memory aliasing information queries, backed by LLVM's alias analysis passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemoryDependenceResults { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">llvm/Analysis/MemoryDependenceAnalysis.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb5d4e618ecf28ecd42ab6fab5a4245">NonLocalDepInfo</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepentry">NonLocalDepEntry</a> &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be442e59733488467093467f8042e33">LocalDepMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f064bcc104b6f8d4a0bb68399e5610">ValueIsLoadPair</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 1, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pair&lt;Value*, bool&gt; where the bool is true if the dependence is a read only dependence, false if read/write. <a href="#af8f064bcc104b6f8d4a0bb68399e5610">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f7a0fff3b6b76c1dec6d4e4267822ce">BBSkipFirstBlockPair</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 1, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pair is used when caching information for a block. <a href="#a7f7a0fff3b6b76c1dec6d4e4267822ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf9f5c1b3f477173cc7ac18fd07b45d">ReverseNonLocalDefsCacheTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7ec7e0ef71b031bbb984f7bc7ad9b3">CachedNonLocalPointerInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">ValueIsLoadPair</a>, NonLocalPointerInfo &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map stores the cached results of doing a pointer lookup at the bottom of a block. <a href="#abb7ec7e0ef71b031bbb984f7bc7ad9b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ae71583008cba7fca63f45bf0661ac">ReverseNonLocalPtrDepTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">ValueIsLoadPair</a>, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992eb97901d3a17517827f8605178de9">PerInstNLInfo</a> = std::pair&lt; <a href="#a1fb5d4e618ecf28ecd42ab6fab5a4245">NonLocalDepInfo</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the instruction we keep for each cached access that we have for an instruction. <a href="#a992eb97901d3a17517827f8605178de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a30dbc00fe21c152591fa9ca20a1958">NonLocalDepMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, PerInstNLInfo &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0119b05b7204f92cefe44b17d368fcf7">ReverseDepMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4265e52e81113f073c48269b3e8867c6">ClobberOffsetsMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, int32_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offsets to dependant clobber loads. <a href="#a4265e52e81113f073c48269b3e8867c6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d532144bcebb13e2fbe5db3dee77abf">MemoryDependenceResults</a> (AAResults &amp;AA, AssumptionCache &amp;AC, const TargetLibraryInfo &amp;TLI, DominatorTree &amp;DT, unsigned DefaultBlockScanLimit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb9a6afa20a9c40940f135b6a1cf59b">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation in the new PM. <a href="#afdb9a6afa20a9c40940f135b6a1cf59b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2685b1764b0730fb0ff4379700b9aba">getDefaultBlockScanLimit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some methods limit the number of instructions they will examine. <a href="#aa2685b1764b0730fb0ff4379700b9aba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c238ef927795521aeb232b467a6cd1">getDependency</a> (Instruction *QueryInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction on which a memory operation depends. <a href="#aa5c238ef927795521aeb232b467a6cd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1fb5d4e618ecf28ecd42ab6fab5a4245">NonLocalDepInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7240503037f0c0499222a41a5f22d06">getNonLocalCallDependency</a> (CallBase *QueryCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a full dependency query for the specified call, returning the set of blocks that the value is potentially live across. <a href="#aa7240503037f0c0499222a41a5f22d06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46fb372d99dc0562d09cfdcd041d5ab">getNonLocalPointerDependency</a> (Instruction *QueryInst, SmallVectorImpl&lt; NonLocalDepResult &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a full dependency query for an access to the QueryInst's specified memory location, returning the set of instructions that either define or clobber the value. <a href="#ab46fb372d99dc0562d09cfdcd041d5ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4082748189dc3460ea7130cd8d7790b5">removeInstruction</a> (Instruction *InstToRemove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes an instruction from the dependence analysis, updating the dependence of instructions that previously depended on it. <a href="#a4082748189dc3460ea7130cd8d7790b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a5826c1be70ba257e98f90ed73a6b7c">invalidateCachedPointerInfo</a> (Value *Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidates cached information about the specified pointer, because it may be too conservative in memdep. <a href="#a2a5826c1be70ba257e98f90ed73a6b7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278345b63e562031b41d6900c3e3bfb3">invalidateCachedPredecessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a> info. <a href="#a278345b63e562031b41d6900c3e3bfb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2f5f9e9837f7f9010c8a26cbd04f6f">getPointerDependencyFrom</a> (const MemoryLocation &amp;Loc, bool isLoad, BasicBlock::iterator ScanIt, BasicBlock *BB, Instruction *QueryInst=nullptr, unsigned *Limit=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction on which a memory location depends. <a href="#a2f2f5f9e9837f7f9010c8a26cbd04f6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3928622cecd7b474f1c959b50897fae4">getPointerDependencyFrom</a> (const MemoryLocation &amp;Loc, bool isLoad, BasicBlock::iterator ScanIt, BasicBlock *BB, Instruction *QueryInst, unsigned *Limit, BatchAAResults &amp;BatchAA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10168569b54ede5f3a15b05463db9495">getSimplePointerDependencyFrom</a> (const MemoryLocation &amp;MemLoc, bool isLoad, BasicBlock::iterator ScanIt, BasicBlock *BB, Instruction *QueryInst, unsigned *Limit, BatchAAResults &amp;BatchAA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ed5939e93e21552b452f5f82a73a38">getInvariantGroupPointerDependency</a> (LoadInst *LI, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This analysis looks for other loads and stores with invariant.group metadata and the same pointer operand. <a href="#a81ed5939e93e21552b452f5f82a73a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81aabf5a99fd1f67c2619a1386731d6">releaseMemory</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release memory in caches. <a href="#ae81aabf5a99fd1f67c2619a1386731d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b657f4fb63ca69608d191828f32ff01">getClobberOffset</a> (LoadInst *DepInst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the clobber offset to dependent instruction. <a href="#a3b657f4fb63ca69608d191828f32ff01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9979c3a0fa0b1f27ea8e830875bd08f">getCallDependencyFrom</a> (CallBase *Call, bool isReadOnlyCall, BasicBlock::iterator ScanIt, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private helper for finding the local dependencies of a call site. <a href="#ad9979c3a0fa0b1f27ea8e830875bd08f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f09518d625c6cf9b18c25476c120100">getNonLocalPointerDepFromBB</a> (Instruction *QueryInst, const PHITransAddr &amp;Pointer, const MemoryLocation &amp;Loc, bool isLoad, BasicBlock *BB, SmallVectorImpl&lt; NonLocalDepResult &gt; &amp;Result, SmallDenseMap&lt; BasicBlock *, Value *, 16 &gt; &amp;Visited, bool SkipFirstBlock=false, bool IsIncomplete=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a dependency query based on pointer/pointeesize starting at the end of StartBB. <a href="#a6f09518d625c6cf9b18c25476c120100">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad837f20e512ed064b21828071eca6ed7">getNonLocalInfoForBlock</a> (Instruction *QueryInst, const MemoryLocation &amp;Loc, bool isLoad, BasicBlock *BB, NonLocalDepInfo *Cache, unsigned NumSortedEntries, BatchAAResults &amp;BatchAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the memdep value for BB with Pointer/PointeeSize using either cached information in Cache or by doing a lookup (which may use dirty cache info if available). <a href="#ad837f20e512ed064b21828071eca6ed7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7eab4554aeae1406557302ccc42d95d">removeCachedNonLocalPointerDependencies</a> (ValueIsLoadPair P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If P exists in CachedNonLocalPointerInfo or NonLocalDefsCache, remove it. <a href="#ab7eab4554aeae1406557302ccc42d95d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9196fb37f3d6d59db110d6c720ed57f8">verifyRemoved</a> (Instruction *Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the specified instruction does not occur in our internal data structures. <a href="#a9196fb37f3d6d59db110d6c720ed57f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">LocalDepMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607dc55ef161d0171005584775b0bef2">LocalDeps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepresult">NonLocalDepResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7cd365ba3bb5dc42ce6edfaca44342f">NonLocalDefsCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache storing single nonlocal def for the instruction. <a href="#aa7cd365ba3bb5dc42ce6edfaca44342f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ReverseNonLocalDefsCacheTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b963913e363cd73ad03b6e1cef1783c">ReverseNonLocalDefsCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">CachedNonLocalPointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa27d4a18b855225cdcdf19d58c732f26">NonLocalPointerDeps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ReverseNonLocalPtrDepTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47989864934b9852000cc87419f2b6a1">ReverseNonLocalPtrDeps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">NonLocalDepMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461c2fb0d9b1e37af4d76dc65a6d2a2d">NonLocalDepsMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ReverseDepMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5efbbbb92817e1db3322733be6722d47">ReverseLocalDeps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ReverseDepMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33697948eb34123a34200a84b07d15f8">ReverseNonLocalDeps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54c80229f77a7729c4f49c6c6e3dab9">AA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> implementation, just a cache. <a href="#ab54c80229f77a7729c4f49c6c6e3dab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce9772a5933493fb943b4175240d06a">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4a0182d9e5bb041efa14ff8d1cc1af">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820bc308a1070473ab353dbe182c4b8f">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edb50f717fe067ed222058869b8ceb6">PredCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/earliestescapeanalysis">EarliestEscapeAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99c43a2f6e4c5add448b5269b9c15f1">EEA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bb3be4669cf6ee873897a7bdd6772a">DefaultBlockScanLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ClobberOffsetsMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa507d703998ed3afdfe891727f1656ed">ClobberOffsets</a></td>
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

<p>Provides a lazy, caching interface for making common memory aliasing information queries, backed by LLVM's alias analysis passes.</p>


<p>The dependency information returned is somewhat unusual, but is pragmatic. If queried about a store or call that might modify memory, the analysis will return the instruction[s] that may either load from that memory or store to it. If queried with a load or call that can never modify memory, the analysis will return calls and stores that might modify the pointer, but generally does not return loads unless a) they are volatile, or b) they load from <em>must-aliased</em> pointers. Returning a dependence on must-alias'd pointers instead of all pointers interacts well with the internal caching mechanism.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NonLocalDepInfo {#a1fb5d4e618ecf28ecd42ab6fab5a4245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::NonLocalDepInfo =  std::vector&lt;NonLocalDepEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BBSkipFirstBlockPair {#a7f7a0fff3b6b76c1dec6d4e4267822ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::BBSkipFirstBlockPair =  PointerIntPair&lt;BasicBlock *, 1, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This pair is used when caching information for a block.</p>


<p>If the pointer is null, the cache value is not a full query that starts at the specified block. If non-null, the bool indicates whether or not the contents of the block was skipped.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### CachedNonLocalPointerInfo {#abb7ec7e0ef71b031bbb984f7bc7ad9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::CachedNonLocalPointerInfo = 
      DenseMap&lt;ValueIsLoadPair, NonLocalPointerInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This map stores the cached results of doing a pointer lookup at the bottom of a block.</p>


<p>The key of this map is the pointer+isload bit, the value is a list of &lt;bb-&gt;result&gt; mappings.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ClobberOffsetsMapType {#a4265e52e81113f073c48269b3e8867c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::ClobberOffsetsMapType =  DenseMap&lt;LoadInst *, int32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offsets to dependant clobber loads.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### LocalDepMapType {#a2be442e59733488467093467f8042e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::LocalDepMapType =  DenseMap&lt;Instruction *, MemDepResult&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### NonLocalDepMapType {#a7a30dbc00fe21c152591fa9ca20a1958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::NonLocalDepMapType =  DenseMap&lt;Instruction *, PerInstNLInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### PerInstNLInfo {#a992eb97901d3a17517827f8605178de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::PerInstNLInfo =  std::pair&lt;NonLocalDepInfo, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the instruction we keep for each cached access that we have for an instruction.</p>


<p>The pointer is an owning pointer and the bool indicates whether we have any dirty bits in the set.</p>


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseDepMapType {#a0119b05b7204f92cefe44b17d368fcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::ReverseDepMapType = 
      DenseMap&lt;Instruction *, SmallPtrSet&lt;Instruction *, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseNonLocalDefsCacheTy {#a0cf9f5c1b3f477173cc7ac18fd07b45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::ReverseNonLocalDefsCacheTy = 
    DenseMap&lt;Instruction *, SmallPtrSet&lt;const Value*, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseNonLocalPtrDepTy {#a26ae71583008cba7fca63f45bf0661ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::ReverseNonLocalPtrDepTy = 
      DenseMap&lt;Instruction *, SmallPtrSet&lt;ValueIsLoadPair, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ValueIsLoadPair {#af8f064bcc104b6f8d4a0bb68399e5610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryDependenceResults::ValueIsLoadPair =  PointerIntPair&lt;const Value *, 1, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pair&lt;Value*, bool&gt; where the bool is true if the dependence is a read only dependence, false if read/write.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryDependenceResults() {#a2d532144bcebb13e2fbe5db3dee77abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryDependenceResults::MemoryDependenceResults (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, unsigned DefaultBlockScanLimit)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getClobberOffset() {#a3b657f4fb63ca69608d191828f32ff01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int32_t &gt; llvm::MemoryDependenceResults::getClobberOffset (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * DepInst)</td>
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

<p>Return the clobber offset to dependent instruction.</p>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### getDefaultBlockScanLimit() {#aa2685b1764b0730fb0ff4379700b9aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MemoryDependenceResults::getDefaultBlockScanLimit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some methods limit the number of instructions they will examine.</p>


<p>The return value of this method is the default limit that will be used if no limit is explicitly passed in.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a10168569b54ede5f3a15b05463db9495">getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getDependency() {#aa5c238ef927795521aeb232b467a6cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getDependency (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the instruction on which a memory operation depends.</p>


<p>See the class comment for more details. It is illegal to call this on non-memory instructions.</p>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#ae824fe970b941b6bafc9b41d65cb4799">llvm::MemDepResult::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#adfd696331e43abcbcf5060bf0cd506e4">llvm::MemDepResult::getNonFuncLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a465c166d520399ff2b114c8aac5e7f3d">llvm::MemDepResult::getNonLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a2f2f5f9e9837f7f9010c8a26cbd04f6f">getPointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a87800772e5bbce0b8e0cb23b54e47f58">llvm::MemDepResult::getUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a728f79528ca8659e15d00c1e6818b316">llvm::isModSet</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a90f6ea490b2dda15f00cf09a9c5cd98d">RemoveFromReverseMap</a>.</p>


<p>Referenced by <a href="#aa7240503037f0c0499222a41a5f22d06">getNonLocalCallDependency</a>.</p>

</div>
</div>

### getInvariantGroupPointerDependency() {#a81ed5939e93e21552b452f5f82a73a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getInvariantGroupPointerDependency (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This analysis looks for other loads and stores with invariant.group metadata and the same pointer operand.</p>


<p>Returns Unknown if it does not find anything, and Def if it can be assumed that 2 instructions load or store the same value and NonLocal which indicate that non-local Def was found, which can be retrieved by calling getNonLocalPointerDependency with the same queried instruction.</p>


<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#ae4760893fa2bd86ce4460d3171fb9a82">llvm::MemDepResult::getDef</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a465c166d520399ff2b114c8aac5e7f3d">llvm::MemDepResult::getNonLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54b19432f9c7d4df0f2f2307175f73e4">llvm::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a87800772e5bbce0b8e0cb23b54e47f58">llvm::MemDepResult::getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">llvm::Instruction::hasMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a3928622cecd7b474f1c959b50897fae4">getPointerDependencyFrom</a>.</p>

</div>
</div>

### getNonLocalCallDependency() {#aa7240503037f0c0499222a41a5f22d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemoryDependenceResults::NonLocalDepInfo &amp; MemoryDependenceResults::getNonLocalCallDependency (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * QueryCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a full dependency query for the specified call, returning the set of blocks that the value is potentially live across.</p>


<p>The returned set of results will include a "NonLocal" result for all blocks where the value is live across.</p>


<p>This method assumes the instruction returns a "NonLocal" dependency within its own block.</p>


<p>This returns a reference to an internal data structure that may be invalidated on the next non-local query or when an instruction is removed. Clients must copy this data if they want it around longer than that.</p>


<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#aac7d0e8a679e82bca022febc48796059">AssertSorted</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="#aa5c238ef927795521aeb232b467a6cd1">getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#ae824fe970b941b6bafc9b41d65cb4799">llvm::MemDepResult::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#adfd696331e43abcbcf5060bf0cd506e4">llvm::MemDepResult::getNonFuncLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a465c166d520399ff2b114c8aac5e7f3d">llvm::MemDepResult::getNonLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepentry/#ae7d7cd05b277b0ce27a6b56b94dae06f">llvm::NonLocalDepEntry::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a2b6159ef05223f67e8dd0a178377f06b">llvm::MemDepResult::isNonLocal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a90f6ea490b2dda15f00cf09a9c5cd98d">RemoveFromReverseMap</a>, <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepentry/#a35eb598d0afaa4a88efcddf50be97b74">llvm::NonLocalDepEntry::setResult</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### getNonLocalPointerDependency() {#ab46fb372d99dc0562d09cfdcd041d5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::getNonLocalPointerDependency (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepresult">NonLocalDepResult</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a full dependency query for an access to the QueryInst's specified memory location, returning the set of instructions that either define or clobber the value.</p>


<p>Warning: For a volatile query instruction, the dependencies will be accurate, and thus usable for reordering, but it is never legal to remove the query instruction.</p>


<p>This method assumes the pointer has a "NonLocal" dependency within QueryInst's parent basic block.</p>


<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a87800772e5bbce0b8e0cb23b54e47f58">llvm::MemDepResult::getUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#af21791a898355d83b502fd655b90e061">isOrdered</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a92599976668e8eec0d73b986ad3e7732">llvm::Instruction::isVolatile</a>.</p>

</div>
</div>

### getPointerDependencyFrom() {#a2f2f5f9e9837f7f9010c8a26cbd04f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getPointerDependencyFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool isLoad, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ScanIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst=nullptr, unsigned * Limit=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the instruction on which a memory location depends.</p>


<p>If isLoad is true, this routine ignores may-aliases with read-only operations. If isLoad is false, this routine ignores may-aliases with reads from read-only locations. If possible, pass the query instruction as well; this function may take advantage of the metadata annotated to the query instruction to refine the result. <span class="doxyComputerOutput">Limit</span> can be used to set the maximum number of instructions that will be examined to find the pointer dependency. On return, it will be set to the number of instructions left to examine. If a null pointer is passed in, the limit will default to the value of -memdep-block-scan-limit.</p>


<p>Note that this is an uncached query, and thus may be inefficient.</p>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="#a2f2f5f9e9837f7f9010c8a26cbd04f6f">getPointerDependencyFrom</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>.</p>


<p>Referenced by <a href="#aa5c238ef927795521aeb232b467a6cd1">getDependency</a> and <a href="#a2f2f5f9e9837f7f9010c8a26cbd04f6f">getPointerDependencyFrom</a>.</p>

</div>
</div>

### getPointerDependencyFrom() {#a3928622cecd7b474f1c959b50897fae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getPointerDependencyFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool isLoad, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ScanIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst, unsigned * Limit, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BatchAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a81ed5939e93e21552b452f5f82a73a38">getInvariantGroupPointerDependency</a>, <a href="#a10168569b54ede5f3a15b05463db9495">getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a87800772e5bbce0b8e0cb23b54e47f58">llvm::MemDepResult::getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a70bfd297fb0ed3a5fa0ef09b5a47b496">llvm::MemDepResult::isDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a2b6159ef05223f67e8dd0a178377f06b">llvm::MemDepResult::isNonLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#aad752ec517a6efc823355c1e2fc21abb">llvm::MemDepResult::isUnknown</a>.</p>

</div>
</div>

### getSimplePointerDependencyFrom() {#a10168569b54ede5f3a15b05463db9495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getSimplePointerDependencyFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; MemLoc, bool isLoad, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ScanIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst, unsigned * Limit, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BatchAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#a2afd85d1ce874e1dd6391c967101d3b8">llvm::BatchAAResults::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a49f776e0940cc5d63d17d85ff6dac257">llvm::MemoryLocation::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a6acfd94bce56e2812f8e5d7626dd9b8f">llvm::MemDepResult::getClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#ae4760893fa2bd86ce4460d3171fb9a82">llvm::MemDepResult::getDef</a>, <a href="#aa2685b1764b0730fb0ff4379700b9aba">getDefaultBlockScanLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#adfa0be41805b25d9577d6f15d148a0d7">llvm::BatchAAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#af2a774dba86bfeea3d8843822a974fe2">llvm::BatchAAResults::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#adfd696331e43abcbcf5060bf0cd506e4">llvm::MemDepResult::getNonFuncLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a465c166d520399ff2b114c8aac5e7f3d">llvm::MemDepResult::getNonLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a47f5c74e1b14ba4a61db057400644acc">llvm::Value::getPointerAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#a87800772e5bbce0b8e0cb23b54e47f58">llvm::MemDepResult::getUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a854abfc88bcd24e3878e2c9ab1f70fd3">llvm::isModOrRefSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a728f79528ca8659e15d00c1e6818b316">llvm::isModSet</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#ab9ba3a606a0299b684755f56b1d2f1c7">llvm::BatchAAResults::isMustAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a433468826ef20b5ddb53704fc38363fc">llvm::isNoAliasCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af21b12b7c8de1504a945c4c974e06bff">llvm::isStrongerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a1d3115b016cea5ab80926ecc5493b5">llvm::isStrongerThanUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a92599976668e8eec0d73b986ad3e7732">llvm::Instruction::isVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a9e724bc94de38c6ca77508f19c246c0c">llvm::AliasResult::PartialAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>


<p>Referenced by <a href="#a3928622cecd7b474f1c959b50897fae4">getPointerDependencyFrom</a>.</p>

</div>
</div>

### invalidate() {#afdb9a6afa20a9c40940f135b6a1cf59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDependenceResults::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation in the new PM.</p>

<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1748 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### invalidateCachedPointerInfo() {#a2a5826c1be70ba257e98f90ed73a6b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::invalidateCachedPointerInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidates cached information about the specified pointer, because it may be too conservative in memdep.</p>


<p>This is an optional call that can be used when the client detects an equivalence between the pointer and some other value and replaces the other value with ptr. This can make Ptr available in more places that cached info does not necessarily keep.</p>


<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### invalidateCachedPredecessors() {#a278345b63e562031b41d6900c3e3bfb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::invalidateCachedPredecessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clears the <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a> info.</p>


<p>This needs to be done when the CFG changes, e.g., due to splitting critical edges.</p>


<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1486 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>.</p>

</div>
</div>

### releaseMemory() {#ae81aabf5a99fd1f67c2619a1386731d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemoryDependenceResults::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release memory in caches.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### removeInstruction() {#a4082748189dc3460ea7130cd8d7790b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::removeInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InstToRemove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes an instruction from the dependence analysis, updating the dependence of instructions that previously depended on it.</p>

<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/memdepresult/#ae824fe970b941b6bafc9b41d65cb4799">llvm::MemDepResult::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a90f6ea490b2dda15f00cf09a9c5cd98d">RemoveFromReverseMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab7e8be1d1ae7e526ea156b60c51c10e5">llvm::FoldSingleEntryPHINodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getCallDependencyFrom() {#ad9979c3a0fa0b1f27ea8e830875bd08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getCallDependencyFrom (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, bool isReadOnlyCall, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ScanIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private helper for finding the local dependencies of a call site.</p>

<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getNonLocalInfoForBlock() {#ad837f20e512ed064b21828071eca6ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult MemoryDependenceResults::getNonLocalInfoForBlock (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool isLoad, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a1fb5d4e618ecf28ecd42ab6fab5a4245">NonLocalDepInfo</a> * Cache, unsigned NumSortedEntries, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BatchAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the memdep value for BB with Pointer/PointeeSize using either cached information in Cache or by doing a lookup (which may use dirty cache info if available).</p>


<p>If we do a lookup, add the result to the cache.</p>


<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getNonLocalPointerDepFromBB() {#a6f09518d625c6cf9b18c25476c120100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDependenceResults::getNonLocalPointerDepFromBB (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * QueryInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phitransaddr">PHITransAddr</a> &amp; Pointer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool isLoad, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * StartBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepresult">NonLocalDepResult</a> &gt; &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt; &amp; Visited, bool SkipFirstBlock=false, bool IsIncomplete=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a dependency query based on pointer/pointeesize starting at the end of StartBB.</p>


<p>Add any clobber/def results to the results vector and keep track of which blocks are visited in 'Visited'.</p>


<p>This has special behavior for the first block queries (when SkipFirstBlock is true). In this special case, it ignores the contents of the specified block and starts returning dependence info for its predecessors.</p>


<p>This function returns true on success, or false to indicate that it could not compute dependence information for some reason. This should be treated as a clobber dependence on the first instruction in the predecessor block.</p>


<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>

</div>
</div>

### removeCachedNonLocalPointerDependencies() {#ab7eab4554aeae1406557302ccc42d95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::removeCachedNonLocalPointerDependencies (<a href="/web-llvm/docs/api/classes/llvm/pointerintpair">ValueIsLoadPair</a> P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If P exists in CachedNonLocalPointerInfo or NonLocalDefsCache, remove it.</p>

<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>

</div>
</div>

### verifyRemoved() {#a9196fb37f3d6d59db110d6c720ed57f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDependenceResults::verifyRemoved (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the specified instruction does not occur in our internal data structures.</p>


<p>This function verifies by asserting in debug builds.</p>


<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>, definition at line 1662 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#ab54c80229f77a7729c4f49c6c6e3dab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; llvm::MemoryDependenceResults::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> implementation, just a cache.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### AC {#a7ce9772a5933493fb943b4175240d06a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; llvm::MemoryDependenceResults::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ClobberOffsets {#aa507d703998ed3afdfe891727f1656ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClobberOffsetsMapType llvm::MemoryDependenceResults::ClobberOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### DefaultBlockScanLimit {#a49bb3be4669cf6ee873897a7bdd6772a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryDependenceResults::DefaultBlockScanLimit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### DT {#a820bc308a1070473ab353dbe182c4b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::MemoryDependenceResults::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### EEA {#aa99c43a2f6e4c5add448b5269b9c15f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EarliestEscapeAnalysis llvm::MemoryDependenceResults::EEA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### LocalDeps {#a607dc55ef161d0171005584775b0bef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalDepMapType llvm::MemoryDependenceResults::LocalDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### NonLocalDefsCache {#aa7cd365ba3bb5dc42ce6edfaca44342f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;const Value&gt;, NonLocalDepResult&gt; llvm::MemoryDependenceResults::NonLocalDefsCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache storing single nonlocal def for the instruction.</p>


<p>It is set when nonlocal def would be found in function returning only local dependencies.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### NonLocalDepsMap {#a461c2fb0d9b1e37af4d76dc65a6d2a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonLocalDepMapType llvm::MemoryDependenceResults::NonLocalDepsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### NonLocalPointerDeps {#aa27d4a18b855225cdcdf19d58c732f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CachedNonLocalPointerInfo llvm::MemoryDependenceResults::NonLocalPointerDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### PredCache {#a3edb50f717fe067ed222058869b8ceb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredIteratorCache llvm::MemoryDependenceResults::PredCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseLocalDeps {#a5efbbbb92817e1db3322733be6722d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReverseDepMapType llvm::MemoryDependenceResults::ReverseLocalDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseNonLocalDefsCache {#a4b963913e363cd73ad03b6e1cef1783c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReverseNonLocalDefsCacheTy llvm::MemoryDependenceResults::ReverseNonLocalDefsCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseNonLocalDeps {#a33697948eb34123a34200a84b07d15f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReverseDepMapType llvm::MemoryDependenceResults::ReverseNonLocalDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### ReverseNonLocalPtrDeps {#a47989864934b9852000cc87419f2b6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReverseNonLocalPtrDepTy llvm::MemoryDependenceResults::ReverseNonLocalPtrDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### TLI {#a6f4a0182d9e5bb041efa14ff8d1cc1af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo&amp; llvm::MemoryDependenceResults::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp">MemoryDependenceAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
