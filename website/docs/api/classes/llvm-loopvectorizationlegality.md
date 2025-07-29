---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopvectorizationlegality
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopVectorizationLegality` Class

<p><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> checks if it is legal to vectorize a loop, and to what vectorization factor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopVectorizationLegality { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">llvm/Transforms/Vectorize/LoopVectorizationLegality.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe830a64fea7dbeee20cdda3726b0120">ReductionList</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#abe830a64fea7dbeee20cdda3726b0120">ReductionList</a> contains the reduction descriptors for all of the reductions that were found in the loop. <a href="#abe830a64fea7dbeee20cdda3726b0120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063c4d98febe7ef90dddbfedcfc59d16">InductionList</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a063c4d98febe7ef90dddbfedcfc59d16">InductionList</a> saves induction variables and maps them to the induction descriptor. <a href="#a063c4d98febe7ef90dddbfedcfc59d16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543d30d3a2b289aaa6b363be25d2b295">RecurrenceSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 8 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a543d30d3a2b289aaa6b363be25d2b295">RecurrenceSet</a> contains the phi nodes that are recurrences other than inductions and reductions. <a href="#a543d30d3a2b289aaa6b363be25d2b295">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ee5ed437953ba182781372d6a03fb3">LoopVectorizationLegality</a> (Loop *L, PredicatedScalarEvolution &amp;PSE, DominatorTree *DT, TargetTransformInfo *TTI, TargetLibraryInfo *TLI, Function *F, LoopAccessInfoManager &amp;LAIs, LoopInfo *LI, OptimizationRemarkEmitter *ORE, LoopVectorizationRequirements *R, LoopVectorizeHints *H, DemandedBits *DB, AssumptionCache *AC, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce10d1174bdfcac2b73ed7efa352b7f">canVectorize</a> (bool UseVPlanNativePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is legal to vectorize this loop. <a href="#a3ce10d1174bdfcac2b73ed7efa352b7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552a158f5a673da0a26461d1471cea41">canVectorizeFPMath</a> (bool EnableStrictReductions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is legal to vectorize the FP math operations in this loop. <a href="#a552a158f5a673da0a26461d1471cea41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa8144325b3c584e828b07d73a8cb25">canFoldTailByMasking</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can vectorize this loop while folding its tail by masking. <a href="#aafa8144325b3c584e828b07d73a8cb25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b7c658c190bc113272ef4257a47659">prepareToFoldTailByMasking</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all respective loads/stores for masking. <a href="#ab0b7c658c190bc113272ef4257a47659">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78dab1aa1facf4bf6300b3275490fa11">getPrimaryInduction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the primary induction variable. <a href="#a78dab1aa1facf4bf6300b3275490fa11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abe830a64fea7dbeee20cdda3726b0120">ReductionList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31c04881c640716da40ae22ddda69ad">getReductionVars</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the reduction variables found in the loop. <a href="#aa31c04881c640716da40ae22ddda69ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a063c4d98febe7ef90dddbfedcfc59d16">InductionList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dffddf3feec953bba0425b324b380dc">getInductionVars</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the induction variables found in the loop. <a href="#a8dffddf3feec953bba0425b324b380dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a543d30d3a2b289aaa6b363be25d2b295">RecurrenceSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317c5bedc82363ee7513fe56790878e7">getFixedOrderRecurrences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the fixed-order recurrences found in the loop. <a href="#a317c5bedc82363ee7513fe56790878e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1bbdeff3d286d3cd7a6e1f67a7e43ea">getWidestInductionType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the widest induction type. <a href="#ab1bbdeff3d286d3cd7a6e1f67a7e43ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9fd1c0627dfa3e013a1b2c7416ae90">isInvariantStoreOfReduction</a> (StoreInst *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if given store is a final invariant store of one of the reductions found in the loop. <a href="#a1c9fd1c0627dfa3e013a1b2c7416ae90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f384c7ff8e4b23cc79156daf2a5c11">isInvariantAddressOfReduction</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if given address is invariant and is used to store recurrent expression. <a href="#a34f384c7ff8e4b23cc79156daf2a5c11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7803d6f1162773c3b1a61e3ff441fcb8">isInductionPhi</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if V is a Phi node of an induction variable in this loop. <a href="#a7803d6f1162773c3b1a61e3ff441fcb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74bcb5c6d80d9d7fb0eeb1131eeef2dc">getIntOrFpInductionDescriptor</a> (PHINode *Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the induction descriptor, if <span class="doxyComputerOutput">Phi</span> is an integer or floating point induction. <a href="#a74bcb5c6d80d9d7fb0eeb1131eeef2dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728069d0bcacf976cbb3764bad749562">getPointerInductionDescriptor</a> (PHINode *Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the induction descriptor, if <span class="doxyComputerOutput">Phi</span> is pointer induction. <a href="#a728069d0bcacf976cbb3764bad749562">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0c0e675aff7e870f18b9c911977b7a">isCastedInductionVariable</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if V is a cast that is part of an induction def-use chain, and had been proven to be redundant under a runtime guard (in other words, the cast has the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression as the induction phi). <a href="#afd0c0e675aff7e870f18b9c911977b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f3d6495086eb1a43e829bf045fd073">isInductionVariable</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if V can be considered as an induction variable in this loop. <a href="#af9f3d6495086eb1a43e829bf045fd073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c26e54d871c42c42dc62f9d449c633a">isReductionVariable</a> (PHINode *PN) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if PN is a reduction variable in this loop. <a href="#a5c26e54d871c42c42dc62f9d449c633a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6b8f1a562e7d26404946de46d3045b">isFixedOrderRecurrence</a> (const PHINode *Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns True if Phi is a fixed-order recurrence in this loop. <a href="#a5d6b8f1a562e7d26404946de46d3045b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b78b24a3c241e611957b82cd12640da">blockNeedsPredication</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the block BB needs to be predicated in order for the loop to be vectorized. <a href="#a3b78b24a3c241e611957b82cd12640da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4589ea484ebe1919b451fff3948a17cc">isConsecutivePtr</a> (Type *AccessTy, Value *Ptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this pointer is consecutive when vectorizing. <a href="#a4589ea484ebe1919b451fff3948a17cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10b9dac96a36c8b4da25fc6fa1d4352">isInvariant</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">V</span> is invariant across all loop iterations according to <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#aa10b9dac96a36c8b4da25fc6fa1d4352">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e581cb8e98cb0649e8b524eed5c9c0">isUniform</a> (Value *V, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if value V is uniform across <span class="doxyComputerOutput">VF</span> lanes, when <span class="doxyComputerOutput">VF</span> is provided, and otherwise if <span class="doxyComputerOutput">V</span> is invariant across all loop iterations. <a href="#a86e581cb8e98cb0649e8b524eed5c9c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac562402715584ed9e836026bae1ac150">isUniformMemOp</a> (Instruction &amp;I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A uniform memory op is a load or store which accesses the same memory location on all <span class="doxyComputerOutput">VF</span> lanes, if <span class="doxyComputerOutput">VF</span> is provided and otherwise if the memory location is invariant. <a href="#ac562402715584ed9e836026bae1ac150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15a090796e9a873af5163ba057f4c85">getRuntimePointerChecking</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the information that we collected about runtime memory check. <a href="#af15a090796e9a873af5163ba057f4c85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5632546144c4db5bbe1f975aeebd9d2">getLAI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6717c9edc2614476ebb19bd73e8bcb8">isSafeForAnyVectorWidth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2551d678f358fcb0f498224876f58673">getMaxSafeVectorWidthInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">hasUncountableEarlyExit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the loop has exactly one uncountable early exit, i.e. <a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1727fd1036f0c932cae65a5b5db5a0d">getUncountableEarlyExitingBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the uncountable early exiting block, if there is exactly one. <a href="#ae1727fd1036f0c932cae65a5b5db5a0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fd596d86681aff77584c0fd661f18a">getUncountableEarlyExitBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the destination of the uncountable early exiting block, if there is exactly one. <a href="#a64fd596d86681aff77584c0fd661f18a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ced1e23ba4d4a56286b5f17f448ed7">isMaskRequired</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if vector representation of the instruction <span class="doxyComputerOutput">I</span> requires mask. <a href="#af0ced1e23ba4d4a56286b5f17f448ed7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ba553cf7c1e1b64bbf9d30eb540234">hasVectorCallVariants</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is at least one function call in the loop which has a vectorized variant available. <a href="#a23ba553cf7c1e1b64bbf9d30eb540234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ede4d70a86b91ae038a77c86b3f4aaa">hasStructVectorCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is at least one function call in the loop which returns a struct type and needs to be vectorized. <a href="#a9ede4d70a86b91ae038a77c86b3f4aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f59a9c87ede76fde54388f16562a930">getNumStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d35bb02e49c20fcafc8d179559da10">getNumLoads</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/histograminfo">HistogramInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5c51eb16a87d311cfebdceb7b04ea7">getHistogramInfo</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a HistogramInfo* for the given instruction if it was determined to be part of a load -&gt; update -&gt; store sequence where multiple lanes may be working on the same memory address. <a href="#a4f5c51eb16a87d311cfebdceb7b04ea7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab306c8094bdb8c7cbdbdfb9a05800007">hasHistograms</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a list of all known histogram operations in the loop. <a href="#ab306c8094bdb8c7cbdbdfb9a05800007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ecfb3b35e9665ce1444966f8ae0930f">getPredicatedScalarEvolution</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bbeec474957c61045c6cb37f2d8379">getLoop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13545e37bc06efcf7642cfda97c65bd3">getLoopInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b011656b75317bd3e291ef771491f10">getAssumptionCache</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6b349a0e6598527d2ea3ef89dba230">getScalarEvolution</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3add6f3f23fa2ec67277682de9acef7f">getDominatorTree</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a32abdcf9e80b2483aa55bc36f2840e">getCountableExitingBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns all exiting blocks with a countable exit, i.e. <a href="#a7a32abdcf9e80b2483aa55bc36f2840e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e8b4a71d2eb63862cf0dfcb0e7d786">getUncountableEdge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the loop edge to an uncountable exit, or std::nullopt if there isn't a single such edge. <a href="#ad9e8b4a71d2eb63862cf0dfcb0e7d786">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a41b60d10bc31461995d56e5e05d8c9">canVectorizeLoopNestCFG</a> (Loop *Lp, bool UseVPlanNativePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the pre-header, exiting and latch blocks of <span class="doxyComputerOutput">Lp</span> and all its nested loops are considered legal for vectorization. <a href="#a9a41b60d10bc31461995d56e5e05d8c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2be4e9ca1d89ddb6724948c0dfc57d4">setupOuterLoopInductions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up outer loop inductions by checking Phis in outer loop header for supported inductions (int inductions). <a href="#aa2be4e9ca1d89ddb6724948c0dfc57d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb63ada87ea6eadc31ce33747903538f">canVectorizeLoopCFG</a> (Loop *Lp, bool UseVPlanNativePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the pre-header, exiting and latch blocks of <span class="doxyComputerOutput">Lp</span> (non-recursive) are considered legal for vectorization. <a href="#adb63ada87ea6eadc31ce33747903538f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba58236b7663ae958f41a085233e758a">canVectorizeInstrs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a single basic block loop is vectorizable. <a href="#aba58236b7663ae958f41a085233e758a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637e3ecb85b6fff4f0f166d67f45c270">canVectorizeMemory</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When we vectorize loops we may change the order in which we read and write from memory. <a href="#a637e3ecb85b6fff4f0f166d67f45c270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05fda32a2e1807a0b70938d95a27c2ed">canVectorizeIndirectUnsafeDependences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If LAA cannot determine whether all dependences are safe, we may be able to further analyse some IndirectUnsafe dependences and if they match a certain pattern (like a histogram) then we may still be able to vectorize. <a href="#a05fda32a2e1807a0b70938d95a27c2ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a5ae24d98b624801fe6776da7e47dc">canVectorizeWithIfConvert</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can vectorize this loop using the IF-conversion transformation. <a href="#ae6a5ae24d98b624801fe6776da7e47dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5aafa99304a61bb2e13f6c2bd25a7d">canVectorizeOuterLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can vectorize this outer loop. <a href="#a9c5aafa99304a61bb2e13f6c2bd25a7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0961a8a5109f7d5c34a2313293e602e2">isVectorizableEarlyExitLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is an early exit loop that can be vectorized. <a href="#a0961a8a5109f7d5c34a2313293e602e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9b746c802505da2247f2d2252b6b43">blockCanBePredicated</a> (BasicBlock *BB, SmallPtrSetImpl&lt; Value * &gt; &amp;SafePtrs, SmallPtrSetImpl&lt; const Instruction * &gt; &amp;MaskedOp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all of the instructions in the block can be speculatively executed, and record the loads/stores that require masking. <a href="#aeb9b746c802505da2247f2d2252b6b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c97b098510b893ff3c16829cfa78f3b">addInductionPhi</a> (PHINode *Phi, const InductionDescriptor &amp;ID, SmallPtrSetImpl&lt; Value * &gt; &amp;AllowedExit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the vectorization state by adding <span class="doxyComputerOutput">Phi</span> to the inductions list. <a href="#a7c97b098510b893ff3c16829cfa78f3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3808cce17fc47f8edd58849af507fc2f">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop that we evaluate. <a href="#a3808cce17fc47f8edd58849af507fc2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb9b6635ed708773bc9c079fc10cb1b">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis. <a href="#aecb9b6635ed708773bc9c079fc10cb1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdd6f36c94c7915cb98d7ad501a49be">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks. <a href="#a3bdd6f36c94c7915cb98d7ad501a49be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaaacd1e1d906e11bdf1f8b6fb7c91b9">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info. <a href="#acaaacd1e1d906e11bdf1f8b6fb7c91b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa863ed59572b0d4943ce4cce06179f12">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info. <a href="#aa863ed59572b0d4943ce4cce06179f12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b56d32f00a7726f94dfa06ed752670">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominator Tree. <a href="#a27b56d32f00a7726f94dfa06ed752670">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9867aa9ca1a32c23a5c99862d1699bac">LAIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca72182d1d5250777d463e2254ed8ac">LAI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd8f7c0effe71c22a81569e18560945">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to emit optimization remarks. <a href="#a1dd8f7c0effe71c22a81569e18560945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ebbb2516317552943315010ba587c6">PrimaryInduction</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the primary induction variable. <a href="#a09ebbb2516317552943315010ba587c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abe830a64fea7dbeee20cdda3726b0120">ReductionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac847a2194c17711fa779faf681db9633">Reductions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the reduction variables. <a href="#ac847a2194c17711fa779faf681db9633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a063c4d98febe7ef90dddbfedcfc59d16">InductionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051d230e9e98d92f852cfd260bb5e9a4">Inductions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds all of the induction variables that we found in the loop. <a href="#a051d230e9e98d92f852cfd260bb5e9a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a4f19197a92484b208fc2bfe0aca7a3">InductionCastsToIgnore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds all the casts that participate in the update chain of the induction variables, and that have been proven to be redundant (possibly under a runtime guard). <a href="#a4a4f19197a92484b208fc2bfe0aca7a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a543d30d3a2b289aaa6b363be25d2b295">RecurrenceSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191a73e34e9a7d2e062bb060ed4e7ade">FixedOrderRecurrences</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the phi nodes that are fixed-order recurrences. <a href="#a191a73e34e9a7d2e062bb060ed4e7ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721cfa46a725be4df869b2ae813b2220">WidestIndTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the widest induction type encountered. <a href="#a721cfa46a725be4df869b2ae813b2220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d7005ce88b86f4f401da73fe6b3deb">AllowedExit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allowed outside users. <a href="#aa6d7005ce88b86f4f401da73fe6b3deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationrequirements">LoopVectorizationRequirements</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd645b276e25a4f01514a0356d3c3384">Requirements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization requirements that will go through late-evaluation. <a href="#abd645b276e25a4f01514a0356d3c3384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3667ca6a2694b97d6fae411ab3a3c5fd">Hints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to emit an analysis of any legality issues. <a href="#a3667ca6a2694b97d6fae411ab3a3c5fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4b9d46b9523a6b927694ed619a5867">DB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The demanded bits analysis is used to compute the minimum type size in which a reduction can be computed. <a href="#adc4b9d46b9523a6b927694ed619a5867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860a8a7b7929889b96c26360e192e383">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The assumption cache analysis is used to compute the minimum type size in which a reduction can be computed. <a href="#a860a8a7b7929889b96c26360e192e383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afccd90bfd1e42ce5292774817868ad50">MaskedOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>While vectorizing these instructions we have to generate a call to the appropriate masked intrinsic or drop them in case of conditional assumes. <a href="#afccd90bfd1e42ce5292774817868ad50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/histograminfo">HistogramInfo</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585a359098cc54d37a1e25848125648d">Histograms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all identified histogram operations, which are sequences of load -&gt; update -&gt; store instructions where multiple lanes in a vector may work on the same memory location. <a href="#a585a359098cc54d37a1e25848125648d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc77083a325ee5d9e483dd5b4129a28">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BFI and PSI are used to check for profile guided size optimizations. <a href="#abfc77083a325ee5d9e483dd5b4129a28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6651b04bacfb0bbeca80220c9c106e43">PSI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a395814e2243de64a10a416dc8735f">VecCallVariantsFound</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we discover function calls within the loop which have a valid vectorized variant, record that fact so that LoopVectorize can (potentially) make a better decision on the maximum VF and enable the use of those function variants. <a href="#ab4a395814e2243de64a10a416dc8735f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e9e9e7a204e2a788f60c966c899e85">StructVecCallFound</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we find a call (to be vectorized) that returns a struct type, record that so we can bail out until this is supported. <a href="#aa1e9e9e7a204e2a788f60c966c899e85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d36674731fde829eee1057072582274">CountableExitingBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of all the countable and uncountable exiting blocks if the exact backedge taken count is not computable. <a href="#a2d36674731fde829eee1057072582274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde701a5f5765e682e8b4480ebae3be5">UncountableEdge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the loop edge to an uncountable exit, comprising a pair of (Exiting, Exit) blocks, if there is exactly one early exit. <a href="#adde701a5f5765e682e8b4480ebae3be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> checks if it is legal to vectorize a loop, and to what vectorization factor.</p>


<p>This class does not look at the profitability of vectorization, only the legality. This class has two main kinds of checks:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> checks - The code in canVectorizeMemory checks if vectorization will change the order of memory accesses in a way that will change the correctness of the program.</li>
<li>Scalars checks - The code in canVectorizeInstrs and canVectorizeMemory checks for a number of different conditions, such as the availability of a single induction variable, that all types are supported and vectorize-able, etc. This code reflects the capabilities of <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a>. This class is also used by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> for identifying induction variable and the different reduction variables.</li>
</ul>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InductionList {#a063c4d98febe7ef90dddbfedcfc59d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationLegality::InductionList =  MapVector&lt;PHINode *, InductionDescriptor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a063c4d98febe7ef90dddbfedcfc59d16">InductionList</a> saves induction variables and maps them to the induction descriptor.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### RecurrenceSet {#a543d30d3a2b289aaa6b363be25d2b295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationLegality::RecurrenceSet =  SmallPtrSet&lt;const PHINode *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a543d30d3a2b289aaa6b363be25d2b295">RecurrenceSet</a> contains the phi nodes that are recurrences other than inductions and reductions.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### ReductionList {#abe830a64fea7dbeee20cdda3726b0120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationLegality::ReductionList =  MapVector&lt;PHINode *, RecurrenceDescriptor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#abe830a64fea7dbeee20cdda3726b0120">ReductionList</a> contains the reduction descriptors for all of the reductions that were found in the loop.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopVectorizationLegality() {#a57ee5ed437953ba182781372d6a03fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizationLegality::LoopVectorizationLegality (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp; LAIs, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationrequirements">LoopVectorizationRequirements</a> * R, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> * H, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### blockNeedsPredication() {#a3b78b24a3c241e611957b82cd12640da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::blockNeedsPredication (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the block BB needs to be predicated in order for the loop to be vectorized.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#aa67d22298695c49e80b79cb8a271928b">llvm::LoopAccessInfo::blockNeedsPredication</a>, <a href="#ae1727fd1036f0c932cae65a5b5db5a0d">getUncountableEarlyExitingBlock</a>, <a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">hasUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>


<p>Referenced by <a href="#ac562402715584ed9e836026bae1ac150">isUniformMemOp</a>.</p>

</div>
</div>

### canFoldTailByMasking() {#aafa8144325b3c584e828b07d73a8cb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canFoldTailByMasking ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can vectorize this loop while folding its tail by masking.</p>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8dffddf3feec953bba0425b324b380dc">getInductionVars</a>, <a href="#aa31c04881c640716da40ae22ddda69ad">getReductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### canVectorize() {#a3ce10d1174bdfcac2b73ed7efa352b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorize (bool UseVPlanNativePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is legal to vectorize this loop.</p>


<p>This does not mean that it is profitable to vectorize this loop, only that it is legal to do so. Temporarily taking UseVPlanNativePath parameter. If true, take the new code path being implemented for outer loop vectorization (should be functional for inner loop vectorization) based on <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. If false, good old LV code.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a1692f783b14148757cae5bcb6ece48c3">PragmaVectorizeSCEVCheckThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#ac43b82ae3bb3c5acae897a8b18c0d3fc">VectorizeSCEVCheckThreshold</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### canVectorizeFPMath() {#a552a158f5a673da0a26461d1471cea41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeFPMath (bool EnableStrictReductions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is legal to vectorize the FP math operations in this loop.</p>


<p>Vectorizing is legal if we allow reordering of FP operations, or if we can use in-order reductions.</p>


<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#aee5a5c8071e7352a9ec7199bca954882">llvm::InductionDescriptor::getExactFPMathInst</a>, <a href="#a8dffddf3feec953bba0425b324b380dc">getInductionVars</a>, <a href="#aa31c04881c640716da40ae22ddda69ad">getReductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a25187781de77a2ccf8406804fe510ce8">llvm::RecurrenceDescriptor::hasExactFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a8dad5abc2bd929acd8391643b2dbe4c5">llvm::RecurrenceDescriptor::isOrdered</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### getAssumptionCache() {#a4b011656b75317bd3e291ef771491f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache * llvm::LoopVectorizationLegality::getAssumptionCache ()</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getCountableExitingBlocks() {#a7a32abdcf9e80b2483aa55bc36f2840e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVector&lt; BasicBlock *, 4 &gt; &amp; llvm::LoopVectorizationLegality::getCountableExitingBlocks ()</td>
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

<p>Returns all exiting blocks with a countable exit, i.e.</p>


<p>the exit-not-taken count is known exactly at compile time.</p>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### getDominatorTree() {#a3add6f3f23fa2ec67277682de9acef7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree * llvm::LoopVectorizationLegality::getDominatorTree ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getFixedOrderRecurrences() {#a317c5bedc82363ee7513fe56790878e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceSet &amp; llvm::LoopVectorizationLegality::getFixedOrderRecurrences ()</td>
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

<p>Return the fixed-order recurrences found in the loop.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getHistogramInfo() {#a4f5c51eb16a87d311cfebdceb7b04ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const HistogramInfo * &gt; llvm::LoopVectorizationLegality::getHistogramInfo (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Returns a HistogramInfo* for the given instruction if it was determined to be part of a load -&gt; update -&gt; store sequence where multiple lanes may be working on the same memory address.</p>

<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getInductionVars() {#a8dffddf3feec953bba0425b324b380dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InductionList &amp; llvm::LoopVectorizationLegality::getInductionVars ()</td>
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

<p>Returns the induction variables found in the loop.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="#aafa8144325b3c584e828b07d73a8cb25">canFoldTailByMasking</a>, <a href="#a552a158f5a673da0a26461d1471cea41">canVectorizeFPMath</a>, <a href="#a74bcb5c6d80d9d7fb0eeb1131eeef2dc">getIntOrFpInductionDescriptor</a> and <a href="#a728069d0bcacf976cbb3764bad749562">getPointerInductionDescriptor</a>.</p>

</div>
</div>

### getIntOrFpInductionDescriptor() {#a74bcb5c6d80d9d7fb0eeb1131eeef2dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InductionDescriptor * llvm::LoopVectorizationLegality::getIntOrFpInductionDescriptor (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the induction descriptor, if <span class="doxyComputerOutput">Phi</span> is an integer or floating point induction.</p>

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="#a8dffddf3feec953bba0425b324b380dc">getInductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccab0b71801de025f26b088a8cb22825f79">llvm::InductionDescriptor::IK_FpInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccaf0191e822c9708e106d7bb58aa9ec947">llvm::InductionDescriptor::IK_IntInduction</a> and <a href="#a7803d6f1162773c3b1a61e3ff441fcb8">isInductionPhi</a>.</p>

</div>
</div>

### getLAI() {#ab5632546144c4db5bbe1f975aeebd9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo * llvm::LoopVectorizationLegality::getLAI ()</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### getLoop() {#ae2bbeec474957c61045c6cb37f2d8379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::LoopVectorizationLegality::getLoop ()</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getLoopInfo() {#a13545e37bc06efcf7642cfda97c65bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo * llvm::LoopVectorizationLegality::getLoopInfo ()</td>
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



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getMaxSafeVectorWidthInBits() {#a2551d678f358fcb0f498224876f58673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LoopVectorizationLegality::getMaxSafeVectorWidthInBits ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### getNumLoads() {#aa9d35bb02e49c20fcafc8d179559da10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizationLegality::getNumLoads ()</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### getNumStores() {#a0f59a9c87ede76fde54388f16562a930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizationLegality::getNumStores ()</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### getPointerInductionDescriptor() {#a728069d0bcacf976cbb3764bad749562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InductionDescriptor * llvm::LoopVectorizationLegality::getPointerInductionDescriptor (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the induction descriptor, if <span class="doxyComputerOutput">Phi</span> is pointer induction.</p>

<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="#a8dffddf3feec953bba0425b324b380dc">getInductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccab61689ca7d0a024fc4ff52a74d691ae2">llvm::InductionDescriptor::IK_PtrInduction</a> and <a href="#a7803d6f1162773c3b1a61e3ff441fcb8">isInductionPhi</a>.</p>

</div>
</div>

### getPredicatedScalarEvolution() {#a3ecfb3b35e9665ce1444966f8ae0930f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution * llvm::LoopVectorizationLegality::getPredicatedScalarEvolution ()</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getPrimaryInduction() {#a78dab1aa1facf4bf6300b3275490fa11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * llvm::LoopVectorizationLegality::getPrimaryInduction ()</td>
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

<p>Returns the primary induction variable.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### getReductionVars() {#aa31c04881c640716da40ae22ddda69ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ReductionList &amp; llvm::LoopVectorizationLegality::getReductionVars ()</td>
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

<p>Returns the reduction variables found in the loop.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="#aafa8144325b3c584e828b07d73a8cb25">canFoldTailByMasking</a>, <a href="#a552a158f5a673da0a26461d1471cea41">canVectorizeFPMath</a>, <a href="#a34f384c7ff8e4b23cc79156daf2a5c11">isInvariantAddressOfReduction</a>, <a href="#a1c9fd1c0627dfa3e013a1b2c7416ae90">isInvariantStoreOfReduction</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getRuntimePointerChecking() {#af15a090796e9a873af5163ba057f4c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RuntimePointerChecking * llvm::LoopVectorizationLegality::getRuntimePointerChecking ()</td>
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

<p>Returns the information that we collected about runtime memory check.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### getScalarEvolution() {#abf6b349a0e6598527d2ea3ef89dba230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution * llvm::LoopVectorizationLegality::getScalarEvolution ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a8ac11c0decb75671fa7087748d32c156">llvm::ARMTTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### getUncountableEarlyExitBlock() {#a64fd596d86681aff77584c0fd661f18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::LoopVectorizationLegality::getUncountableEarlyExitBlock ()</td>
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

<p>Returns the destination of the uncountable early exiting block, if there is exactly one.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="#ad9e8b4a71d2eb63862cf0dfcb0e7d786">getUncountableEdge</a> and <a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">hasUncountableEarlyExit</a>.</p>

</div>
</div>

### getUncountableEarlyExitingBlock() {#ae1727fd1036f0c932cae65a5b5db5a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::LoopVectorizationLegality::getUncountableEarlyExitingBlock ()</td>
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

<p>Returns the uncountable early exiting block, if there is exactly one.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="#ad9e8b4a71d2eb63862cf0dfcb0e7d786">getUncountableEdge</a> and <a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">hasUncountableEarlyExit</a>.</p>


<p>Referenced by <a href="#a3b78b24a3c241e611957b82cd12640da">blockNeedsPredication</a>.</p>

</div>
</div>

### getUncountableEdge() {#ad9e8b4a71d2eb63862cf0dfcb0e7d786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; BasicBlock *, BasicBlock * &gt; &gt; llvm::LoopVectorizationLegality::getUncountableEdge ()</td>
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

<p>Returns the loop edge to an uncountable exit, or std::nullopt if there isn't a single such edge.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="#a64fd596d86681aff77584c0fd661f18a">getUncountableEarlyExitBlock</a>, <a href="#ae1727fd1036f0c932cae65a5b5db5a0d">getUncountableEarlyExitingBlock</a> and <a href="#ab22ff9e23f7f27234c8f6ec76db0c1f3">hasUncountableEarlyExit</a>.</p>

</div>
</div>

### getWidestInductionType() {#ab1bbdeff3d286d3cd7a6e1f67a7e43ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::LoopVectorizationLegality::getWidestInductionType ()</td>
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

<p>Returns the widest induction type.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### hasHistograms() {#ab306c8094bdb8c7cbdbdfb9a05800007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::hasHistograms ()</td>
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

<p>Returns a list of all known histogram operations in the loop.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### hasStructVectorCall() {#a9ede4d70a86b91ae038a77c86b3f4aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::hasStructVectorCall ()</td>
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

<p>Returns true if there is at least one function call in the loop which returns a struct type and needs to be vectorized.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### hasUncountableEarlyExit() {#ab22ff9e23f7f27234c8f6ec76db0c1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::hasUncountableEarlyExit ()</td>
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

<p>Returns true if the loop has exactly one uncountable early exit, i.e.</p>


<p>an uncountable exit that isn't the latch block.</p>


<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Reference <a href="#ad9e8b4a71d2eb63862cf0dfcb0e7d786">getUncountableEdge</a>.</p>


<p>Referenced by <a href="#a3b78b24a3c241e611957b82cd12640da">blockNeedsPredication</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="#a64fd596d86681aff77584c0fd661f18a">getUncountableEarlyExitBlock</a>, <a href="#ae1727fd1036f0c932cae65a5b5db5a0d">getUncountableEarlyExitingBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### hasVectorCallVariants() {#a23ba553cf7c1e1b64bbf9d30eb540234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::hasVectorCallVariants ()</td>
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

<p>Returns true if there is at least one function call in the loop which has a vectorized variant available.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### isCastedInductionVariable() {#afd0c0e675aff7e870f18b9c911977b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isCastedInductionVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if V is a cast that is part of an induction def-use chain, and had been proven to be redundant under a runtime guard (in other words, the cast has the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression as the induction phi).</p>

<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#af9f3d6495086eb1a43e829bf045fd073">isInductionVariable</a>.</p>

</div>
</div>

### isConsecutivePtr() {#a4589ea484ebe1919b451fff3948a17cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LoopVectorizationLegality::isConsecutivePtr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this pointer is consecutive when vectorizing.</p>


<p>This happens when the last index of the GEP is the induction variable, or that the pointer itself is an induction variable. This check allows us to vectorize A[idx] into a wide load/store. Returns: 0 - Stride is unknown or non-consecutive. 1 - Address is consecutive. -1 - Address is consecutive, and decreasing. NOTE: This method must only be used before modifying the original scalar loop. Do not use after invoking 'createVectorizedLoopSkeleton' (PR34965).</p>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea089e7eb4db258e05f70eef4ed5aa10bb">llvm::IRPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>

</div>
</div>

### isFixedOrderRecurrence() {#a5d6b8f1a562e7d26404946de46d3045b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isFixedOrderRecurrence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if Phi is a fixed-order recurrence in this loop.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### isInductionPhi() {#a7803d6f1162773c3b1a61e3ff441fcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isInductionPhi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if V is a Phi node of an induction variable in this loop.</p>

<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>.</p>


<p>Referenced by <a href="#a74bcb5c6d80d9d7fb0eeb1131eeef2dc">getIntOrFpInductionDescriptor</a>, <a href="#a728069d0bcacf976cbb3764bad749562">getPointerInductionDescriptor</a> and <a href="#af9f3d6495086eb1a43e829bf045fd073">isInductionVariable</a>.</p>

</div>
</div>

### isInductionVariable() {#af9f3d6495086eb1a43e829bf045fd073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isInductionVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if V can be considered as an induction variable in this loop.</p>


<p>V can be the induction phi, or some redundant cast in the def-use chain of the inducion phi.</p>


<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="#afd0c0e675aff7e870f18b9c911977b7a">isCastedInductionVariable</a> and <a href="#a7803d6f1162773c3b1a61e3ff441fcb8">isInductionPhi</a>.</p>

</div>
</div>

### isInvariant() {#aa10b9dac96a36c8b4da25fc6fa1d4352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isInvariant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">V</span> is invariant across all loop iterations according to <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>Referenced by <a href="#a86e581cb8e98cb0649e8b524eed5c9c0">isUniform</a>.</p>

</div>
</div>

### isInvariantAddressOfReduction() {#a34f384c7ff8e4b23cc79156daf2a5c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isInvariantAddressOfReduction (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if given address is invariant and is used to store recurrent expression.</p>

<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aefb15964facf7f35f22a6e8a7fb67285">llvm::StoreInst::getPointerOperand</a>, <a href="#aa31c04881c640716da40ae22ddda69ad">getReductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a9e4044de402972428a2101b8afcaa1b7">llvm::RecurrenceDescriptor::IntermediateStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>.</p>

</div>
</div>

### isInvariantStoreOfReduction() {#a1c9fd1c0627dfa3e013a1b2c7416ae90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isInvariantStoreOfReduction (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns True if given store is a final invariant store of one of the reductions found in the loop.</p>

<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#aa31c04881c640716da40ae22ddda69ad">getReductionVars</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a9e4044de402972428a2101b8afcaa1b7">llvm::RecurrenceDescriptor::IntermediateStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>.</p>

</div>
</div>

### isMaskRequired() {#af0ced1e23ba4d4a56286b5f17f448ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isMaskRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Returns true if vector representation of the instruction <span class="doxyComputerOutput">I</span> requires mask.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isReductionVariable() {#a5c26e54d871c42c42dc62f9d449c633a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isReductionVariable (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
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

<p>Returns True if PN is a reduction variable in this loop.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### isSafeForAnyVectorWidth() {#aa6717c9edc2614476ebb19bd73e8bcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isSafeForAnyVectorWidth ()</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### isUniform() {#a86e581cb8e98cb0649e8b524eed5c9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isUniform (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if value V is uniform across <span class="doxyComputerOutput">VF</span> lanes, when <span class="doxyComputerOutput">VF</span> is provided, and otherwise if <span class="doxyComputerOutput">V</span> is invariant across all loop iterations.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa10b9dac96a36c8b4da25fc6fa1d4352">isInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="#ac562402715584ed9e836026bae1ac150">isUniformMemOp</a>.</p>

</div>
</div>

### isUniformMemOp() {#ac562402715584ed9e836026bae1ac150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isUniformMemOp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A uniform memory op is a load or store which accesses the same memory location on all <span class="doxyComputerOutput">VF</span> lanes, if <span class="doxyComputerOutput">VF</span> is provided and otherwise if the memory location is invariant.</p>

<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="#a3b78b24a3c241e611957b82cd12640da">blockNeedsPredication</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a86e581cb8e98cb0649e8b524eed5c9c0">isUniform</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### prepareToFoldTailByMasking() {#ab0b7c658c190bc113272ef4257a47659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationLegality::prepareToFoldTailByMasking ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark all respective loads/stores for masking.</p>


<p>Must only be called when tail-folding is possible.</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1937 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addInductionPhi() {#a7c97b098510b893ff3c16829cfa78f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationLegality::addInductionPhi (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AllowedExit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the vectorization state by adding <span class="doxyComputerOutput">Phi</span> to the inductions list.</p>


<p>This can set <span class="doxyComputerOutput">Phi</span> as the main induction of the loop if <span class="doxyComputerOutput">Phi</span> is a better choice for the main induction than the existing one.</p>


<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### blockCanBePredicated() {#aeb9b746c802505da2247f2d2252b6b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::blockCanBePredicated (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; SafePtrs, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; MaskedOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all of the instructions in the block can be speculatively executed, and record the loads/stores that require masking.</p>


<p><span class="doxyComputerOutput">SafePtrs</span> is a list of addresses that are known to be legal and we know that we can read from them without segfault. <span class="doxyComputerOutput">MaskedOp</span> is a list of instructions that have to be transformed into calls to the appropriate masked intrinsic when the loop is vectorized or dropped if the instruction is a conditional assume intrinsic.</p>


<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeIndirectUnsafeDependences() {#a05fda32a2e1807a0b70938d95a27c2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeIndirectUnsafeDependences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If LAA cannot determine whether all dependences are safe, we may be able to further analyse some IndirectUnsafe dependences and if they match a certain pattern (like a histogram) then we may still be able to vectorize.</p>

<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeInstrs() {#aba58236b7663ae958f41a085233e758a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeInstrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a single basic block loop is vectorizable.</p>


<p>At this point we know that this is a loop with a constant trip count and we only need to check individual instructions.</p>


<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeLoopCFG() {#adb63ada87ea6eadc31ce33747903538f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeLoopCFG (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Lp, bool UseVPlanNativePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the pre-header, exiting and latch blocks of <span class="doxyComputerOutput">Lp</span> (non-recursive) are considered legal for vectorization.</p>


<p>Temporarily taking UseVPlanNativePath parameter. If true, take the new code path being implemented for outer loop vectorization (should be functional for inner loop vectorization) based on <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. If false, good old LV code.</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeLoopNestCFG() {#a9a41b60d10bc31461995d56e5e05d8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeLoopNestCFG (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Lp, bool UseVPlanNativePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the pre-header, exiting and latch blocks of <span class="doxyComputerOutput">Lp</span> and all its nested loops are considered legal for vectorization.</p>


<p>These legal checks are common for inner and outer loop vectorization. Temporarily taking UseVPlanNativePath parameter. If true, take the new code path being implemented for outer loop vectorization (should be functional for inner loop vectorization) based on <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. If false, good old LV code.</p>


<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1586 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeMemory() {#a637e3ecb85b6fff4f0f166d67f45c270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When we vectorize loops we may change the order in which we read and write from memory.</p>


<p>This method checks if it is legal to vectorize the code, considering only memory constrains. Returns true if the loop is vectorizable</p>


<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeOuterLoop() {#a9c5aafa99304a61bb2e13f6c2bd25a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeOuterLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can vectorize this outer loop.</p>


<p>The method performs specific checks for outer loop vectorization.</p>


<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### canVectorizeWithIfConvert() {#ae6a5ae24d98b624801fe6776da7e47dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::canVectorizeWithIfConvert ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can vectorize this loop using the IF-conversion transformation.</p>

<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### isVectorizableEarlyExitLoop() {#a0961a8a5109f7d5c34a2313293e602e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::isVectorizableEarlyExitLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is an early exit loop that can be vectorized.</p>


<p>Currently, a loop with an uncountable early exit is considered vectorizable if:</p>


<ol class="doxyList" type="1">
<li>There are no writes to memory in the loop.</li>
<li>The loop has only one early uncountable exit</li>
<li>The early exit block dominates the latch block.</li>
<li>The latch block has an exact exit count.</li>
<li>The loop does not contain reductions or recurrences.</li>
<li>We can prove at compile-time that loops will not contain faulting loads.</li>
<li>It is safe to speculatively execute instructions such as divide or call instructions. The list above is not based on theoretical limitations of vectorization, but simply a statement that more work is needed to support these additional cases safely.</li>
</ol>

<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 1612 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### setupOuterLoopInductions() {#aa2be4e9ca1d89ddb6724948c0dfc57d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::setupOuterLoopInductions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up outer loop inductions by checking Phis in outer loop header for supported inductions (int inductions).</p>


<p>Return false if any of these Phis is not a supported induction or if we fail to find an induction.</p>


<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a860a8a7b7929889b96c26360e192e383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::LoopVectorizationLegality::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The assumption cache analysis is used to compute the minimum type size in which a reduction can be computed.</p>

<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### AllowedExit {#aa6d7005ce88b86f4f401da73fe6b3deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value *, 4&gt; llvm::LoopVectorizationLegality::AllowedExit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allowed outside users.</p>


<p>This holds the variables that can be accessed from outside the loop.</p>


<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### BFI {#abfc77083a325ee5d9e483dd5b4129a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::LoopVectorizationLegality::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BFI and PSI are used to check for profile guided size optimizations.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### CountableExitingBlocks {#a2d36674731fde829eee1057072582274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 4&gt; llvm::LoopVectorizationLegality::CountableExitingBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of all the countable and uncountable exiting blocks if the exact backedge taken count is not computable.</p>

<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### DB {#adc4b9d46b9523a6b927694ed619a5867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DemandedBits* llvm::LoopVectorizationLegality::DB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The demanded bits analysis is used to compute the minimum type size in which a reduction can be computed.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### DT {#a27b56d32f00a7726f94dfa06ed752670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::LoopVectorizationLegality::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dominator Tree.</p>

<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### FixedOrderRecurrences {#a191a73e34e9a7d2e062bb060ed4e7ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceSet llvm::LoopVectorizationLegality::FixedOrderRecurrences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the phi nodes that are fixed-order recurrences.</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Hints {#a3667ca6a2694b97d6fae411ab3a3c5fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizeHints* llvm::LoopVectorizationLegality::Hints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to emit an analysis of any legality issues.</p>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Histograms {#a585a359098cc54d37a1e25848125648d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;HistogramInfo, 1&gt; llvm::LoopVectorizationLegality::Histograms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains all identified histogram operations, which are sequences of load -&gt; update -&gt; store instructions where multiple lanes in a vector may work on the same memory location.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### InductionCastsToIgnore {#a4a4f19197a92484b208fc2bfe0aca7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 4&gt; llvm::LoopVectorizationLegality::InductionCastsToIgnore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds all the casts that participate in the update chain of the induction variables, and that have been proven to be redundant (possibly under a runtime guard).</p>


<p>These casts can be ignored when creating the vectorized loop body.</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Inductions {#a051d230e9e98d92f852cfd260bb5e9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InductionList llvm::LoopVectorizationLegality::Inductions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds all of the induction variables that we found in the loop.</p>


<p>Notice that inductions don't need to start at zero and that induction variables can be pointers.</p>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### LAI {#aaca72182d1d5250777d463e2254ed8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo* llvm::LoopVectorizationLegality::LAI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### LAIs {#a9867aa9ca1a32c23a5c99862d1699bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAccessInfoManager&amp; llvm::LoopVectorizationLegality::LAIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### LI {#aecb9b6635ed708773bc9c079fc10cb1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopVectorizationLegality::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis.</p>

<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### MaskedOp {#afccd90bfd1e42ce5292774817868ad50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Instruction *, 8&gt; llvm::LoopVectorizationLegality::MaskedOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>While vectorizing these instructions we have to generate a call to the appropriate masked intrinsic or drop them in case of conditional assumes.</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### ORE {#a1dd8f7c0effe71c22a81569e18560945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::LoopVectorizationLegality::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface to emit optimization remarks.</p>

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### PrimaryInduction {#a09ebbb2516317552943315010ba587c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* llvm::LoopVectorizationLegality::PrimaryInduction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the primary induction variable.</p>


<p>This is the counter of the loop.</p>


<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### PSE {#a3bdd6f36c94c7915cb98d7ad501a49be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::LoopVectorizationLegality::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks.</p>


<p>Applies dynamic knowledge to simplify <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions in the context of existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> assumptions. The analysis will also add a minimal set of new predicates if this is required to enable vectorization and unrolling.</p>


<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### PSI {#a6651b04bacfb0bbeca80220c9c106e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::LoopVectorizationLegality::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Reductions {#ac847a2194c17711fa779faf681db9633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReductionList llvm::LoopVectorizationLegality::Reductions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the reduction variables.</p>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Requirements {#abd645b276e25a4f01514a0356d3c3384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationRequirements* llvm::LoopVectorizationLegality::Requirements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization requirements that will go through late-evaluation.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### StructVecCallFound {#aa1e9e9e7a204e2a788f60c966c899e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::StructVecCallFound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we find a call (to be vectorized) that returns a struct type, record that so we can bail out until this is supported.</p>


<p>TODO: Remove this flag once vectorizing calls with struct returns is supported.</p>


<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### TheLoop {#a3808cce17fc47f8edd58849af507fc2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LoopVectorizationLegality::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop that we evaluate.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### TLI {#aa863ed59572b0d4943ce4cce06179f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* llvm::LoopVectorizationLegality::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info.</p>

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### TTI {#acaaacd1e1d906e11bdf1f8b6fb7c91b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* llvm::LoopVectorizationLegality::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info.</p>

<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### UncountableEdge {#adde701a5f5765e682e8b4480ebae3be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::pair&lt;BasicBlock *, BasicBlock *&gt; &gt; llvm::LoopVectorizationLegality::UncountableEdge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the loop edge to an uncountable exit, comprising a pair of (Exiting, Exit) blocks, if there is exactly one early exit.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### VecCallVariantsFound {#ab4a395814e2243de64a10a416dc8735f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationLegality::VecCallVariantsFound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we discover function calls within the loop which have a valid vectorized variant, record that fact so that LoopVectorize can (potentially) make a better decision on the maximum VF and enable the use of those function variants.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### WidestIndTy {#a721cfa46a725be4df869b2ae813b2220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::LoopVectorizationLegality::WidestIndTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the widest induction type encountered.</p>

<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
