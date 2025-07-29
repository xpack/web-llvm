---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SimplifyIndvar` Class

<p>This is a utility for simplifying induction variables based on <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SimplifyIndVar.cpp}::SimplifyIndvar { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9927ff53dcde314a02563533fd811b6">SimplifyIndvar</a> (Loop *Loop, ScalarEvolution *SE, DominatorTree *DT, LoopInfo *LI, const TargetTransformInfo *TTI, SCEVExpander &amp;Rewriter, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;Dead)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab034f8c7eb931424cbc2a9749f8356ab">hasChanged</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018e1ba64d8ecb5b3a8a9c95cfd331da">runUnswitching</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a> (PHINode *CurrIV, IVVisitor *V=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteratively perform simplification on a worklist of users of the specified induction variable. <a href="#a1ba99155749ea6a41858f9bc4449f543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbabc703d62c3cc425d6b03dd1d3ef5">pushIVUsers</a> (Instruction *Def, SmallPtrSet&lt; Instruction *, 16 &gt; &amp;Simplified, SmallVectorImpl&lt; std::pair&lt; Instruction *, Instruction * &gt; &gt; &amp;SimpleIVUsers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add all uses of Def to the current IV's worklist. <a href="#abcbabc703d62c3cc425d6b03dd1d3ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f6125cdd608cb0459585ddb68ead53">foldIVUser</a> (Instruction *UseInst, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold an IV operand into its use. <a href="#a12f6125cdd608cb0459585ddb68ead53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45f11045718186c0300d34919228c2a">eliminateIdentitySCEV</a> (Instruction *UseInst, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate any operation that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> can prove is an identity function. <a href="#ae45f11045718186c0300d34919228c2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287ee23f262c0a9deb16096da9d34e7a">replaceIVUserWithLoopInvariant</a> (Instruction *UseInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the UseInst with a loop invariant expression if it is safe. <a href="#a287ee23f262c0a9deb16096da9d34e7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16096e55b9292113f13073fa2343b9c7">replaceFloatIVWithIntegerIV</a> (Instruction *UseInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate redundant type cast between integer and float. <a href="#a16096e55b9292113f13073fa2343b9c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a706e35559bb3deb6e92a8ac4bfe1e8">eliminateOverflowIntrinsic</a> (WithOverflowInst *WO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8629a06eaa190b10f442dd35c1df09a">eliminateSaturatingIntrinsic</a> (SaturatingInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5eb28a130d94e94dff2f9e798617ab">eliminateTrunc</a> (TruncInst *TI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a> (Instruction *UseInst, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate an operation that consumes a simple IV and has no observable side-effect given the range of IV values. <a href="#a08427a7d29ad22c694e5447d0d0adf4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304f0837129322608c9e0384d193a0ba">makeIVComparisonInvariant</a> (ICmpInst *ICmp, Instruction *IVOperand)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acccaf0eaeef2b860b1182f8985f59e94">eliminateIVComparison</a> (ICmpInst *ICmp, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SimplifyIVUsers helper for eliminating useless comparisons against an induction variable. <a href="#acccaf0eaeef2b860b1182f8985f59e94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4e22418fd040f349bdecefdc303c2e">simplifyIVRemainder</a> (BinaryOperator *Rem, Instruction *IVOperand, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SimplifyIVUsers helper for eliminating useless remainder operations operating on an induction variable or replacing srem by urem. <a href="#a9a4e22418fd040f349bdecefdc303c2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ea440b89ee11cd2aaecfd52290e069">replaceRemWithNumerator</a> (BinaryOperator *Rem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645f6e970e94d7ca51922b3932338f51">replaceRemWithNumeratorOrZero</a> (BinaryOperator *Rem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a96c9b1143670a73852464de9950e8e">replaceSRemWithURem</a> (BinaryOperator *Rem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664aaf46532d6ebeed0dfeb704308d33">eliminateSDiv</a> (BinaryOperator *SDiv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef1c9cb26f85c3ef0e39c3b0d6df989">strengthenBinaryOp</a> (BinaryOperator *BO, Instruction *IVOperand)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6315ffed3396dd69c53e1e51cfcd9f6">strengthenOverflowingOperation</a> (BinaryOperator *OBO, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Annotate BO with nsw / nuw if it provably does not signed-overflow / unsigned-overflow. <a href="#ad6315ffed3396dd69c53e1e51cfcd9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff215a6e938a8df32c29c99bc126603">strengthenRightShift</a> (BinaryOperator *BO, Instruction *IVOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Annotate the Shr in (X &lt;&lt; IVOperand) &gt;&gt; C as exact using the information from the IV's range. <a href="#a8ff215a6e938a8df32c29c99bc126603">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a938296bce5ed4ce4cfc4603fc4d23e5b">L</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae862f582600b34487d706d33b8461041">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1b2309852a5d82808f9d27ddc4bf85">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2644f97d4fb76f14b8da4244c73de249">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb2fa2cca93d7ebc31dccd07957b3d3">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6324295d78c2ad6e97e34b2806cbe87">Rewriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32dbbed79b0b157474ee94720560ca5d">DeadInsts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc9bd06acb15df166ae28bb4905490d">Changed</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0565c03a96527aa9d0b2d2f75a05a968">RunUnswitching</a> = false</td>
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

<p>This is a utility for simplifying induction variables based on <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>.</p>


<p>It is the primary instrument of the IndvarSimplify pass, but it may also be directly invoked to cleanup after other loop passes that preserve <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SimplifyIndvar() {#ae9927ff53dcde314a02563533fd811b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::SimplifyIndvar (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Rewriter, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; Dead)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eliminateIdentitySCEV() {#ae45f11045718186c0300d34919228c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateIdentitySCEV (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate any operation that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> can prove is an identity function.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a4a4e0f6178682ef05a0d85891e5a9">llvm::impliesPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### eliminateIVComparison() {#acccaf0eaeef2b860b1182f8985f59e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::eliminateIVComparison (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICmp, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SimplifyIVUsers helper for eliminating useless comparisons against an induction variable.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a61b5cb822ee8e25eee3418a520337962">findCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#af07a09f1cda33d984cc725dc9e856d40">llvm::ICmpInst::getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a304f0837129322608c9e0384d193a0ba">makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a126a12b67fa620ad28ec0c919ca7a3e8">llvm::CmpInst::setPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### eliminateIVUser() {#a08427a7d29ad22c694e5447d0d0adf4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateIVUser (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate an operation that consumes a simple IV and has no observable side-effect given the range of IV values.</p>


<p>IVOperand is guaranteed SCEVable, but UseInst may not be.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ae45f11045718186c0300d34919228c2a">eliminateIdentitySCEV</a>, <a href="#acccaf0eaeef2b860b1182f8985f59e94">eliminateIVComparison</a>, <a href="#a5a706e35559bb3deb6e92a8ac4bfe1e8">eliminateOverflowIntrinsic</a>, <a href="#ad8629a06eaa190b10f442dd35c1df09a">eliminateSaturatingIntrinsic</a>, <a href="#a664aaf46532d6ebeed0dfeb704308d33">eliminateSDiv</a>, <a href="#a6f5eb28a130d94e94dff2f9e798617ab">eliminateTrunc</a> and <a href="#a9a4e22418fd040f349bdecefdc303c2e">simplifyIVRemainder</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### eliminateOverflowIntrinsic() {#a5a706e35559bb3deb6e92a8ac4bfe1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateOverflowIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/withoverflowinst">WithOverflowInst</a> * WO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#aa73e62aac1753cb7b3c3aaccef3df8b1">llvm::BinaryOpIntrinsic::getBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#abd530ffa05240e0728bf85169dc7abcc">llvm::BinaryOpIntrinsic::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#a0583d2d049d59cf53ccfd2b6f4e53c87">llvm::BinaryOpIntrinsic::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#a814f3097eebe0236748fcc2ab5ce59d5">llvm::BinaryOpIntrinsic::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### eliminateSaturatingIntrinsic() {#ad8629a06eaa190b10f442dd35c1df09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateSaturatingIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/saturatinginst">SaturatingInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### eliminateSDiv() {#a664aaf46532d6ebeed0dfeb704308d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateSDiv (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * SDiv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a689a03df5b4ae094d6a3a1bd13dac574">llvm::Instruction::isExact</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### eliminateTrunc() {#a6f5eb28a130d94e94dff2f9e798617ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::eliminateTrunc (<a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a> * TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a9d5f70171d811078c4d263811f13c121">llvm::ICmpInst::getSignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#af07a09f1cda33d984cc725dc9e856d40">llvm::ICmpInst::getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### foldIVUser() {#a12f6125cdd608cb0459585ddb68ead53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SimplifyIndvar::foldIVUser (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold an IV operand into its use.</p>


<p>This removes increments of an aligned IV when used by a instruction that ignores the low bits.</p>


<p>IVOperand is guaranteed SCEVable, but UseInst may not be.</p>


<p>Return the operand of IVOperand for this induction variable if IVOperand can be folded (in case more folding opportunities have been exposed). Otherwise return null.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ad4613def4002aa69721553e567ca4187">llvm::Instruction::dropPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a689a03df5b4ae094d6a3a1bd13dac574">llvm::Instruction::isExact</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### hasChanged() {#ab034f8c7eb931424cbc2a9749f8356ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::hasChanged ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### makeIVComparisonInvariant() {#a304f0837129322608c9e0384d193a0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::makeIVComparisonInvariant (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICmp, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a837209d51e75f7afcfdf457b20e59493">llvm::SCEVCheapExpansionBudget</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a126a12b67fa620ad28ec0c919ca7a3e8">llvm::CmpInst::setPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#acccaf0eaeef2b860b1182f8985f59e94">eliminateIVComparison</a>.</p>

</div>
</div>

### pushIVUsers() {#abcbabc703d62c3cc425d6b03dd1d3ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::pushIVUsers (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt; &amp; Simplified, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &gt; &amp; SimpleIVUsers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add all uses of Def to the current IV's worklist.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### replaceFloatIVWithIntegerIV() {#a16096e55b9292113f13073fa2343b9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::replaceFloatIVWithIntegerIV (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate redundant type cast between integer and float.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad9b99a13e459cb18bb386ddd610ecf8c">llvm::Type::getFPMantissaWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### replaceIVUserWithLoopInvariant() {#a287ee23f262c0a9deb16096da9d34e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::replaceIVUserWithLoopInvariant (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the UseInst with a loop invariant expression if it is safe.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1c43bfed9a4937c8f7918ac6fb09c56">llvm::formLCSSAForInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a1869a16772f9088e7536b3488405a066">GetLoopInvariantInsertPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a837209d51e75f7afcfdf457b20e59493">llvm::SCEVCheapExpansionBudget</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### replaceRemWithNumerator() {#ad4ea440b89ee11cd2aaecfd52290e069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::replaceRemWithNumerator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * Rem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a9a4e22418fd040f349bdecefdc303c2e">simplifyIVRemainder</a>.</p>

</div>
</div>

### replaceRemWithNumeratorOrZero() {#a645f6e970e94d7ca51922b3932338f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::replaceRemWithNumeratorOrZero (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * Rem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>.</p>


<p>Referenced by <a href="#a9a4e22418fd040f349bdecefdc303c2e">simplifyIVRemainder</a>.</p>

</div>
</div>

### replaceSRemWithURem() {#a8a96c9b1143670a73852464de9950e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::replaceSRemWithURem (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * Rem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a9a4e22418fd040f349bdecefdc303c2e">simplifyIVRemainder</a>.</p>

</div>
</div>

### runUnswitching() {#a018e1ba64d8ecb5b3a8a9c95cfd331da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::runUnswitching ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### simplifyIVRemainder() {#a9a4e22418fd040f349bdecefdc303c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::simplifyIVRemainder (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * Rem, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SimplifyIVUsers helper for eliminating useless remainder operations operating on an induction variable or replacing srem by urem.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad4ea440b89ee11cd2aaecfd52290e069">replaceRemWithNumerator</a>, <a href="#a645f6e970e94d7ca51922b3932338f51">replaceRemWithNumeratorOrZero</a> and <a href="#a8a96c9b1143670a73852464de9950e8e">replaceSRemWithURem</a>.</p>


<p>Referenced by <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>.</p>

</div>
</div>

### simplifyUsers() {#a1ba99155749ea6a41858f9bc4449f543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimplifyIndvar::simplifyUsers (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * CurrIV, <a href="/web-llvm/docs/api/classes/llvm/ivvisitor">IVVisitor</a> * V=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iteratively perform simplification on a worklist of users of the specified induction variable.</p>


<p>This is the top-level driver that applies all simplifications to users of an IV.</p>


<p>Each successive simplification may push more users which may themselves be candidates for simplification.</p>


<p>This algorithm does not require <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> analysis. Instead, it simplifies instructions in-place during analysis. Rather than rewriting induction variables bottom-up from their users, it transforms a chain of <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> top-down, updating the IR only when it encounters a clear optimization opportunity.</p>


<p>Once DisableIVRewrite is default, LSR will be the only client of <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a>.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a08427a7d29ad22c694e5447d0d0adf4a">eliminateIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a12f6125cdd608cb0459585ddb68ead53">foldIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a3e219df8a1368668aa0aac77616a4ce9">isSimpleIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#abcbabc703d62c3cc425d6b03dd1d3ef5">pushIVUsers</a>, <a href="#a16096e55b9292113f13073fa2343b9c7">replaceFloatIVWithIntegerIV</a>, <a href="#a287ee23f262c0a9deb16096da9d34e7a">replaceIVUserWithLoopInvariant</a>, <a href="#a7ef1c9cb26f85c3ef0e39c3b0d6df989">strengthenBinaryOp</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>

</div>
</div>

### strengthenBinaryOp() {#a7ef1c9cb26f85c3ef0e39c3b0d6df989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::strengthenBinaryOp (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ad6315ffed3396dd69c53e1e51cfcd9f6">strengthenOverflowingOperation</a> and <a href="#a8ff215a6e938a8df32c29c99bc126603">strengthenRightShift</a>.</p>


<p>Referenced by <a href="#a1ba99155749ea6a41858f9bc4449f543">simplifyUsers</a>.</p>

</div>
</div>

### strengthenOverflowingOperation() {#ad6315ffed3396dd69c53e1e51cfcd9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::strengthenOverflowingOperation (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Annotate BO with nsw / nuw if it provably does not signed-overflow / unsigned-overflow.</p>


<p>Returns true if anything changed, false otherwise.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#adfe987ba0fa56ab9ecdb606c2462b6b9">llvm::ScalarEvolution::maskFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>.</p>


<p>Referenced by <a href="#a7ef1c9cb26f85c3ef0e39c3b0d6df989">strengthenBinaryOp</a>.</p>

</div>
</div>

### strengthenRightShift() {#a8ff215a6e938a8df32c29c99bc126603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimplifyIndvar::strengthenRightShift (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Annotate the Shr in (X &lt;&lt; IVOperand) &gt;&gt; C as exact using the information from the IV's range.</p>


<p>Returns true if anything changed, false otherwise.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4d69e164b5fb0f73a15a07119c4302f7">llvm::ConstantRange::getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a689a03df5b4ae094d6a3a1bd13dac574">llvm::Instruction::isExact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac01940f561517355e394911c203bcedf">llvm::Instruction::setIsExact</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a7ef1c9cb26f85c3ef0e39c3b0d6df989">strengthenBinaryOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Changed {#aacc9bd06acb15df166ae28bb4905490d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::Changed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### DeadInsts {#a32dbbed79b0b157474ee94720560ca5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;WeakTrackingVH&gt;&amp; anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::DeadInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### DT {#a2644f97d4fb76f14b8da4244c73de249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### L {#a938296bce5ed4ce4cfc4603fc4d23e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### LI {#ae862f582600b34487d706d33b8461041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### Rewriter {#ac6324295d78c2ad6e97e34b2806cbe87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVExpander&amp; anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::Rewriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### RunUnswitching {#a0565c03a96527aa9d0b2d2f75a05a968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::RunUnswitching = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### SE {#a8f1b2309852a5d82808f9d27ddc4bf85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### TTI {#a9cb2fa2cca93d7ebc31dccd07957b3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
