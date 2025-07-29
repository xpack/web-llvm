---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-objcarcopts-cpp-/objcarcopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjCARCOpt` Class

<p>The main ARC optimization pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ObjCARCOpts.cpp}::ObjCARCOpt { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cda1b8e595016dcd88239ffa731aa87">hasCFGChanged</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gac7ff3521e7b4b50e8db182392234aefb">init</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga2542f915a6ba493b029cfe3ffc5f4a44">run</a> (Function &amp;F, AAResults &amp;AA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362019b54e8e6b3ebc579afb2d63cd94">addOpBundleForFunclet</a> (BasicBlock *BB, SmallVectorImpl&lt; OperandBundleDef &gt; &amp;OpBundles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gab7467c68650a8dc6d24fe9c344c04085">OptimizeRetainRVCall</a> (Function &amp;F, Instruction *RetainRV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn objc_retainAutoreleasedReturnValue into objc_retain if the operand is not a return value. <a href="/web-llvm/docs/api/groups/arcopt/#gab7467c68650a8dc6d24fe9c344c04085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga789b4bb09ba9b36d0c886628e1bb15b4">OptimizeAutoreleaseRVCall</a> (Function &amp;F, Instruction *AutoreleaseRV, ARCInstKind &amp;Class)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn objc_autoreleaseReturnValue into objc_autorelease if the result is not used as a return value. <a href="/web-llvm/docs/api/groups/arcopt/#ga789b4bb09ba9b36d0c886628e1bb15b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gad642d84f3331bef3c9017bd93a4bb3c1">OptimizeIndividualCalls</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit each call, one at a time, and make simplifications without doing any additional analysis. <a href="/web-llvm/docs/api/groups/arcopt/#gad642d84f3331bef3c9017bd93a4bb3c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga28da34b57036ba57baef3cddd26e041b">OptimizeIndividualCallImpl</a> (Function &amp;F, Instruction *Inst, ARCInstKind Class, const Value *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize an individual call, optionally passing the GetArgRCIdentityRoot if it has already been computed. <a href="/web-llvm/docs/api/groups/arcopt/#ga28da34b57036ba57baef3cddd26e041b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga8f7f9f59fd3284f07c06f5c01f41b24e">OptimizeInlinedAutoreleaseRVCall</a> (Function &amp;F, Instruction *Inst, const Value *&amp;Arg, ARCInstKind Class, Instruction *AutoreleaseRV, const Value *&amp;AutoreleaseRVArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to optimize an AutoreleaseRV with a RetainRV or UnsafeClaimRV. <a href="/web-llvm/docs/api/groups/arcopt/#ga8f7f9f59fd3284f07c06f5c01f41b24e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gaf6c4b98c71372c90ba7d4323316aaeb6">CheckForCFGHazards</a> (const BasicBlock *BB, DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, BBState &amp;MyStates) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check for critical edges, loop boundaries, irreducible control flow, or other CFG structures where moving code across the edge would result in it being executed more. <a href="/web-llvm/docs/api/groups/arcopt/#gaf6c4b98c71372c90ba7d4323316aaeb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga07b42ef98233c8d32f13f0f179293e15">VisitInstructionBottomUp</a> (Instruction *Inst, BasicBlock *BB, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains, BBState &amp;MyStates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga4c5a52fd57476e00ca45107d7681fc98">VisitBottomUp</a> (BasicBlock *BB, DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gac1b237a7d98a4fa9c498cba32f750522">VisitInstructionTopDown</a> (Instruction *Inst, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases, BBState &amp;MyStates, const DenseMap&lt; const Instruction *, SmallPtrSet&lt; const Value *, 2 &gt; &gt; &amp;ReleaseInsertPtToRCIdentityRoots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga97599c8d224562be41d25da7490d2dcb">VisitTopDown</a> (BasicBlock *BB, DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases, const DenseMap&lt; const Instruction *, SmallPtrSet&lt; const Value *, 2 &gt; &gt; &amp;ReleaseInsertPtToRCIdentityRoots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga58998e72652db416dd2381807603103d">Visit</a> (Function &amp;F, DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gadd0be10d4ed97ef03585c430ee176b39">MoveCalls</a> (Value *Arg, RRInfo &amp;RetainsToMove, RRInfo &amp;ReleasesToMove, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases, SmallVectorImpl&lt; Instruction * &gt; &amp;DeadInsts, Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the calls in RetainsToMove and ReleasesToMove. <a href="/web-llvm/docs/api/groups/arcopt/#gadd0be10d4ed97ef03585c430ee176b39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga5730adc5874d253abd9594a54df0a145">PairUpRetainsAndReleases</a> (DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases, Module *M, Instruction *Retain, SmallVectorImpl&lt; Instruction * &gt; &amp;DeadInsts, RRInfo &amp;RetainsToMove, RRInfo &amp;ReleasesToMove, Value *Arg, bool KnownSafe, bool &amp;AnyPairsCompletelyEliminated)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gad0e6eeb68f71d137154365fe0d0df88e">PerformCodePlacement</a> (DenseMap&lt; const BasicBlock *, BBState &gt; &amp;BBStates, BlotMapVector&lt; Value *, RRInfo &gt; &amp;Retains, DenseMap&lt; Value *, RRInfo &gt; &amp;Releases, Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify pairings between the retains and releases, and delete and/or move them. <a href="/web-llvm/docs/api/groups/arcopt/#gad0e6eeb68f71d137154365fe0d0df88e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga251a26cf11f57d784541bafc65474684">OptimizeWeakCalls</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Weak pointer optimizations. <a href="/web-llvm/docs/api/groups/arcopt/#ga251a26cf11f57d784541bafc65474684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga2fa441bc384c700bfd185cadd4dbc757">OptimizeSequences</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify program paths which execute sequences of retains and releases which can be eliminated. <a href="/web-llvm/docs/api/groups/arcopt/#ga2fa441bc384c700bfd185cadd4dbc757">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga5cc373beaa944f9c5e2d97ba0afd9eee">OptimizeReturns</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for this pattern: <a href="/web-llvm/docs/api/groups/arcopt/#ga5cc373beaa944f9c5e2d97ba0afd9eee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gac805062560f638e214410a27e94c4398">GatherStatistics</a> (Function &amp;F, bool AfterOptimization=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59aa3dbd8a4e0dd759a596add7b3c3f">Changed</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf265a549d81f3bba9f202b47ba0280">CFGChanged</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567ad30d7e9cd356f717dc87256acd8e">PA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/arcruntimeentrypoints">ARCRuntimeEntryPoints</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ec23b78386984cf7c88a29e5e85dde">EP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A cache of references to runtime entry point constants. <a href="#ad8ec23b78386984cf7c88a29e5e85dde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/arcmdkindcache">ARCMDKindCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74faf64be55a01a566c72904003ea726">MDKindCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A cache of MDKinds that can be passed into other functions to propagate MDKind identifiers. <a href="#a74faf64be55a01a566c72904003ea726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs">BundledRetainClaimRVs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a834c97fcdbbcaf41483900b0c011f3de">BundledInsts</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b22c762489dfdc3ea03bc6768bd53d">DisableRetainReleasePairing</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A flag indicating whether the optimization that removes or moves retain/release pairs should be performed. <a href="#ad0b22c762489dfdc3ea03bc6768bd53d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a42fad9d34697ab7047990316c6409">UsedInThisFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags which determine whether each of the interesting runtime functions is in fact used in the current function. <a href="#a24a42fad9d34697ab7047990316c6409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2f1c6ef1b87665f97c6540b46565fa">BlockEHColors</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3706ff978b1b5a0391e81f69b2fc5ee">cloneOpBundlesIf</a> (CallBase *CI, SmallVectorImpl&lt; OperandBundleDef &gt; &amp;OpBundles, PredicateT Predicate)</td>
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

<p>The main ARC optimization pass.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### hasCFGChanged() {#a9cda1b8e595016dcd88239ffa731aa87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::hasCFGChanged ()</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addOpBundleForFunclet() {#a362019b54e8e6b3ebc579afb2d63cd94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::addOpBundleForFunclet (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; &amp; OpBundles)</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockEHColors {#a0d2f1c6ef1b87665f97c6540b46565fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, ColorVector&gt; anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::BlockEHColors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### BundledInsts {#a834c97fcdbbcaf41483900b0c011f3de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BundledRetainClaimRVs* anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::BundledInsts = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### CFGChanged {#a6bf265a549d81f3bba9f202b47ba0280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::CFGChanged = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### Changed {#aa59aa3dbd8a4e0dd759a596add7b3c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::Changed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### DisableRetainReleasePairing {#ad0b22c762489dfdc3ea03bc6768bd53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::DisableRetainReleasePairing = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A flag indicating whether the optimization that removes or moves retain/release pairs should be performed.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### EP {#ad8ec23b78386984cf7c88a29e5e85dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARCRuntimeEntryPoints anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::EP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A cache of references to runtime entry point constants.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### MDKindCache {#a74faf64be55a01a566c72904003ea726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARCMDKindCache anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::MDKindCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A cache of MDKinds that can be passed into other functions to propagate MDKind identifiers.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### PA {#a567ad30d7e9cd356f717dc87256acd8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProvenanceAnalysis anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::PA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### UsedInThisFunction {#a24a42fad9d34697ab7047990316c6409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::UsedInThisFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags which determine whether each of the interesting runtime functions is in fact used in the current function.</p>

<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### cloneOpBundlesIf() {#ad3706ff978b1b5a0391e81f69b2fc5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::ObjCARCOpt::cloneOpBundlesIf (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; &amp; OpBundles, PredicateT Predicate)</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
