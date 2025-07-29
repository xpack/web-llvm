---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dependenceinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DependenceInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> - This class is the main dependence-analysis driver. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DependenceInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">llvm/Analysis/DependenceAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0908efeae361bba872b8d4abd6eccd">DependenceInfo</a> (Function *F, AAResults *AA, ScalarEvolution *SE, LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d6c1036e234fab6e63803cf9fb62de">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle transitive invalidation when the cached analysis results go away. <a href="#a10d6c1036e234fab6e63803cf9fb62de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49197b24cced248bed2d2c89c641a6dd">depends</a> (Instruction *Src, Instruction *Dst, bool PossiblyLoopIndependent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>depends - Tests for a dependence between the Src and Dst instructions. <a href="#a49197b24cced248bed2d2c89c641a6dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110f1f473cbb5a42bf9c82973ac9101c">getSplitIteration</a> (const Dependence &amp;Dep, unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSplitIteration - Give a dependence that's splittable at some particular level, return the iteration that should be used to split the loop. <a href="#a110f1f473cbb5a42bf9c82973ac9101c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4009b44221972360b0b0fb7dbf1cc7f0">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8187e3f7370e0b7bf547022cca10ab0f">establishNestingLevels</a> (const Instruction *Src, const Instruction *Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>establishNestingLevels - Examines the loop nesting of the Src and Dst instructions and establishes their shared loops. <a href="#a8187e3f7370e0b7bf547022cca10ab0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b8e5845abe1a12797ebe585950179d">mapSrcLoop</a> (const Loop *SrcLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mapSrcLoop - Given one of the loops containing the source, return its level index in our numbering scheme. <a href="#a11b8e5845abe1a12797ebe585950179d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f58754d78853e54bb6f61eab7542bf">mapDstLoop</a> (const Loop *DstLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mapDstLoop - Given one of the loops containing the destination, return its level index in our numbering scheme. <a href="#a78f58754d78853e54bb6f61eab7542bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9752863bb26b814a11e51a43b61c0bfd">isLoopInvariant</a> (const SCEV *Expression, const Loop *LoopNest) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLoopInvariant - Returns true if <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> is loop invariant in <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a>. <a href="#a9752863bb26b814a11e51a43b61c0bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcdf9b5f618c4f0a8e6a2761c7bff25">unifySubscriptType</a> (ArrayRef&lt; Subscript * &gt; Pairs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes sure all subscript pairs share the same integer type by sign-extending as necessary. <a href="#a5bcdf9b5f618c4f0a8e6a2761c7bff25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43098cff2af7676a39ac58e5eadaf172">removeMatchingExtensions</a> (Subscript *Pair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeMatchingExtensions - Examines a subscript pair. <a href="#a43098cff2af7676a39ac58e5eadaf172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c7c35b5f98be112979b5281badef35">collectCommonLoops</a> (const SCEV *Expression, const Loop *LoopNest, SmallBitVector &amp;Loops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>collectCommonLoops - Finds the set of loops from the <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> that have a level &lt;= CommonLevels and are referred to by the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a>. <a href="#a67c7c35b5f98be112979b5281badef35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e43032feb7097dc426ebe3d8e39669">checkSrcSubscript</a> (const SCEV *Src, const Loop *LoopNest, SmallBitVector &amp;Loops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkSrcSubscript - Examines the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Src, returning true iff it's linear. <a href="#a30e43032feb7097dc426ebe3d8e39669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d35a6089dff8d26c31f1523024f3221">checkDstSubscript</a> (const SCEV *Dst, const Loop *LoopNest, SmallBitVector &amp;Loops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkDstSubscript - Examines the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Dst, returning true iff it's linear. <a href="#a7d35a6089dff8d26c31f1523024f3221">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b73c42110b894708aff60503174259">isKnownPredicate</a> (ICmpInst::Predicate Pred, const SCEV *X, const SCEV *Y) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isKnownPredicate - Compare X and Y using the predicate Pred. <a href="#a06b73c42110b894708aff60503174259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64520a1ad355c2e0ec8cc08737b2a73">isKnownLessThan</a> (const SCEV *S, const SCEV *Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isKnownLessThan - Compare to see if S is less than Size Another wrapper for isKnownNegative(S - max(Size, 1)) with some extra checking if S is an AddRec and we can prove lessthan using the loop bounds. <a href="#ad64520a1ad355c2e0ec8cc08737b2a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23f3d6f20f827ea9544bdd26d09a98b">isKnownNonNegative</a> (const SCEV *S, const Value *Ptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isKnownNonNegative - Compare to see if S is known not to be negative Uses the fact that S comes from Ptr, which may be an inbound GEP, Proving there is no wrapping going on. <a href="#aa23f3d6f20f827ea9544bdd26d09a98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef18b791087ef93c8dcf9d2aa007b1a">collectUpperBound</a> (const Loop *l, Type *T) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>collectUpperBound - All subscripts are the same type (on my machine, an i64). <a href="#aeef18b791087ef93c8dcf9d2aa007b1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73bf06a69c95ad622d6eac4f44ccd95f">collectConstantUpperBound</a> (const Loop *l, Type *T) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>collectConstantUpperBound - Calls collectUpperBound(), then attempts to cast it to <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a>. <a href="#a73bf06a69c95ad622d6eac4f44ccd95f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Subscript::ClassificationKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4509237bdb40c9fe8d156c65e1d471dc">classifyPair</a> (const SCEV *Src, const Loop *SrcLoopNest, const SCEV *Dst, const Loop *DstLoopNest, SmallBitVector &amp;Loops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>classifyPair - Examines the subscript pair (the Src and Dst SCEVs) and classifies it as either ZIV, SIV, RDIV, MIV, or Nonlinear. <a href="#a4509237bdb40c9fe8d156c65e1d471dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6e82a2ab5b53c7089fbc6d9ab35d03">testZIV</a> (const SCEV *Src, const SCEV *Dst, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testZIV - Tests the ZIV subscript pair (Src and Dst) for dependence. <a href="#a5a6e82a2ab5b53c7089fbc6d9ab35d03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616771eae3c155887b7de9c92489d5fc">testSIV</a> (const SCEV *Src, const SCEV *Dst, unsigned &amp;Level, FullDependence &amp;Result, Constraint &amp;NewConstraint, const SCEV *&amp;SplitIter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testSIV - Tests the SIV subscript pair (Src and Dst) for dependence. <a href="#a616771eae3c155887b7de9c92489d5fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c8eb0ea67713d583559a2465e7261c">testRDIV</a> (const SCEV *Src, const SCEV *Dst, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testRDIV - Tests the RDIV subscript pair (Src and Dst) for dependence. <a href="#a32c8eb0ea67713d583559a2465e7261c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77f040ce8be511b4e2c912fd80f75fc">testMIV</a> (const SCEV *Src, const SCEV *Dst, const SmallBitVector &amp;Loops, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testMIV - Tests the MIV subscript pair (Src and Dst) for dependence. <a href="#ae77f040ce8be511b4e2c912fd80f75fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb60270e81f38acb0d61aaf77a069b2">strongSIVtest</a> (const SCEV *Coeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *CurrentLoop, unsigned Level, FullDependence &amp;Result, Constraint &amp;NewConstraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>strongSIVtest - Tests the strong SIV subscript pair (Src and Dst) for dependence. <a href="#abbb60270e81f38acb0d61aaf77a069b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c294fbfb88edad20f4684a88f4ec47">weakCrossingSIVtest</a> (const SCEV *SrcCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *CurrentLoop, unsigned Level, FullDependence &amp;Result, Constraint &amp;NewConstraint, const SCEV *&amp;SplitIter) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>weakCrossingSIVtest - Tests the weak-crossing SIV subscript pair (Src and Dst) for dependence. <a href="#a18c294fbfb88edad20f4684a88f4ec47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4fa270e1b91bf303ecbe5a49f8a340">exactSIVtest</a> (const SCEV *SrcCoeff, const SCEV *DstCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *CurrentLoop, unsigned Level, FullDependence &amp;Result, Constraint &amp;NewConstraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExactSIVtest - Tests the SIV subscript pair (Src and Dst) for dependence. <a href="#a5e4fa270e1b91bf303ecbe5a49f8a340">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815aee79fe4d2c421763a344b27fa28c">weakZeroSrcSIVtest</a> (const SCEV *DstCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *CurrentLoop, unsigned Level, FullDependence &amp;Result, Constraint &amp;NewConstraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>weakZeroSrcSIVtest - Tests the weak-zero SIV subscript pair (Src and Dst) for dependence. <a href="#a815aee79fe4d2c421763a344b27fa28c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ae6f4fb25d12fb4b0dd0ed20dec859">weakZeroDstSIVtest</a> (const SCEV *SrcCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *CurrentLoop, unsigned Level, FullDependence &amp;Result, Constraint &amp;NewConstraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>weakZeroDstSIVtest - Tests the weak-zero SIV subscript pair (Src and Dst) for dependence. <a href="#a89ae6f4fb25d12fb4b0dd0ed20dec859">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa103a9e231d33df35f987019510f69c7">exactRDIVtest</a> (const SCEV *SrcCoeff, const SCEV *DstCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *SrcLoop, const Loop *DstLoop, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>exactRDIVtest - Tests the RDIV subscript pair for dependence. <a href="#aa103a9e231d33df35f987019510f69c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64dc6b22bd261cf9fd66bb5616f8004">symbolicRDIVtest</a> (const SCEV *SrcCoeff, const SCEV *DstCoeff, const SCEV *SrcConst, const SCEV *DstConst, const Loop *SrcLoop, const Loop *DstLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>symbolicRDIVtest - Tests the RDIV subscript pair for dependence. <a href="#ad64dc6b22bd261cf9fd66bb5616f8004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76bb645eac6d80adcb9956e95620109">gcdMIVtest</a> (const SCEV *Src, const SCEV *Dst, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gcdMIVtest - Tests an MIV subscript pair for dependence. <a href="#af76bb645eac6d80adcb9956e95620109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4dcf2ea37f7a8a89b32325dc2dab1f">banerjeeMIVtest</a> (const SCEV *Src, const SCEV *Dst, const SmallBitVector &amp;Loops, FullDependence &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>banerjeeMIVtest - Tests an MIV subscript pair for dependence. <a href="#afb4dcf2ea37f7a8a89b32325dc2dab1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CoefficientInfo *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3075d705449f859f465d5d33eccaa7">collectCoeffInfo</a> (const SCEV *Subscript, bool SrcFlag, const SCEV *&amp;Constant) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>collectCoefficientInfo - Walks through the subscript, collecting each coefficient, the associated loop bounds, and recording its positive and negative parts for later use. <a href="#a0c3075d705449f859f465d5d33eccaa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50901406ecfa4b67fc7ace03d2cc9b3">getPositivePart</a> (const SCEV *X) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPositivePart - X^+ = max(X, 0). <a href="#af50901406ecfa4b67fc7ace03d2cc9b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656cb147ddf88f7bf7fdea1b4ac3b823">getNegativePart</a> (const SCEV *X) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNegativePart - X^- = min(X, 0). <a href="#a656cb147ddf88f7bf7fdea1b4ac3b823">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6146bace80a93d05eef3cac421d68e">getLowerBound</a> (BoundInfo *Bound) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLowerBound - Looks through all the bounds info and computes the lower bound given the current direction settings at each level. <a href="#a7b6146bace80a93d05eef3cac421d68e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cfb60c85070c71f43c1d8418ad2a7b0">getUpperBound</a> (BoundInfo *Bound) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUpperBound - Looks through all the bounds info and computes the upper bound given the current direction settings at each level. <a href="#a3cfb60c85070c71f43c1d8418ad2a7b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0bf0846cc39b7ba915978e4d4800db">exploreDirections</a> (unsigned Level, CoefficientInfo *A, CoefficientInfo *B, BoundInfo *Bound, const SmallBitVector &amp;Loops, unsigned &amp;DepthExpanded, const SCEV *Delta) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>exploreDirections - Hierarchically expands the direction vector search space, combining the directions of discovered dependences in the DirSet field of Bound. <a href="#abc0bf0846cc39b7ba915978e4d4800db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8fd3114af4fe6d660f543a0b822909">testBounds</a> (unsigned char DirKind, unsigned Level, BoundInfo *Bound, const SCEV *Delta) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testBounds - Returns true iff the current bounds are plausible. <a href="#a4b8fd3114af4fe6d660f543a0b822909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af734e40dabc6fa7a4f467af2cdcc0b42">findBoundsALL</a> (CoefficientInfo *A, CoefficientInfo *B, BoundInfo *Bound, unsigned K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findBoundsALL - Computes the upper and lower bounds for level K using the * direction. <a href="#af734e40dabc6fa7a4f467af2cdcc0b42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196742631a45d66f397577d5e7c58b6b">findBoundsLT</a> (CoefficientInfo *A, CoefficientInfo *B, BoundInfo *Bound, unsigned K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findBoundsLT - Computes the upper and lower bounds for level K using the &lt; direction. <a href="#a196742631a45d66f397577d5e7c58b6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a929bff0ea9c2832b24c4b4cd8ba21">findBoundsGT</a> (CoefficientInfo *A, CoefficientInfo *B, BoundInfo *Bound, unsigned K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findBoundsGT - Computes the upper and lower bounds for level K using the &gt; direction. <a href="#ab9a929bff0ea9c2832b24c4b4cd8ba21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72323033d037a202111a77b18872d354">findBoundsEQ</a> (CoefficientInfo *A, CoefficientInfo *B, BoundInfo *Bound, unsigned K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findBoundsEQ - Computes the upper and lower bounds for level K using the = direction. <a href="#a72323033d037a202111a77b18872d354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e04cec0f5416451c62dbc5fffa2fb40">intersectConstraints</a> (Constraint *X, const Constraint *Y)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>intersectConstraints - Updates X with the intersection of the Constraints X and Y. <a href="#a4e04cec0f5416451c62dbc5fffa2fb40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60da43024ab5c1c95e5f4a0732f5b508">propagate</a> (const SCEV *&amp;Src, const SCEV *&amp;Dst, SmallBitVector &amp;Loops, SmallVectorImpl&lt; Constraint &gt; &amp;Constraints, bool &amp;Consistent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>propagate - Review the constraints, looking for opportunities to simplify a subscript pair (Src and Dst). <a href="#a60da43024ab5c1c95e5f4a0732f5b508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebeeb65c77f90b01425dcf1443e9846">propagateDistance</a> (const SCEV *&amp;Src, const SCEV *&amp;Dst, Constraint &amp;CurConstraint, bool &amp;Consistent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>propagateDistance - Attempt to propagate a distance constraint into a subscript pair (Src and Dst). <a href="#a0ebeeb65c77f90b01425dcf1443e9846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4152d62a68ddc48e83be346b459af51a">propagatePoint</a> (const SCEV *&amp;Src, const SCEV *&amp;Dst, Constraint &amp;CurConstraint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>propagatePoint - Attempt to propagate a point constraint into a subscript pair (Src and Dst). <a href="#a4152d62a68ddc48e83be346b459af51a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbe2fc4dacf0b201746ea538d797935">propagateLine</a> (const SCEV *&amp;Src, const SCEV *&amp;Dst, Constraint &amp;CurConstraint, bool &amp;Consistent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>propagateLine - Attempt to propagate a line constraint into a subscript pair (Src and Dst). <a href="#a1fbe2fc4dacf0b201746ea538d797935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20d1ee304ba68984ec90e0b0ebfa12c">findCoefficient</a> (const SCEV *Expr, const Loop *TargetLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, return the coefficient corresponding to specified loop. <a href="#af20d1ee304ba68984ec90e0b0ebfa12c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61607510c3e1de9058693c7e53a8f6a1">zeroCoefficient</a> (const SCEV *Expr, const Loop *TargetLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>zeroCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> given by zeroing out the coefficient corresponding to the specified loop. <a href="#a61607510c3e1de9058693c7e53a8f6a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10fd2950c90a982a9cab959c9f79eca8">addToCoefficient</a> (const SCEV *Expr, const Loop *TargetLoop, const SCEV *Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addToCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Expr, return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> given by adding some <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the coefficient corresponding to the specified TargetLoop. <a href="#a10fd2950c90a982a9cab959c9f79eca8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d39ab3e9b535eb39c9ea650c42e314e">updateDirection</a> (Dependence::DVEntry &amp;Level, const Constraint &amp;CurConstraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateDirection - Update direction vector entry based on the current constraint. <a href="#a9d39ab3e9b535eb39c9ea650c42e314e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38f730e04cd80e9044f98be0a0ba965">tryDelinearize</a> (Instruction *Src, Instruction *Dst, SmallVectorImpl&lt; Subscript &gt; &amp;Pair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a linear access function, tries to recover subscripts for each dimension of the array element access. <a href="#ab38f730e04cd80e9044f98be0a0ba965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7905a64872c4dfdf2890decb10645d8b">tryDelinearizeFixedSize</a> (Instruction *Src, Instruction *Dst, const SCEV *SrcAccessFn, const SCEV *DstAccessFn, SmallVectorImpl&lt; const SCEV * &gt; &amp;SrcSubscripts, SmallVectorImpl&lt; const SCEV * &gt; &amp;DstSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to delinearize <span class="doxyComputerOutput">Src</span> and <span class="doxyComputerOutput">Dst</span> access functions for a fixed size multi-dimensional array. <a href="#a7905a64872c4dfdf2890decb10645d8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ce11cba642ec2f690f9b11bb9e929b">tryDelinearizeParametricSize</a> (Instruction *Src, Instruction *Dst, const SCEV *SrcAccessFn, const SCEV *DstAccessFn, SmallVectorImpl&lt; const SCEV * &gt; &amp;SrcSubscripts, SmallVectorImpl&lt; const SCEV * &gt; &amp;DstSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to delinearize access function for a multi-dimensional array with symbolic runtime sizes. <a href="#af2ce11cba642ec2f690f9b11bb9e929b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027899e63b70019b6b33f6fb215ec0d6">checkSubscript</a> (const SCEV *Expr, const Loop *LoopNest, SmallBitVector &amp;Loops, bool IsSrc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkSubscript - Helper function for checkSrcSubscript and checkDstSubscript to avoid duplicate code <a href="#a027899e63b70019b6b33f6fb215ec0d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905d007d35b7f781ab8de05340f92e10">AA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d54f5951133ad794e2617824f48496d">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f20bd6748fc2a70e6196cd5e59e352">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87443ab2c52d00527e2e8f4c0c260bb9">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b6ca8de1f9a391b86922b14e703127">CommonLevels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069c302e230f2ea0e4d055344ba80d7b">SrcLevels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e0d1ac3bed60bf7a46cf84859f538a">MaxLevels</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> - This class is the main dependence-analysis driver.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DependenceInfo() {#a6e0908efeae361bba872b8d4abd6eccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DependenceInfo::DependenceInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### depends() {#a49197b24cced248bed2d2c89c641a6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Dependence &gt; DependenceInfo::depends (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dst, bool PossiblyLoopIndependent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>depends - Tests for a dependence between the Src and Dst instructions.</p>


<p>Returns NULL if no dependence; otherwise, returns a <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> (or a <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a>) with as much information as can be gleaned. The flag PossiblyLoopIndependent should be set by the caller if it appears that control flow can reach from Src to Dst without traversing a loop back edge.</p>


<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3589 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ab06e25d03b0091f03f2a25118933236b">llvm::SmallBitVector::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ae0307ad5c950df7f6fb56dc8326184ce">llvm::SmallBitVector::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#aca71d335b07010ddc09f275d56096353">Delinearize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3f932542066a4a9ff8d9368b1871e9d6">dumpSmallBitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917ad4051c16e1d2336250f8e267c1e03281">llvm::Dependence::DVEntry::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a13ace390c34c56c32bff6c20c4e7c6b5">isLoadOrStore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a0916b614598c673c1e6a59c7312a1409">llvm::AliasResult::MayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917add6bfdcbd5e035c0c932ab75dd7ab654">llvm::Dependence::DVEntry::NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a9e724bc94de38c6ca77508f19c246c0c">llvm::AliasResult::PartialAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#af1232d0679de538d35381496f43e303a">llvm::SmallBitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a72bc4f47a61dc9d9888561c4dc22e8f6">llvm::SmallBitVector::set_bits</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a5737072fd3031fc204134cf904dc36bb">underlyingObjectsAlias</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#afa7cdefae294ca029d754def452709e9">checkDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a6b2b20549af64712df253586da3701a8">llvm::IndexedReference::hasTemporalReuse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adffe8dd96d1c957f04909ca9c2cd79ba">llvm::isSafeToMoveBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#adcd261211472362965c5b1bc5a3efebe">populateDependencyMatrix</a>.</p>

</div>
</div>

### getFunction() {#a4009b44221972360b0b0fb7dbf1cc7f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::DependenceInfo::getFunction ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### getSplitIteration() {#a110f1f473cbb5a42bf9c82973ac9101c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::getSplitIteration (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> &amp; Dep, unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSplitIteration - Give a dependence that's splittable at some particular level, return the iteration that should be used to split the loop.</p>


<p>Generally, the dependence analyzer will be used to build a dependence graph for a function (basically a map from instructions to dependences). Looking for cycles in the graph shows us loops that cannot be trivially vectorized/parallelized.</p>


<p>We can try to improve the situation by examining all the dependences that make up the cycle, looking for ones we can break. Sometimes, peeling the first or last iteration of a loop will break dependences, and there are flags for those possibilities. Sometimes, splitting a loop at some other iteration will do the trick, and we've got a flag for that case. Rather than waste the space to record the exact iteration (since we rarely know), we provide a method that calculates the iteration. It's a drag that it must work from scratch, but wonderful in that it's possible.</p>


<p>Here's an example:</p>


<p>for (i = 0; i &lt; 10; i++) A[i] = ... ... = A[11 - i]</p>


<p>There's a loop-carried flow dependence from the store to the load, found by the weak-crossing SIV test. The dependence will have a flag, indicating that the dependence can be broken by splitting the loop. Calling getSplitIteration will return 5. Splitting the loop breaks the dependence, like so:</p>


<p>for (i = 0; i &lt;= 5; i++) A[i] = ... ... = A[11 - i] for (i = 6; i &lt; 10; i++) A[i] = ... ... = A[11 - i]</p>


<p>breaks the dependence and allows us to vectorize/parallelize both loops.</p>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 4023 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ab06e25d03b0091f03f2a25118933236b">llvm::SmallBitVector::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ae0307ad5c950df7f6fb56dc8326184ce">llvm::SmallBitVector::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#aca71d335b07010ddc09f275d56096353">Delinearize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dependence/#a1e9c3ea9ecca5734fd90a2eea39cb4f5">llvm::Dependence::getDst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/dependence/#add64f4bc4fb47b10873cbc281c55c62e">llvm::Dependence::getSrc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a13ace390c34c56c32bff6c20c4e7c6b5">isLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/dependence/#a6e3dba62b3e54312c7cb84af34d00015">llvm::Dependence::isSplitable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#af1232d0679de538d35381496f43e303a">llvm::SmallBitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a72bc4f47a61dc9d9888561c4dc22e8f6">llvm::SmallBitVector::set_bits</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a5737072fd3031fc204134cf904dc36bb">underlyingObjectsAlias</a>.</p>

</div>
</div>

### invalidate() {#a10d6c1036e234fab6e63803cf9fb62de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle transitive invalidation when the cached analysis results go away.</p>

<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3564 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addToCoefficient() {#a10fd2950c90a982a9cab959c9f79eca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::addToCoefficient (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TargetLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addToCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Expr, return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> given by adding some <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the coefficient corresponding to the specified TargetLoop.</p>


<p>For example, given a*i + b*j + c*k, adding 1 to the coefficient corresponding to the j loop would yield a*i + (b+1)*j + c*k.</p>


<p>Declaration at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3115 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### banerjeeMIVtest() {#afb4dcf2ea37f7a8a89b32325dc2dab1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::banerjeeMIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>banerjeeMIVtest - Tests an MIV subscript pair for dependence.</p>


<p>Returns true if any possible dependence is disproved. Marks the result as inconsistent. Computes directions.</p>


<p>Declaration at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2604 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### checkDstSubscript() {#a7d35a6089dff8d26c31f1523024f3221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::checkDstSubscript (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * LoopNest, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkDstSubscript - Examines the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Dst, returning true iff it's linear.</p>


<p>Collect the set of loops mentioned by Dst.</p>


<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### checkSrcSubscript() {#a30e43032feb7097dc426ebe3d8e39669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::checkSrcSubscript (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * LoopNest, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkSrcSubscript - Examines the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Src, returning true iff it's linear.</p>


<p>Collect the set of loops mentioned by Src.</p>


<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### checkSubscript() {#a027899e63b70019b6b33f6fb215ec0d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::checkSubscript (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * LoopNest, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops, bool IsSrc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkSubscript - Helper function for checkSrcSubscript and checkDstSubscript to avoid duplicate code</p>

<p>Declaration at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### classifyPair() {#a4509237bdb40c9fe8d156c65e1d471dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo::Subscript::ClassificationKind DependenceInfo::classifyPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * SrcLoopNest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * DstLoopNest, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>classifyPair - Examines the subscript pair (the Src and Dst SCEVs) and classifies it as either ZIV, SIV, RDIV, MIV, or Nonlinear.</p>


<p>Collects the associated loops in a set.</p>


<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### collectCoeffInfo() {#a0c3075d705449f859f465d5d33eccaa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo::CoefficientInfo * DependenceInfo::collectCoeffInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Subscript, bool SrcFlag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Constant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>collectCoefficientInfo - Walks through the subscript, collecting each coefficient, the associated loop bounds, and recording its positive and negative parts for later use.</p>

<p>Declaration at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2998 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### collectCommonLoops() {#a67c7c35b5f98be112979b5281badef35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::collectCommonLoops (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * LoopNest, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>collectCommonLoops - Finds the set of loops from the <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> that have a level &lt;= CommonLevels and are referred to by the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a>.</p>

<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### collectConstantUpperBound() {#a73bf06a69c95ad622d6eac4f44ccd95f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVConstant * DependenceInfo::collectConstantUpperBound (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * l, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>collectConstantUpperBound - Calls collectUpperBound(), then attempts to cast it to <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a>.</p>


<p>If the cast fails, returns NULL.</p>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### collectUpperBound() {#aeef18b791087ef93c8dcf9d2aa007b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::collectUpperBound (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * l, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>collectUpperBound - All subscripts are the same type (on my machine, an i64).</p>


<p>The loop bound may be a smaller type. collectUpperBound find the bound, if available, and zero extends it to the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> T. (I zero extend since the bound should always be &gt;= 0.) If no upper bound is available, return NULL.</p>


<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### establishNestingLevels() {#a8187e3f7370e0b7bf547022cca10ab0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::establishNestingLevels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>establishNestingLevels - Examines the loop nesting of the Src and Dst instructions and establishes their shared loops.</p>


<p>Sets the variables CommonLevels, SrcLevels, and MaxLevels. The source and destination instructions needn't be contained in the same loop. The routine establishNestingLevels finds the level of most deeply nested loop that contains them both, CommonLevels. An instruction that's not contained in a loop is at level = 0. MaxLevels is equal to the level of the source plus the level of the destination, minus CommonLevels. This lets us allocate vectors MaxLevels in length, with room for every distinct loop referenced in both the source and destination subscripts. The variable SrcLevels is the nesting depth of the source instruction. It's used to help calculate distinct loops referenced by the destination. Here's the map from loops to levels: 0 - unused 1 - outermost common loop ... - other common loops CommonLevels - innermost common loop ... - loops containing Src but not Dst SrcLevels - innermost loop containing Src but not Dst ... - loops containing Dst but not Src MaxLevels - innermost loop containing Dst but not Src Consider the follow code fragment: for (a = ...) { for (b = ...) { for (c = ...) { for (d = ...) { A[] = ...; } } for (e = ...) { for (f = ...) { for (g = ...) { ... = A[]; } } } } } If we're looking at the possibility of a dependence between the store to A (the Src) and the load from A (the Dst), we'll note that they have 2 loops in common, so CommonLevels will equal 2 and the direction vector for Result will have 2 entries. SrcLevels = 4 and MaxLevels = 7. A map from loop names to level indices would look like a - 1 b - 2 = CommonLevels c - 3 d - 4 = SrcLevels e - 5 f - 6 g - 7 = MaxLevels</p>


<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### exactRDIVtest() {#aa103a9e231d33df35f987019510f69c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::exactRDIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * SrcLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * DstLoop, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>exactRDIVtest - Tests the RDIV subscript pair for dependence.</p>


<p>Things of the form [c1 + a*i] and [c2 + b*j], where i and j are induction variable, c1 and c2 are loop invariant, and a and b are constants. Returns true if any possible dependence is disproved. Marks the result as inconsistent. Works in some cases that symbolicRDIVtest doesn't, and vice versa.</p>


<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1954 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### exactSIVtest() {#a5e4fa270e1b91bf303ecbe5a49f8a340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::exactSIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentLoop, unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExactSIVtest - Tests the SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a1*i] and [c2 + a2*i], where i is an induction variable, c1 and c2 are loop invariant, and a1 and a2 are constant. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction entry. Set consistent to false.</p>


<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1566 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### exploreDirections() {#abc0bf0846cc39b7ba915978e4d4800db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DependenceInfo::exploreDirections (unsigned Level, CoefficientInfo * A, CoefficientInfo * B, BoundInfo * Bound, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops, unsigned &amp; DepthExpanded, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Delta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>exploreDirections - Hierarchically expands the direction vector search space, combining the directions of discovered dependences in the DirSet field of Bound.</p>


<p>Returns the number of distinct dependences discovered. If the dependence is disproved, it will return 0.</p>


<p>Declaration at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2684 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### findBoundsALL() {#af734e40dabc6fa7a4f467af2cdcc0b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::findBoundsALL (CoefficientInfo * A, CoefficientInfo * B, BoundInfo * Bound, unsigned K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findBoundsALL - Computes the upper and lower bounds for level K using the * direction.</p>


<p>Records them in Bound.</p>


<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2830 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### findBoundsEQ() {#a72323033d037a202111a77b18872d354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::findBoundsEQ (CoefficientInfo * A, CoefficientInfo * B, BoundInfo * Bound, unsigned K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findBoundsEQ - Computes the upper and lower bounds for level K using the = direction.</p>


<p>Records them in Bound.</p>


<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2869 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### findBoundsGT() {#ab9a929bff0ea9c2832b24c4b4cd8ba21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::findBoundsGT (CoefficientInfo * A, CoefficientInfo * B, BoundInfo * Bound, unsigned K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findBoundsGT - Computes the upper and lower bounds for level K using the &gt; direction.</p>


<p>Records them in Bound.</p>


<p>Declaration at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2953 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### findBoundsLT() {#a196742631a45d66f397577d5e7c58b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::findBoundsLT (CoefficientInfo * A, CoefficientInfo * B, BoundInfo * Bound, unsigned K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findBoundsLT - Computes the upper and lower bounds for level K using the &lt; direction.</p>


<p>Records them in Bound.</p>


<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2909 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### findCoefficient() {#af20d1ee304ba68984ec90e0b0ebfa12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::findCoefficient (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TargetLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, return the coefficient corresponding to specified loop.</p>


<p>If there isn't one, return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> constant 0. For example, given a*i + b*j + c*k, returning the coefficient corresponding to the j loop would yield b.</p>


<p>Declaration at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3080 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### gcdMIVtest() {#af76bb645eac6d80adcb9956e95620109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::gcdMIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>gcdMIVtest - Tests an MIV subscript pair for dependence.</p>


<p>Returns true if any possible dependence is disproved. Marks the result as inconsistent. Can sometimes disprove the equal direction for 1 or more loops. so we use it as a backup for everything.</p>


<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2402 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getLowerBound() {#a7b6146bace80a93d05eef3cac421d68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::getLowerBound (BoundInfo * Bound)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLowerBound - Looks through all the bounds info and computes the lower bound given the current direction settings at each level.</p>

<p>Declaration at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3043 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getNegativePart() {#a656cb147ddf88f7bf7fdea1b4ac3b823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::getNegativePart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getNegativePart - X^- = min(X, 0).</p>

<p>Declaration at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2989 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getPositivePart() {#af50901406ecfa4b67fc7ace03d2cc9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::getPositivePart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPositivePart - X^+ = max(X, 0).</p>

<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2983 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### getUpperBound() {#a3cfb60c85070c71f43c1d8418ad2a7b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::getUpperBound (BoundInfo * Bound)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getUpperBound - Looks through all the bounds info and computes the upper bound given the current direction settings at each level.</p>

<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3059 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### intersectConstraints() {#a4e04cec0f5416451c62dbc5fffa2fb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::intersectConstraints (Constraint * X, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Constraint * Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>intersectConstraints - Updates X with the intersection of the Constraints X and Y.</p>


<p>Returns true if X has changed.</p>


<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### isKnownLessThan() {#ad64520a1ad355c2e0ec8cc08737b2a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::isKnownLessThan (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isKnownLessThan - Compare to see if S is less than Size Another wrapper for isKnownNegative(S - max(Size, 1)) with some extra checking if S is an AddRec and we can prove lessthan using the loop bounds.</p>


<p>Compare to see if S is less than Size, using isKnownNegative(S - max(Size, 1)) with some extra checking if S is an AddRec and we can prove less-than using the loop bounds.</p>


<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### isKnownNonNegative() {#aa23f3d6f20f827ea9544bdd26d09a98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::isKnownNonNegative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isKnownNonNegative - Compare to see if S is known not to be negative Uses the fact that S comes from Ptr, which may be an inbound GEP, Proving there is no wrapping going on.</p>

<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### isKnownPredicate() {#a06b73c42110b894708aff60503174259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::isKnownPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * X, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isKnownPredicate - Compare X and Y using the predicate Pred.</p>


<p>Basically a wrapper for SCEV::isKnownPredicate, but tries harder, especially in the presence of sign and zero extensions and symbolics.</p>


<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### isLoopInvariant() {#a9752863bb26b814a11e51a43b61c0bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::isLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * LoopNest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLoopInvariant - Returns true if <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> is loop invariant in <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a>.</p>

<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### mapDstLoop() {#a78f58754d78853e54bb6f61eab7542bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DependenceInfo::mapDstLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * DstLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mapDstLoop - Given one of the loops containing the destination, return its level index in our numbering scheme.</p>

<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### mapSrcLoop() {#a11b8e5845abe1a12797ebe585950179d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DependenceInfo::mapSrcLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * SrcLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mapSrcLoop - Given one of the loops containing the source, return its level index in our numbering scheme.</p>

<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### propagate() {#a60da43024ab5c1c95e5f4a0732f5b508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::propagate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Dst, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; Constraint &gt; &amp; Constraints, bool &amp; Consistent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>propagate - Review the constraints, looking for opportunities to simplify a subscript pair (Src and Dst).</p>


<p>Return true if some simplification occurs. If the simplification isn't exact (that is, if it is conservative in terms of dependence), set consistent to false.</p>


<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3152 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### propagateDistance() {#a0ebeeb65c77f90b01425dcf1443e9846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::propagateDistance (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Dst, Constraint &amp; CurConstraint, bool &amp; Consistent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>propagateDistance - Attempt to propagate a distance constraint into a subscript pair (Src and Dst).</p>


<p>Return true if some simplification occurs. If the simplification isn't exact (that is, if it is conservative in terms of dependence), set consistent to false.</p>


<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3176 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### propagateLine() {#a1fbe2fc4dacf0b201746ea538d797935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::propagateLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Dst, Constraint &amp; CurConstraint, bool &amp; Consistent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>propagateLine - Attempt to propagate a line constraint into a subscript pair (Src and Dst).</p>


<p>Return true if some simplification occurs. If the simplification isn't exact (that is, if it is conservative in terms of dependence), set consistent to false.</p>


<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### propagatePoint() {#a4152d62a68ddc48e83be346b459af51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::propagatePoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Dst, Constraint &amp; CurConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>propagatePoint - Attempt to propagate a point constraint into a subscript pair (Src and Dst).</p>


<p>Return true if some simplification occurs.</p>


<p>Declaration at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3277 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### removeMatchingExtensions() {#a43098cff2af7676a39ac58e5eadaf172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::removeMatchingExtensions (Subscript * Pair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeMatchingExtensions - Examines a subscript pair.</p>


<p>If the source and destination are identically sign (or zero) extended, it strips off the extension in an effort to simplify the actual analysis.</p>


<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 944 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### strongSIVtest() {#abbb60270e81f38acb0d61aaf77a069b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::strongSIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Coeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentLoop, unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>strongSIVtest - Tests the strong SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a*i] and [c2 + a*i], where i is an induction variable, c1 and c2 are loop invariant, and a is a constant Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction and distance.</p>


<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### symbolicRDIVtest() {#ad64dc6b22bd261cf9fd66bb5616f8004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::symbolicRDIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * SrcLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * DstLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>symbolicRDIVtest - Tests the RDIV subscript pair for dependence.</p>


<p>Things of the form [c1 + a*i] and [c2 + b*j], where i and j are induction variable, c1 and c2 are loop invariant, and a and b are constants. Returns true if any possible dependence is disproved. Marks the result as inconsistent. Works in some cases that exactRDIVtest doesn't, and vice versa. Can also be used as a backup for ordinary SIV tests.</p>


<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### testBounds() {#a4b8fd3114af4fe6d660f543a0b822909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::testBounds (unsigned char DirKind, unsigned Level, BoundInfo * Bound, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Delta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>testBounds - Returns true iff the current bounds are plausible.</p>

<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2802 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### testMIV() {#ae77f040ce8be511b4e2c912fd80f75fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::testMIV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; Loops, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>testMIV - Tests the MIV subscript pair (Src and Dst) for dependence.</p>


<p>Returns true if dependence disproved. Can sometimes refine direction vectors.</p>


<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2360 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### testRDIV() {#a32c8eb0ea67713d583559a2465e7261c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::testRDIV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>testRDIV - Tests the RDIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a1*i] and [c2 + a2*j] where i and j are induction variables, c1 and c2 are loop invariant, and a1 and a2 are constant. With minor algebra, this test can also be used for things like [c1 + a1*i + a2*j][c2]. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Marks the Result as inconsistent.</p>


<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### testSIV() {#a616771eae3c155887b7de9c92489d5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::testSIV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, unsigned &amp; Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; SplitIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>testSIV - Tests the SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a1*i] and [c2 + a2*j], where i and j are induction variables, c1 and c2 are loop invariant, and a1 and a2 are constant. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction vector entry and, when possible, the distance vector entry. If the dependence isn't proven to exist, marks the Result as inconsistent.</p>


<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 2226 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### testZIV() {#a5a6e82a2ab5b53c7089fbc6d9ab35d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::testZIV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>testZIV - Tests the ZIV subscript pair (Src and Dst) for dependence.</p>


<p>Returns true if any possible dependence is disproved. If there might be a dependence, returns false. If the dependence isn't proven to exist, marks the Result as inconsistent.</p>


<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### tryDelinearize() {#ab38f730e04cd80e9044f98be0a0ba965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::tryDelinearize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; Subscript &gt; &amp; Pair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a linear access function, tries to recover subscripts for each dimension of the array element access.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we can delinearize the subscripts.</p>


<p>If the SCEVs representing the source and destination array references are recurrences on a nested loop, this function flattens the nested recurrences into separate recurrences for each loop level.</p>


<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3349 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### tryDelinearizeFixedSize() {#a7905a64872c4dfdf2890decb10645d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::tryDelinearizeFixedSize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcAccessFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstAccessFn, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; SrcSubscripts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; DstSubscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to delinearize <span class="doxyComputerOutput">Src</span> and <span class="doxyComputerOutput">Dst</span> access functions for a fixed size multi-dimensional array.</p>


<p>Try to delinearize <span class="doxyComputerOutput">SrcAccessFn</span> and <span class="doxyComputerOutput">DstAccessFn</span> if the underlying arrays accessed are fixed-size arrays.</p>


<p>Calls <a href="/web-llvm/docs/api/namespaces/llvm/#ab73239c9eac42ae767c00ecc64e98dff">tryDelinearizeFixedSizeImpl()</a> to delinearize <span class="doxyComputerOutput">Src</span> and <span class="doxyComputerOutput">Dst</span> separately,</p>


<p>Return true if delinearization was successful.</p>


<p>Declaration at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3402 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### tryDelinearizeParametricSize() {#af2ce11cba642ec2f690f9b11bb9e929b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::tryDelinearizeParametricSize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcAccessFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstAccessFn, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; SrcSubscripts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; DstSubscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to delinearize access function for a multi-dimensional array with symbolic runtime sizes.</p>


<p>Returns true upon success and false otherwise.</p>


<p>Declaration at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3479 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### unifySubscriptType() {#a5bcdf9b5f618c4f0a8e6a2761c7bff25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::unifySubscriptType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; Subscript * &gt; Pairs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes sure all subscript pairs share the same integer type by sign-extending as necessary.</p>


<p>Sign-extending a subscript is safe because getelementptr assumes the array subscripts are signed.</p>


<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### updateDirection() {#a9d39ab3e9b535eb39c9ea650c42e314e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependenceInfo::updateDirection (<a href="/web-llvm/docs/api/structs/llvm/dependence/dventry">Dependence::DVEntry</a> &amp; Level, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Constraint &amp; CurConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateDirection - Update direction vector entry based on the current constraint.</p>

<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3296 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### weakCrossingSIVtest() {#a18c294fbfb88edad20f4684a88f4ec47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::weakCrossingSIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentLoop, unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; SplitIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>weakCrossingSIVtest - Tests the weak-crossing SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a*i] and [c2 - a*i], where i is an induction variable, c1 and c2 are loop invariant, and a is a constant. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction entry. Set consistent to false. Marks the dependence as splitable.</p>


<p>Declaration at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### weakZeroDstSIVtest() {#a89ae6f4fb25d12fb4b0dd0ed20dec859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::weakZeroDstSIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentLoop, unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>weakZeroDstSIVtest - Tests the weak-zero SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1 + a*i] and [c2], where i is an induction variable, c1 and c2 are loop invariant, and a is a constant. See also weakZeroSrcSIVtest. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction entry. Set consistent to false. If loop peeling will break the dependence, mark appropriately.</p>


<p>Declaration at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1869 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### weakZeroSrcSIVtest() {#a815aee79fe4d2c421763a344b27fa28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependenceInfo::weakZeroSrcSIVtest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstCoeff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SrcConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * DstConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentLoop, unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> &amp; Result, Constraint &amp; NewConstraint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>weakZeroSrcSIVtest - Tests the weak-zero SIV subscript pair (Src and Dst) for dependence.</p>


<p>Things of the form [c1] and [c2 + a*i], where i is an induction variable, c1 and c2 are loop invariant, and a is a constant. See also weakZeroDstSIVtest. Returns true if any possible dependence is disproved. If there might be a dependence, returns false. Sets appropriate direction entry. Set consistent to false. If loop peeling will break the dependence, mark appropriately.</p>


<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 1759 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

### zeroCoefficient() {#a61607510c3e1de9058693c7e53a8f6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * DependenceInfo::zeroCoefficient (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TargetLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>zeroCoefficient - Given a linear <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> given by zeroing out the coefficient corresponding to the specified loop.</p>


<p>For example, given a*i + b*j + c*k, zeroing the coefficient corresponding to the j loop would yield a*i + c*k.</p>


<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 3096 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a905d007d35b7f781ab8de05340f92e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::DependenceInfo::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### CommonLevels {#a92b6ca8de1f9a391b86922b14e703127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DependenceInfo::CommonLevels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### F {#a87443ab2c52d00527e2e8f4c0c260bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::DependenceInfo::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### LI {#a45f20bd6748fc2a70e6196cd5e59e352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::DependenceInfo::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### MaxLevels {#a19e0d1ac3bed60bf7a46cf84859f538a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DependenceInfo::MaxLevels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### SE {#a3d54f5951133ad794e2617824f48496d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::DependenceInfo::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### SrcLevels {#a069c302e230f2ea0e4d055344ba80d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DependenceInfo::SrcLevels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
