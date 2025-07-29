---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-deadstoreelimination-cpp-/dsestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DSEState` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{DeadStoreElimination.cpp}::DSEState { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4379cc88c3ee5e87f0dd0e43f8b037">DSEState</a> (const DSEState &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> (Function &amp;F, AliasAnalysis &amp;AA, MemorySSA &amp;MSSA, DominatorTree &amp;DT, PostDominatorTree &amp;PDT, const TargetLibraryInfo &amp;TLI, const LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate">DSEState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9a9e4bc63b4f1c3b0e20bfb5e2be21">operator=</a> (const DSEState &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa3589bcd74d9f4a9131af14ccd5a430">strengthenLocationSize</a> (const Instruction *I, LocationSize Size) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173">OverwriteResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a> (const Instruction *KillingI, const Instruction *DeadI, const MemoryLocation &amp;KillingLoc, const MemoryLocation &amp;DeadLoc, int64_t &amp;KillingOff, int64_t &amp;DeadOff)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return 'OW_Complete' if a store to the 'KillingLoc' location (by <span class="doxyComputerOutput">KillingI</span> instruction) completely overwrites a store to the 'DeadLoc' location (by <span class="doxyComputerOutput">DeadI</span> instruction). <a href="#ad2005ee17b5b6cb575257dc12793a077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad7610d15181c1efbcaa192efb34430">isInvisibleToCallerAfterRet</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a> (Instruction *I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, bool &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a> (Instruction *I, bool ConsiderInitializesAttr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming this instruction has a dead analyzable write, can we delete this instruction? <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3544d6fc5a304b516d34fb76461b345e">isCompleteOverwrite</a> (const MemoryLocation &amp;DefLoc, Instruction *DefInst, Instruction *UseInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">UseInst</span> completely overwrites <span class="doxyComputerOutput">DefLoc</span> (stored by <span class="doxyComputerOutput">DefInst</span>). <a href="#a3544d6fc5a304b516d34fb76461b345e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb76849763054986dcdd4f2f41d369e">isWriteAtEndOfFunction</a> (MemoryDef *Def, const MemoryLocation &amp;DefLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Def</span> is not read before returning from the function. <a href="#a5eb76849763054986dcdd4f2f41d369e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a51eb63abe756612f5b8765cfe4e2a">getLocForTerminator</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">I</span> is a memory terminator like llvm.lifetime.end or free, return a pair with the <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> terminated by <span class="doxyComputerOutput">I</span> and a boolean flag indicating whether <span class="doxyComputerOutput">I</span> is a free-like call. <a href="#ad1a51eb63abe756612f5b8765cfe4e2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac1334eaea5f705c77ad5fc431333f8">isMemTerminatorInst</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory terminator instruction like llvm.lifetime.end or free. <a href="#a5ac1334eaea5f705c77ad5fc431333f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282a917fb3815ffbd1d1f4dc9974d843">isMemTerminator</a> (const MemoryLocation &amp;Loc, Instruction *AccessI, Instruction *MaybeTerm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">MaybeTerm</span> is a memory terminator for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> from instruction <span class="doxyComputerOutput">AccessI</span>. <a href="#a282a917fb3815ffbd1d1f4dc9974d843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3a865fee609f58bb1a914b69afe20f">isReadClobber</a> (const MemoryLocation &amp;DefLoc, Instruction *UseInst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a> (const Instruction *Current, const Instruction *KillingDef, const MemoryLocation &amp;CurrentLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a dependency between <span class="doxyComputerOutput">Current</span> and <span class="doxyComputerOutput">KillingDef</span> is guaranteed to be loop invariant for the loops that they are in. <a href="#a870a4918277d840461917023a42f1d57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a> (const Value *Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Ptr</span> is guaranteed to be loop invariant for any possible loop. <a href="#a55232923939cd416fa4b1d1aad06cd2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a> (MemoryDef *KillingDef, MemoryAccess *StartAccess, const MemoryLocation &amp;KillingLoc, const Value *KillingUndObj, unsigned &amp;ScanLimit, unsigned &amp;WalkerStepLimit, bool IsMemTerm, unsigned &amp;PartialLimit, bool IsInitializesAttrMemLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a> (Instruction *SI, SmallPtrSetImpl&lt; MemoryAccess * &gt; *Deleted=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete dead memory defs and recursively add their operands to ToRemove if they became dead. <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0ccb39ca68a8679460a7bd49678c88">mayThrowBetween</a> (Instruction *KillingI, Instruction *DeadI, const Value *KillingUndObj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1806b14f4d7a63958af99758745046e2">isDSEBarrier</a> (const Value *KillingUndObj, Instruction *DeadI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate writes to objects that are not visible in the caller and are not accessed before returning from the function. <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a> (MemoryDef *Def, const Value *DefUO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have a zero initializing memset following a call to malloc, try folding it into a call to calloc. <a href="#a5e2cdb7da821f277764240569336bd07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae046f3782a1242c97fe9fe937793fa3f">dominatingConditionImpliesValue</a> (MemoryDef *Def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a> (MemoryDef *Def, const Value *DefUO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afceb7703f48842eea9acf024ce0bd865">removePartiallyOverlappedStores</a> (InstOverlapIntervalsTy &amp;IOL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminates writes to locations where the value that is being written is already stored at the same location. <a href="#a73ef5ac7d0abd594af4c190baa6515a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58d526e759487737de52702abf2b7c5">getInitializesArgMemLoc</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a> (const MemoryLocationWrapper &amp;KillingLocWrapper)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341c9b08b6693494d83c9a28aae1d3a8">eliminateDeadDefs</a> (const MemoryDefWrapper &amp;KillingDefWrapper)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2ae8a14a4be9361bcce760c89d2eac">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa794cce8f9f5e3d955bec921152a6c17">AA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4d21540d7bb0e9c694b2fad0ae8d1b">EA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The single BatchAA instance that is used to cache AA queries. <a href="#a5495504ab8eb253e69a94261f275cd15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670428895b6bf9c32a8960747b25decc">PDT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6801022c51a18914c49e3ecf8d139b3">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7b15819b7223fc2f19b3708372de1d">ContainsIrreducibleLoops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> *, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2553a2f977ad3f44aa1fbfd250b409">MemDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cc54791481863d6a63992f0bdc7b5f">SkipStores</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35726fe54d4ed5d882902b2915de71df">CapturedBeforeReturn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f82a6d5fab81ea329c99054aef113a0">InvisibleToCallerAfterRet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add68fc1b146794ec3ade9cee80aa34b0">ThrowingBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c6b1abd4690a7185fa71371a4e523e">PostOrderNumbers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7e1af7835f27dc4a15c94320884797e9">InstOverlapIntervalsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92b91b957cb57f2dfdc5dadc62ed3c9">IOLs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of instructions (partly) overlapping with killing MemoryDefs per basic block. <a href="#ad92b91b957cb57f2dfdc5dadc62ed3c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c41d3a5e832d85f16db3fb43b729b0">AnyUnreachableExit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5389ad8a0692df0ac580907f82703d2">ShouldIterateEndOfFunctionDSE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae042e649168834e60114a0d11320bcd0">ToRemove</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dead instructions to be removed at the end of DSE. <a href="#ae042e649168834e60114a0d11320bcd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50c0551a73d70d5bd769557bdbec3d7">pushMemUses</a> (MemoryAccess *Acc, SmallVectorImpl&lt; MemoryAccess * &gt; &amp;WorkList, SmallPtrSetImpl&lt; MemoryAccess * &gt; &amp;Visited)</td>
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


<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DSEState() {#a7d4379cc88c3ee5e87f0dd0e43f8b037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DeadStoreElimination.cpp}::DSEState::DSEState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate">DSEState</a> &amp;)</td>
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



<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Reference <a href="#a7d4379cc88c3ee5e87f0dd0e43f8b037">DSEState</a>.</p>


<p>Referenced by <a href="#a7d4379cc88c3ee5e87f0dd0e43f8b037">DSEState</a> and <a href="#a3f9a9e4bc63b4f1c3b0e20bfb5e2be21">operator=</a>.</p>

</div>
</div>

### DSEState() {#aa1d21b1024d9925b46d10fcd11e0483c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DeadStoreElimination.cpp}::DSEState::DSEState (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> &amp; MSSA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#aa794cce8f9f5e3d955bec921152a6c17">AA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#ae1c41d3a5e832d85f16db3fb43b729b0">AnyUnreachableExit</a>, <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="#acc7b15819b7223fc2f19b3708372de1d">ContainsIrreducibleLoops</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a9a4d21540d7bb0e9c694b2fad0ae8d1b">EA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a1248cac6839081d01f783c52127c5dd0">EnableInitializesImprovement</a>, <a href="#acd2ae8a14a4be9361bcce760c89d2eac">F</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#a4f3e2c0f6369d8d9bd65a1f7c16f2f52">anonymous{DeadStoreElimination.cpp}::hasInitializesAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a4f82a6d5fab81ea329c99054aef113a0">InvisibleToCallerAfterRet</a>, <a href="#a5ac1334eaea5f705c77ad5fc431333f8">isMemTerminatorInst</a>, <a href="#ab6801022c51a18914c49e3ecf8d139b3">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add8cf45ebe45732b4baff48cb3a8d435">llvm::mayContainIrreducibleControl</a>, <a href="#a7f2553a2f977ad3f44aa1fbfd250b409">MemDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a50cb26889f6560627ffe4cfe17044a65">MemorySSADefsPerBlockLimit</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="#a670428895b6bf9c32a8960747b25decc">PDT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41c4916e8090ce40598db1a8dd2a5d5d">llvm::post_order</a>, <a href="#a84c6b1abd4690a7185fa71371a4e523e">PostOrderNumbers</a>, <a href="#add68fc1b146794ec3ade9cee80aa34b0">ThrowingBlocks</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a3f9a9e4bc63b4f1c3b0e20bfb5e2be21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DSEState &amp; anonymous{DeadStoreElimination.cpp}::DSEState::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate">DSEState</a> &amp;)</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Reference <a href="#a7d4379cc88c3ee5e87f0dd0e43f8b037">DSEState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleteDeadInstruction() {#a32e5e2e67b52bcd45fef4487f664f9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt; * Deleted=nullptr)</td>
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

<p>Delete dead memory defs and recursively add their operands to ToRemove if they became dead.</p>

<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a35726fe54d4ed5d882902b2915de71df">CapturedBeforeReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a5fe6005bf6e415c950c011fb65f12b8f">Deleted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9a4d21540d7bb0e9c694b2fad0ae8d1b">EA</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4f82a6d5fab81ea329c99054aef113a0">InvisibleToCallerAfterRet</a>, <a href="#ad92b91b957cb57f2dfdc5dadc62ed3c9">IOLs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5df9c7cb06c08a066a30482d77cc1d9">llvm::salvageKnowledge</a>, <a href="#ae5389ad8a0692df0ac580907f82703d2">ShouldIterateEndOfFunctionDSE</a>, <a href="#a67cc54791481863d6a63992f0bdc7b5f">SkipStores</a>, <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a> and <a href="#ae042e649168834e60114a0d11320bcd0">ToRemove</a>.</p>


<p>Referenced by <a href="#a341c9b08b6693494d83c9a28aae1d3a8">eliminateDeadDefs</a> and <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>.</p>

</div>
</div>

### dominatingConditionImpliesValue() {#ae046f3782a1242c97fe9fe937793fa3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::dominatingConditionImpliesValue (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * Def)</td>
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



<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a327f8dad1ecd68d640256e844d49f9ba">llvm::PatternMatch::m_c_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2adca0e23c974dbb32019dccb22547bc">llvm::PatternMatch::m_Instruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6a512a71ae0746953ca6585669a4d47c">llvm::PatternMatch::m_Load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>.</p>


<p>Referenced by <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a>.</p>

</div>
</div>

### eliminateDeadDefs() {#acdd3b591101453540fdf4b9d17d49100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper">MemoryLocationWrapper</a> &amp; KillingLocWrapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper/#aab5cc4da031d95a282962ae7c67ba2c0">anonymous{DeadStoreElimination.cpp}::MemoryLocationWrapper::DefByInitializesAttr</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorydefwrapper/#a02849cff77b89e851615cd54faa29d0d">anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::DefinedLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper/#a9a7aa637d8dab0a0d78c6f199e4ebd22">anonymous{DeadStoreElimination.cpp}::MemoryLocationWrapper::DefInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a5fe6005bf6e415c950c011fb65f12b8f">Deleted</a>, <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a30df40b902c979f5cf5e4a1576fdd0bf">EnablePartialStoreMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#ad92b91b957cb57f2dfdc5dadc62ed3c9">IOLs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a5ac1334eaea5f705c77ad5fc431333f8">isMemTerminatorInst</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa46849ad227581d0105b7c41b4f9377f">isPartialOverwrite</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper/#a81828c4ffa1e456607f598ff6b0a9580">anonymous{DeadStoreElimination.cpp}::MemoryLocationWrapper::MemDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper/#a55b84ff5c035f034d7bfce04ccae354e">anonymous{DeadStoreElimination.cpp}::MemoryLocationWrapper::MemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa4a0732f6643b5a97dee032a7b43c1af">MemorySSAPartialStoreLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a9c369e6c129e5ea1834c23f2a22c4b44">MemorySSAScanLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#ad73f165ea1c5a5bbbc0a8bdf2c17fe68">MemorySSAUpwardsStepLimit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173aca58bbedad54ea965c6413e5ba085138">anonymous{DeadStoreElimination.cpp}::OW_MaybePartial</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173ab92940d0612a997d924e7f87aa969cdb">anonymous{DeadStoreElimination.cpp}::OW_PartialEarlierWithFullLater</a>, <a href="#a84c6b1abd4690a7185fa71371a4e523e">PostOrderNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="#a67cc54791481863d6a63992f0bdc7b5f">SkipStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a5ac801ed9e1a056f66831b7f0129fdb0">tryToMergePartialOverlappingStores</a> and <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper/#a6dcb2c7e682afd013b32631ad46c10da">anonymous{DeadStoreElimination.cpp}::MemoryLocationWrapper::UnderlyingObject</a>.</p>


<p>Referenced by <a href="#a341c9b08b6693494d83c9a28aae1d3a8">eliminateDeadDefs</a>.</p>

</div>
</div>

### eliminateDeadDefs() {#a341c9b08b6693494d83c9a28aae1d3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorydefwrapper">MemoryDefWrapper</a> &amp; KillingDefWrapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorydefwrapper/#a02849cff77b89e851615cd54faa29d0d">anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::DefinedLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorydefwrapper/#adba1b2b1805c9f7dd7ca315e41dcdded">anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::DefInst</a>, <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### eliminateDeadWritesAtEndOfFunction() {#a84375aa02b6bdbc67c1a42dccc3904e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadWritesAtEndOfFunction ()</td>
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

<p>Eliminate writes to objects that are not visible in the caller and are not accessed before returning from the function.</p>

<p>Definition at line 1913 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#aebc62faf59fecc07e8471fcf035d789e">deleteDeadInstruction</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#a4ad7610d15181c1efbcaa192efb34430">isInvisibleToCallerAfterRet</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="#a5eb76849763054986dcdd4f2f41d369e">isWriteAtEndOfFunction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a7f2553a2f977ad3f44aa1fbfd250b409">MemDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#ae5389ad8a0692df0ac580907f82703d2">ShouldIterateEndOfFunctionDSE</a> and <a href="#a67cc54791481863d6a63992f0bdc7b5f">SkipStores</a>.</p>

</div>
</div>

### eliminateRedundantStoresOfExistingValues() {#a73ef5ac7d0abd594af4c190baa6515a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::eliminateRedundantStoresOfExistingValues ()</td>
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

<p>Eliminates writes to locations where the value that is being written is already stored at the same location.</p>

<p>Definition at line 2187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#aebc62faf59fecc07e8471fcf035d789e">deleteDeadInstruction</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#abe63c310031eb3c578b122f0c31739d7">llvm::MemoryUseOrDef::getMemoryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ad848bd0184fc7bcb7b71e19248f08f34">llvm::Instruction::isIdenticalTo</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#a7a3a865fee609f58bb1a914b69afe20f">isReadClobber</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a7f2553a2f977ad3f44aa1fbfd250b409">MemDefs</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a> and <a href="#a67cc54791481863d6a63992f0bdc7b5f">SkipStores</a>.</p>

</div>
</div>

### getDomMemoryDef() {#a0b9027fe8e7ff91d9d6ee565fbdb3db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryAccess * &gt; anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * KillingDef, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * StartAccess, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; KillingLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * KillingUndObj, unsigned &amp; ScanLimit, unsigned &amp; WalkerStepLimit, bool IsMemTerm, unsigned &amp; PartialLimit, bool IsInitializesAttrMemLoc)</td>
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



<p>Definition at line 1425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#ae1c41d3a5e832d85f16db3fb43b729b0">AnyUnreachableExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#a0b8426b10dd0013c86e790af7ff415b8">anonymous{DeadStoreElimination.cpp}::canSkipDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#abe63c310031eb3c578b122f0c31739d7">llvm::MemoryUseOrDef::getMemoryInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a3544d6fc5a304b516d34fb76461b345e">isCompleteOverwrite</a>, <a href="#a1806b14f4d7a63958af99758745046e2">isDSEBarrier</a>, <a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a>, <a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a>, <a href="#a4ad7610d15181c1efbcaa192efb34430">isInvisibleToCallerAfterRet</a>, <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a>, <a href="#a282a917fb3815ffbd1d1f4dc9974d843">isMemTerminator</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#aafc4044eaf6d1effe7de8dd56d5bd243">anonymous{DeadStoreElimination.cpp}::isNoopIntrinsic</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#a7a3a865fee609f58bb1a914b69afe20f">isReadClobber</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9149819221d66953ac6c2938b87f0136">llvm::Instruction::mayReadFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0501e3b4084693092efc0be8b02c1b6b">llvm::Instruction::mayThrow</a>, <a href="#abd0ccb39ca68a8679460a7bd49678c88">mayThrowBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a942e9d7d88c83c2a8c212dda071f5fa2">MemorySSAOtherBBStepCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#af48ae41686c15765aedf065d2ab8fa4a">MemorySSAPathCheckLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa2d3141f0c72029b5e37952a6dc7f28c">MemorySSASameBBStepCost</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#ae4cd17695d61c2193abfa79a4a2ff556">OptimizeMemorySSA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173aca58bbedad54ea965c6413e5ba085138">anonymous{DeadStoreElimination.cpp}::OW_MaybePartial</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a24895aa26eff0c4648c9a58c9b8c8f9c">anonymous{DeadStoreElimination.cpp}::OW_None</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173acebc97682d8036254b6ee04910656525">anonymous{DeadStoreElimination.cpp}::OW_Unknown</a>, <a href="#a670428895b6bf9c32a8960747b25decc">PDT</a>, <a href="#a84c6b1abd4690a7185fa71371a4e523e">PostOrderNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="#ad50c0551a73d70d5bd769557bdbec3d7">pushMemUses</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydef/#af8ce9c4c2a0f042aa8a7c365a293d642">llvm::MemoryDef::setOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>.</p>

</div>
</div>

### getInitializesArgMemLoc() {#ae58d526e759487737de52702abf2b7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; MemoryLocation, 1 &gt; anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa87fae97a8c702741eca5a95748af49d">llvm::CallBase::doesNotThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9a4d21540d7bb0e9c694b2fad0ae8d1b">EA</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a5ad56085375ff21711ca97af4bb7ef44">llvm::ConstantRangeList::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46815b7f69bb96eddd2e1e01bec6120c">llvm::MemoryLocation::getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ae6155da930181ded60bf9106eccec2b0">anonymous{DeadStoreElimination.cpp}::getIntersectedInitRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50b4d34365cf704260dd9e43796144ea">llvm::CallBase::getParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a93a771ed3c28612ca7852e1d9c62ab05">llvm::Attribute::getValueAsConstantRangeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a610f151afe638890b21bea434a26821d">llvm::CallBase::isByValArgument</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#acc93b6f7cc7a5092de1098c7f27a1a48">anonymous{DeadStoreElimination.cpp}::isFuncLocalAndNotCaptured</a>, <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7a2ce134efb83b008e2180d30451ac98">llvm::CallBase::onlyAccessesInaccessibleMemOrArgMem</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a>.</p>

</div>
</div>

### getLocForInst() {#a6e05969129f7f7f1463e3fb1437f6f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::pair&lt; MemoryLocation, bool &gt;, 1 &gt; anonymous{DeadStoreElimination.cpp}::DSEState::getLocForInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool ConsiderInitializesAttr)</td>
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



<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#ae58d526e759487737de52702abf2b7c5">getInitializesArgMemLoc</a>, <a href="#ad1a51eb63abe756612f5b8765cfe4e2a">getLocForTerminator</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a5ac1334eaea5f705c77ad5fc431333f8">isMemTerminatorInst</a>.</p>


<p>Referenced by <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>.</p>

</div>
</div>

### getLocForTerminator() {#ad1a51eb63abe756612f5b8765cfe4e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; MemoryLocation, bool &gt; &gt; anonymous{DeadStoreElimination.cpp}::DSEState::getLocForTerminator (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>If <span class="doxyComputerOutput">I</span> is a memory terminator like llvm.lifetime.end or free, return a pair with the <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> terminated by <span class="doxyComputerOutput">I</span> and a boolean flag indicating whether <span class="doxyComputerOutput">I</span> is a free-like call.</p>

<p>Definition at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a49f776e0940cc5d63d17d85ff6dac257">llvm::MemoryLocation::getAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a> and <a href="#a282a917fb3815ffbd1d1f4dc9974d843">isMemTerminator</a>.</p>

</div>
</div>

### getLocForWrite() {#a7876ddf180b2706ffa008155e3f20c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryLocation &gt; anonymous{DeadStoreElimination.cpp}::DSEState::getLocForWrite (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#ac8f8983c6b76d0e30f22fff86b281f16">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af61b31a99c1e58b1760492d2a7a1ba9c">llvm::MemoryLocation::getOrNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a>, <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a>, <a href="#a3544d6fc5a304b516d34fb76461b345e">isCompleteOverwrite</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a> and <a href="#afceb7703f48842eea9acf024ce0bd865">removePartiallyOverlappedStores</a>.</p>

</div>
</div>

### isCompleteOverwrite() {#a3544d6fc5a304b516d34fb76461b345e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isCompleteOverwrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; DefLoc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DefInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst)</td>
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

<p>Returns true if <span class="doxyComputerOutput">UseInst</span> completely overwrites <span class="doxyComputerOutput">DefLoc</span> (stored by <span class="doxyComputerOutput">DefInst</span>).</p>

<p>Definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a383175f96316074965ad115706bd49d7">llvm::Instruction::mayWriteToMemory</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### isDSEBarrier() {#a1806b14f4d7a63958af99758745046e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isDSEBarrier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * KillingUndObj, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DeadI)</td>
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



<p>Definition at line 1888 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a57efb022f2ee2e19e4cdf582f4d27f2d">llvm::Instruction::isAtomic</a>, <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230fb4d924829b7649a5fb112dcbe9f8">llvm::isStrongerThanMonotonic</a>, <a href="#ab6801022c51a18914c49e3ecf8d139b3">LI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0501e3b4084693092efc0be8b02c1b6b">llvm::Instruction::mayThrow</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### isGuaranteedLoopIndependent() {#a870a4918277d840461917023a42f1d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isGuaranteedLoopIndependent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Current, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * KillingDef, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; CurrentLoc)</td>
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

<p>Returns true if a dependency between <span class="doxyComputerOutput">Current</span> and <span class="doxyComputerOutput">KillingDef</span> is guaranteed to be loop invariant for the loops that they are in.</p>


<p>Either because they are known to be in the same block, in the same loop level or by guaranteeing that <span class="doxyComputerOutput">CurrentLoc</span> only references a single <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> during execution of the containing function.</p>


<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#acc7b15819b7223fc2f19b3708372de1d">ContainsIrreducibleLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a>, <a href="#ab6801022c51a18914c49e3ecf8d139b3">LI</a> and <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a> and <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>.</p>

</div>
</div>

### isGuaranteedLoopInvariant() {#a55232923939cd416fa4b1d1aad06cd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isGuaranteedLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Ptr</span> is guaranteed to be loop invariant for any possible loop.</p>


<p>In particular, this guarantees that it only references a single <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> during execution of the containing function.</p>


<p>Definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#acc7b15819b7223fc2f19b3708372de1d">ContainsIrreducibleLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab6801022c51a18914c49e3ecf8d139b3">LI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a> and <a href="#a5eb76849763054986dcdd4f2f41d369e">isWriteAtEndOfFunction</a>.</p>

</div>
</div>

### isInvisibleToCallerAfterRet() {#a4ad7610d15181c1efbcaa192efb34430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isInvisibleToCallerAfterRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4f82a6d5fab81ea329c99054aef113a0">InvisibleToCallerAfterRet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a433468826ef20b5ddb53704fc38363fc">llvm::isNoAliasCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7912b6c9e7843ca9fd5a11e199bef617">llvm::PointerMayBeCaptured</a>.</p>


<p>Referenced by <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a> and <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### isInvisibleToCallerOnUnwind() {#aa90baa0108f72fbe0f46c158a94fd484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isInvisibleToCallerOnUnwind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a35726fe54d4ed5d882902b2915de71df">CapturedBeforeReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a894b02a1122caccc0ed5eb9b321d22bb">llvm::isNotVisibleOnUnwind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7912b6c9e7843ca9fd5a11e199bef617">llvm::PointerMayBeCaptured</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#ae58d526e759487737de52702abf2b7c5">getInitializesArgMemLoc</a>, <a href="#a1806b14f4d7a63958af99758745046e2">isDSEBarrier</a>, <a href="#a4ad7610d15181c1efbcaa192efb34430">isInvisibleToCallerAfterRet</a> and <a href="#abd0ccb39ca68a8679460a7bd49678c88">mayThrowBetween</a>.</p>

</div>
</div>

### isMemTerminator() {#a282a917fb3815ffbd1d1f4dc9974d843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isMemTerminator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AccessI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MaybeTerm)</td>
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

<p>Returns true if <span class="doxyComputerOutput">MaybeTerm</span> is a memory terminator for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> from instruction <span class="doxyComputerOutput">AccessI</span>.</p>

<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="#ad1a51eb63abe756612f5b8765cfe4e2a">getLocForTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### isMemTerminatorInst() {#a5ac1334eaea5f705c77ad5fc431333f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isMemTerminatorInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory terminator instruction like llvm.lifetime.end or free.</p>

<p>Definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a> and <a href="#a6e05969129f7f7f1463e3fb1437f6f88">getLocForInst</a>.</p>

</div>
</div>

### isOverwrite() {#ad2005ee17b5b6cb575257dc12793a077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverwriteResult anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * KillingI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DeadI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; KillingLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; DeadLoc, int64_t &amp; KillingOff, int64_t &amp; DeadOff)</td>
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

<p>Return 'OW_Complete' if a store to the 'KillingLoc' location (by <span class="doxyComputerOutput">KillingI</span> instruction) completely overwrites a store to the 'DeadLoc' location (by <span class="doxyComputerOutput">DeadI</span> instruction).</p>


<p>Return OW_MaybePartial if <span class="doxyComputerOutput">KillingI</span> does not completely overwrite <span class="doxyComputerOutput">DeadI</span>, but they both write to the same underlying object. In that case, use isPartialOverwrite to check if <span class="doxyComputerOutput">KillingI</span> partially overwrites <span class="doxyComputerOutput">DeadI</span>. Returns 'OR_None' if <span class="doxyComputerOutput">KillingI</span> is known to not overwrite the <span class="doxyComputerOutput">DeadI</span>. Returns 'OW_Unknown' if nothing can be determined.</p>


<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acd2ae8a14a4be9361bcce760c89d2eac">F</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#acedb65c0cfa62eca04a90d92017dd0c6">llvm::AliasResult::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa869f364a3c2e42a22fb605382eaf7c4">getPointerSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#ad877dea909eff4e9714f31be1c770491">llvm::AliasResult::hasOffset</a>, <a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed2c5dd2a303159f87771db83f54352b">llvm::isIdentifiedObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a8daf1ecab5704c6aa3672b2fcec60f29">isMaskedStoreOverwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#aa9addaa6f7dd437922a57401cb192031">llvm::LocationSize::isPrecise</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a900ef826f2fe747a00dc0bdb6b8ede87">llvm::LocationSize::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a2d4a746f8b3f9492889f9232063d86f8">anonymous{DeadStoreElimination.cpp}::OW_Complete</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173aca58bbedad54ea965c6413e5ba085138">anonymous{DeadStoreElimination.cpp}::OW_MaybePartial</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173a24895aa26eff0c4648c9a58c9b8c8f9c">anonymous{DeadStoreElimination.cpp}::OW_None</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ac512d9d0a4bc8f26ff95ba31373e4173acebc97682d8036254b6ee04910656525">anonymous{DeadStoreElimination.cpp}::OW_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a9e724bc94de38c6ca77508f19c246c0c">llvm::AliasResult::PartialAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a39f7ff959874bf38f3e14aa0b2622da0">llvm::MemoryLocation::Size</a>, <a href="#aaa3589bcd74d9f4a9131af14ccd5a430">strengthenLocationSize</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#a3544d6fc5a304b516d34fb76461b345e">isCompleteOverwrite</a> and <a href="#a282a917fb3815ffbd1d1f4dc9974d843">isMemTerminator</a>.</p>

</div>
</div>

### isReadClobber() {#a7a3a865fee609f58bb1a914b69afe20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isReadClobber (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; DefLoc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst)</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#aafc4044eaf6d1effe7de8dd56d5bd243">anonymous{DeadStoreElimination.cpp}::isNoopIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7787f6b577cd7a63f043b87301b8e81">llvm::isRefSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af21b12b7c8de1504a945c4c974e06bff">llvm::isStrongerThan</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9149819221d66953ac6c2938b87f0136">llvm::Instruction::mayReadFromMemory</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>.</p>


<p>Referenced by <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a> and <a href="#a5eb76849763054986dcdd4f2f41d369e">isWriteAtEndOfFunction</a>.</p>

</div>
</div>

### isRemovable() {#ad1d56da72eedcf668dc71bad9f0bc07b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isRemovable (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Assuming this instruction has a dead analyzable write, can we delete this instruction?</p>

<p>Definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a>, <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#afceb7703f48842eea9acf024ce0bd865">removePartiallyOverlappedStores</a>, <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### isWriteAtEndOfFunction() {#a5eb76849763054986dcdd4f2f41d369e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::isWriteAtEndOfFunction (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; DefLoc)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Def</span> is not read before returning from the function.</p>

<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a>, <a href="#a7a3a865fee609f58bb1a914b69afe20f">isReadClobber</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a9c369e6c129e5ea1834c23f2a22c4b44">MemorySSAScanLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>, <a href="#ad50c0551a73d70d5bd769557bdbec3d7">pushMemUses</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a>.</p>

</div>
</div>

### mayThrowBetween() {#abd0ccb39ca68a8679460a7bd49678c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::mayThrowBetween (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * KillingI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DeadI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * KillingUndObj)</td>
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



<p>Definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a> and <a href="#add68fc1b146794ec3ade9cee80aa34b0">ThrowingBlocks</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### removePartiallyOverlappedStores() {#afceb7703f48842eea9acf024ce0bd865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::removePartiallyOverlappedStores (<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7e1af7835f27dc4a15c94320884797e9">InstOverlapIntervalsTy</a> &amp; IOL)</td>
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



<p>Definition at line 2165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#ac631b4af10a30255067fc77ab6c193d8">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::empty</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a315447cd8d049de76d99af3f9cda45a2">tryToShortenBegin</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aac40904307eb0bd89cfc9d73039ba8e0">tryToShortenEnd</a>.</p>

</div>
</div>

### storeIsNoop() {#a0830273a57e2290e00f3ea50b6e082e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::storeIsNoop (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DefUO)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">Def</span> is a no-op store, either because it directly stores back a loaded value or stores zero to a calloced object.</p></dd>
</dl>


<p>Definition at line 2087 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae046f3782a1242c97fe9fe937793fa3f">dominatingConditionImpliesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a108b6e33f153eda5019d322f0ac909b0">llvm::getInitialValueOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetbase/#a770c508bbe4f9b480f0d08a839ca94ff">llvm::MemSetBase&lt; BaseCL &gt;::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#a341c9b08b6693494d83c9a28aae1d3a8">eliminateDeadDefs</a>.</p>

</div>
</div>

### strengthenLocationSize() {#aaa3589bcd74d9f4a9131af14ccd5a430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize anonymous{DeadStoreElimination.cpp}::DSEState::strengthenLocationSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> Size)</td>
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



<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acd2ae8a14a4be9361bcce760c89d2eac">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>.</p>

</div>
</div>

### tryFoldIntoCalloc() {#a5e2cdb7da821f277764240569336bd07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::tryFoldIntoCalloc (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DefUO)</td>
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

<p>If we have a zero initializing memset following a call to malloc, try folding it into a call to calloc.</p>

<p>Definition at line 1956 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a5495504ab8eb253e69a94261f275cd15">BatchAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#acf9a0bb25aae89d274ee9ae7dd0cf9b2">llvm::MemorySSAUpdater::createMemoryAccessAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#aebc62faf59fecc07e8471fcf035d789e">deleteDeadInstruction</a>, <a href="#af22719f6b4218045e44871a8c6d82f4d">DL</a>, <a href="#ab905be2ba2371243af6aa076b9b7ad7a">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbd4c4f3aebf9f810f0590d49ba1003">llvm::emitCalloc</a>, <a href="#acd2ae8a14a4be9361bcce760c89d2eac">F</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a0fef04103987e9763468d19eb680b223">llvm::MemIntrinsicBase&lt; Derived &gt;::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetbase/#a770c508bbe4f9b480f0d08a839ca94ff">llvm::MemSetBase&lt; BaseCL &gt;::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="#ad1d56da72eedcf668dc71bad9f0bc07b">isRemovable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a811d001fa503a556ac2a48d64366500f">llvm::PatternMatch::m_Br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a0efc0e8de0d1c7171d3e84ed656de113a1131a914388fac73e5f07b0ba0aad523">Malloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="#a2dfabd2322e39d5e9dbc326df8022956">MSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#ae112170085cd83327cd02c45a0276bfe">TLI</a>.</p>


<p>Referenced by <a href="#a341c9b08b6693494d83c9a28aae1d3a8">eliminateDeadDefs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AA {#aa794cce8f9f5e3d955bec921152a6c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis&amp; anonymous{DeadStoreElimination.cpp}::DSEState::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>.</p>

</div>
</div>

### AnyUnreachableExit {#ae1c41d3a5e832d85f16db3fb43b729b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::AnyUnreachableExit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> and <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### BatchAA {#a5495504ab8eb253e69a94261f275cd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults anonymous{DeadStoreElimination.cpp}::DSEState::BatchAA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The single BatchAA instance that is used to cache AA queries.</p>


<p>It will not be invalidated over the whole run. This is safe, because:</p>


<ol class="doxyList" type="1">
<li>Only memory writes are removed, so the alias cache for memory locations remains valid.</li>
<li>No new instructions are added (only instructions removed), so cached information for a deleted value cannot be accessed by a re-used new value pointer.</li>
</ol>

<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#ae046f3782a1242c97fe9fe937793fa3f">dominatingConditionImpliesValue</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="#ae58d526e759487737de52702abf2b7c5">getInitializesArgMemLoc</a>, <a href="#a282a917fb3815ffbd1d1f4dc9974d843">isMemTerminator</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#a7a3a865fee609f58bb1a914b69afe20f">isReadClobber</a>, <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### CapturedBeforeReturn {#a35726fe54d4ed5d882902b2915de71df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, bool&gt; anonymous{DeadStoreElimination.cpp}::DSEState::CapturedBeforeReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a> and <a href="#aa90baa0108f72fbe0f46c158a94fd484">isInvisibleToCallerOnUnwind</a>.</p>

</div>
</div>

### ContainsIrreducibleLoops {#acc7b15819b7223fc2f19b3708372de1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::ContainsIrreducibleLoops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a> and <a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a>.</p>

</div>
</div>

### DL {#af22719f6b4218045e44871a8c6d82f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{DeadStoreElimination.cpp}::DSEState::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#afceb7703f48842eea9acf024ce0bd865">removePartiallyOverlappedStores</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### DT {#ab905be2ba2371243af6aa076b9b7ad7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{DeadStoreElimination.cpp}::DSEState::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#ae046f3782a1242c97fe9fe937793fa3f">dominatingConditionImpliesValue</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### EA {#a9a4d21540d7bb0e9c694b2fad0ae8d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EarliestEscapeAnalysis anonymous{DeadStoreElimination.cpp}::DSEState::EA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> and <a href="#ae58d526e759487737de52702abf2b7c5">getInitializesArgMemLoc</a>.</p>

</div>
</div>

### F {#acd2ae8a14a4be9361bcce760c89d2eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{DeadStoreElimination.cpp}::DSEState::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#aaa3589bcd74d9f4a9131af14ccd5a430">strengthenLocationSize</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### InvisibleToCallerAfterRet {#a4f82a6d5fab81ea329c99054aef113a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, bool&gt; anonymous{DeadStoreElimination.cpp}::DSEState::InvisibleToCallerAfterRet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> and <a href="#a4ad7610d15181c1efbcaa192efb34430">isInvisibleToCallerAfterRet</a>.</p>

</div>
</div>

### IOLs {#ad92b91b957cb57f2dfdc5dadc62ed3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;BasicBlock *, InstOverlapIntervalsTy&gt; anonymous{DeadStoreElimination.cpp}::DSEState::IOLs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of instructions (partly) overlapping with killing MemoryDefs per basic block.</p>

<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a> and <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>.</p>

</div>
</div>

### LI {#ab6801022c51a18914c49e3ecf8d139b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo&amp; anonymous{DeadStoreElimination.cpp}::DSEState::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#a1806b14f4d7a63958af99758745046e2">isDSEBarrier</a>, <a href="#a870a4918277d840461917023a42f1d57">isGuaranteedLoopIndependent</a> and <a href="#a55232923939cd416fa4b1d1aad06cd2a">isGuaranteedLoopInvariant</a>.</p>

</div>
</div>

### MemDefs {#a7f2553a2f977ad3f44aa1fbfd250b409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MemoryDef *, 64&gt; anonymous{DeadStoreElimination.cpp}::DSEState::MemDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a> and <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>.</p>

</div>
</div>

### MSSA {#a2dfabd2322e39d5e9dbc326df8022956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA&amp; anonymous{DeadStoreElimination.cpp}::DSEState::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#ae046f3782a1242c97fe9fe937793fa3f">dominatingConditionImpliesValue</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>, <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>, <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### PDT {#a670428895b6bf9c32a8960747b25decc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree&amp; anonymous{DeadStoreElimination.cpp}::DSEState::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> and <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### PostOrderNumbers {#a84c6b1abd4690a7185fa71371a4e523e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, unsigned&gt; anonymous{DeadStoreElimination.cpp}::DSEState::PostOrderNumbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a> and <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a>.</p>

</div>
</div>

### ShouldIterateEndOfFunctionDSE {#ae5389ad8a0692df0ac580907f82703d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeadStoreElimination.cpp}::DSEState::ShouldIterateEndOfFunctionDSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a> and <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a>.</p>

</div>
</div>

### SkipStores {#a67cc54791481863d6a63992f0bdc7b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MemoryAccess *, 4&gt; anonymous{DeadStoreElimination.cpp}::DSEState::SkipStores</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#acdd3b591101453540fdf4b9d17d49100">eliminateDeadDefs</a>, <a href="#a84375aa02b6bdbc67c1a42dccc3904e2">eliminateDeadWritesAtEndOfFunction</a> and <a href="#a73ef5ac7d0abd594af4c190baa6515a5">eliminateRedundantStoresOfExistingValues</a>.</p>

</div>
</div>

### ThrowingBlocks {#add68fc1b146794ec3ade9cee80aa34b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 16&gt; anonymous{DeadStoreElimination.cpp}::DSEState::ThrowingBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a> and <a href="#abd0ccb39ca68a8679460a7bd49678c88">mayThrowBetween</a>.</p>

</div>
</div>

### TLI {#ae112170085cd83327cd02c45a0276bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo&amp; anonymous{DeadStoreElimination.cpp}::DSEState::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>, <a href="#aa1d21b1024d9925b46d10fcd11e0483c">DSEState</a>, <a href="#ad1a51eb63abe756612f5b8765cfe4e2a">getLocForTerminator</a>, <a href="#a7876ddf180b2706ffa008155e3f20c80">getLocForWrite</a>, <a href="#a5ac1334eaea5f705c77ad5fc431333f8">isMemTerminatorInst</a>, <a href="#ad2005ee17b5b6cb575257dc12793a077">isOverwrite</a>, <a href="#a0830273a57e2290e00f3ea50b6e082e4">storeIsNoop</a>, <a href="#aaa3589bcd74d9f4a9131af14ccd5a430">strengthenLocationSize</a> and <a href="#a5e2cdb7da821f277764240569336bd07">tryFoldIntoCalloc</a>.</p>

</div>
</div>

### ToRemove {#ae042e649168834e60114a0d11320bcd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *&gt; anonymous{DeadStoreElimination.cpp}::DSEState::ToRemove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dead instructions to be removed at the end of DSE.</p>

<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="#a32e5e2e67b52bcd45fef4487f664f9ec">deleteDeadInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### pushMemUses() {#ad50c0551a73d70d5bd769557bdbec3d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DeadStoreElimination.cpp}::DSEState::pushMemUses (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Acc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt; &amp; WorkList, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt; &amp; Visited)</td>
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



<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a0b9027fe8e7ff91d9d6ee565fbdb3db4">getDomMemoryDef</a> and <a href="#a5eb76849763054986dcdd4f2f41d369e">isWriteAtEndOfFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
