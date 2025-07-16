---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevaddrecexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEVAddRecExpr` Class Reference

<p>This node represents a polynomial recurrence on the trip count of the specified loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVAddRecExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr">SCEVNAryExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node is a base class providing common functionality for n'ary operators. <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021535ad9d178dccecc793244e6bc32e">SCEVAddRecExpr</a> (const FoldingSetNodeIDRef ID, const SCEV *const *O, size_t N, const Loop *l)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1596600146d065022af8b9c4a1d0b427">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c13fe96d59c787e900b7bbf7173263">getStart</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ab4a82c6d7373e2e367986b9527bf0">getLoop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4049f7040a4628b15f182c3c9aaf802a">getStepRecurrence</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs and returns the recurrence indicating how much this expression steps by. <a href="#a4049f7040a4628b15f182c3c9aaf802a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bb7394d874cbbef1d81e6bea89d4f3">isAffine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this represents an expression A + B*x where A and B are loop invariant values. <a href="#a54bb7394d874cbbef1d81e6bea89d4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e91958e021e28eb6fbd30f76c96b731">isQuadratic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this represents an expression A + B*x + C*x^2 where A, B and C are loop invariant values. <a href="#a5e91958e021e28eb6fbd30f76c96b731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5316a2763777f3670c1606452f4e99d7">setNoWrapFlags</a> (NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set flags for a recurrence without clearing any previously set flags. <a href="#a5316a2763777f3670c1606452f4e99d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33583576f220997d1c415df033559a57">evaluateAtIteration</a> (const SCEV *It, ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of this chain of recurrences at the specified iteration number. <a href="#a33583576f220997d1c415df033559a57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a> (const ConstantRange &amp;Range, ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of iterations of this loop that produce values in the specified constant range. <a href="#a7e688afe102c3fa48ea49cb972a0f00c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3dc6f52dcd0a9cf61508d5703cbe57">getPostIncExpr</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an expression representing the value of this expression one iteration of the loop ahead. <a href="#a8e3dc6f52dcd0a9cf61508d5703cbe57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cfd1a8d0cabc73cccbbf6fe9bbc8522">L</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f92c963408bac18b86bf6f0cfeb06f">evaluateAtIteration</a> (ArrayRef&lt; const SCEV * &gt; Operands, const SCEV *It, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of this chain of recurrences at the specified iteration number. <a href="#aa6f92c963408bac18b86bf6f0cfeb06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b096608fec2f6b2c6d5b4fec2dbb6c">classof</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a93b096608fec2f6b2c6d5b4fec2dbb6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This node represents a polynomial recurrence on the trip count of the specified loop.</p>


<p>This is the primary focus of the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> framework; all the other <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> subclasses are mostly just supporting infrastructure to allow <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> expressions to be created and analyzed.</p>


<p>All operands of an AddRec are required to be loop invariant.</p>


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ScalarEvolution {#a15a0237aaba54972c69acad43448c093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a> and <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a76d2af00b10cda0b511a84a742d13f00">llvm::SCEVNAryExpr::SCEVNAryExpr</a>.</p>


<p>Referenced by <a href="#aa6f92c963408bac18b86bf6f0cfeb06f">evaluateAtIteration</a>, <a href="#a33583576f220997d1c415df033559a57">evaluateAtIteration</a>, <a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a>, <a href="#a8e3dc6f52dcd0a9cf61508d5703cbe57">getPostIncExpr</a>, <a href="#a4049f7040a4628b15f182c3c9aaf802a">getStepRecurrence</a> and <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SCEVAddRecExpr() {#a021535ad9d178dccecc793244e6bc32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVAddRecExpr::SCEVAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * O, size_t N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * l)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateAtIteration() {#a33583576f220997d1c415df033559a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * SCEVAddRecExpr::evaluateAtIteration (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * It, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value of this chain of recurrences at the specified iteration number.</p>


<p>We can evaluate this recurrence by multiplying each element in the chain by the binomial coefficient corresponding to it. In other words, we can evaluate {A,+,B,+,C,+,D} as:</p>


<p>A*BC(It, 0) + B*BC(It, 1) + C*BC(It, 2) + D*BC(It, 3)</p>


<p>where BC(It, k) stands for binomial coefficient.</p>


<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a33583576f220997d1c415df033559a57">evaluateAtIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a> and <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="#a33583576f220997d1c415df033559a57">evaluateAtIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54dedd456f8ee5d9877d13c9717ef94b">EvaluateConstantChrecAtConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/scevloopaddrecrewriter/#a286583ef8d17944c4d4a4e3abcf65fef">llvm::SCEVLoopAddRecRewriter::visitAddRecExpr</a>.</p>

</div>
</div>

### getLoop() {#a99ab4a82c6d7373e2e367986b9527bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop * llvm::SCEVAddRecExpr::getLoop ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a262aeb2eecfb752ae2eecb90bab7ec8a">findIVOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6dc58a1259941c7a17142e6103d059e">llvm::ScalarEvolution::forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5acadc27f8741ff017a264df16bb8885">anonymous{SimplifyIndVar.cpp}::WidenIV::getExtendedOperandRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a>, <a href="#a8e3dc6f52dcd0a9cf61508d5703cbe57">getPostIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="#a4049f7040a4628b15f182c3c9aaf802a">getStepRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a3e219df8a1368668aa0aac77616a4ce9">isSimpleIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevinitrewriter/#ab7555e0b377877b254a14cff2fbe789c">anonymous{ScalarEvolution.cpp}::SCEVInitRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpostincrewriter/#ae2709bd2632b3e205889572afb7cc27f">anonymous{ScalarEvolution.cpp}::SCEVPostIncRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevshiftrewriter/#a94123a099d7fb26bf95c0bb691571567">anonymous{ScalarEvolution.cpp}::SCEVShiftRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-scalarevolutionnormalization-cpp-/normalizedenormalizerewriter/#ac9bcd9133d19e4e656a82dd8e900d3f8">anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter/#aaa2b0da5272312c302e3c605f972234b">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevloopaddrecrewriter/#a286583ef8d17944c4d4a4e3abcf65fef">llvm::SCEVLoopAddRecRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### getNumIterationsInRange() {#a7e688afe102c3fa48ea49cb972a0f00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * SCEVAddRecExpr::getNumIterationsInRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Range, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of iterations of this loop that produce values in the specified constant range.</p>


<p>Another way of looking at this is that it returns the first iteration number where the value is not in the condition, thus computing the exit count. If the iteration count can't be computed, an instance of <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> is returned.</p>


<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 13485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54dedd456f8ee5d9877d13c9717ef94b">EvaluateConstantChrecAtConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a659b27f6737fcb7eaf333b0279da1154">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff9e533399d91febd63fa4bfe82a42a7">llvm::ScalarEvolution::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aaa9b9055fd9c69fe14eb20f0d18d53d5">llvm::ScalarEvolution::getCouldNotCompute</a>, <a href="#a99ab4a82c6d7373e2e367986b9527bf0">getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="#a19c13fe96d59c787e900b7bbf7173263">getStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2c96114e89e8cf2122ebe8bc4d929c7c">llvm::ScalarEvolution::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2579491850c605c8b7cf3439a907fbed">llvm::ScalarEvolution::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a54bb7394d874cbbef1d81e6bea89d4f3">isAffine</a>, <a href="#a5e91958e021e28eb6fbd30f76c96b731">isQuadratic</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#adbb1a17a50dcac886c98f6329540e289">llvm::SCEVNAryExpr::Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a>.</p>

</div>
</div>

### getPostIncExpr() {#a8e3dc6f52dcd0a9cf61508d5703cbe57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr * SCEVAddRecExpr::getPostIncExpr (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an expression representing the value of this expression one iteration of the loop ahead.</p>

<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 13557 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a659b27f6737fcb7eaf333b0279da1154">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="#a99ab4a82c6d7373e2e367986b9527bf0">getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpostincrewriter/#ae2709bd2632b3e205889572afb7cc27f">anonymous{ScalarEvolution.cpp}::SCEVPostIncRewriter::visitAddRecExpr</a>.</p>

</div>
</div>

### getStart() {#a19c13fe96d59c787e900b7bbf7173263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVAddRecExpr::getStart ()</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#adbb1a17a50dcac886c98f6329540e289">llvm::SCEVNAryExpr::Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aa1aac224801967b8ca7361a4a71b36f7">llvm::PredicatedScalarEvolution::areAddRecsEqualWithPreds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7762f1d99f297ecb6ccb4375e715c2ea">getExtendAddRecStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a1596600146d065022af8b9c4a1d0b427">getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a187751c86d349fac41ddc1b807b40b22">mayUsePostIncMode</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a152f85e50f38db96586836800a9e2da4">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToIterCountExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#aca9e38901fab9929c7c586f376249e9a">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToValueExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevinitrewriter/#ab7555e0b377877b254a14cff2fbe789c">anonymous{ScalarEvolution.cpp}::SCEVInitRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter/#aaa2b0da5272312c302e3c605f972234b">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a>.</p>

</div>
</div>

### getStepRecurrence() {#a4049f7040a4628b15f182c3c9aaf802a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVAddRecExpr::getStepRecurrence (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Constructs and returns the recurrence indicating how much this expression steps by.</p>


<p>If this is a polynomial of degree N, it returns a chrec of degree N-1. We cannot determine whether the step recurrence has self-wraparound.</p>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a659b27f6737fcb7eaf333b0279da1154">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="#a99ab4a82c6d7373e2e367986b9527bf0">getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="#a54bb7394d874cbbef1d81e6bea89d4f3">isAffine</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a> and <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aa1aac224801967b8ca7361a4a71b36f7">llvm::PredicatedScalarEvolution::areAddRecsEqualWithPreds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a7fba06debb40db30176f0e6114a3446b">llvm::TargetTransformInfoImplBase::getConstantStrideStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7762f1d99f297ecb6ccb4375e715c2ea">getExtendAddRecStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a187751c86d349fac41ddc1b807b40b22">mayUsePostIncMode</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a152f85e50f38db96586836800a9e2da4">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToIterCountExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#aca9e38901fab9929c7c586f376249e9a">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToValueExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevshiftrewriter/#a94123a099d7fb26bf95c0bb691571567">anonymous{ScalarEvolution.cpp}::SCEVShiftRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter/#aaa2b0da5272312c302e3c605f972234b">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a>.</p>

</div>
</div>

### getType() {#a1596600146d065022af8b9c4a1d0b427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SCEVAddRecExpr::getType ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="#a19c13fe96d59c787e900b7bbf7173263">getStart</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9b6b892760677b9b11c517eb5a46557f">isAddRecSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a187751c86d349fac41ddc1b807b40b22">mayUsePostIncMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter/#aaa2b0da5272312c302e3c605f972234b">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitAddRecExpr</a>.</p>

</div>
</div>

### isAffine() {#a54bb7394d874cbbef1d81e6bea89d4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVAddRecExpr::isAffine ()</td>
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

<p>Return true if this represents an expression A + B*x where A and B are loop invariant values.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0ef183a0f2f6e678cc5f7223aca82535">getFalkorUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a>, <a href="#a4049f7040a4628b15f182c3c9aaf802a">getStepRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a2d58e737d5b362a238d1b9cfbd961532">hasComputableBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a152f85e50f38db96586836800a9e2da4">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToIterCountExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#aca9e38901fab9929c7c586f376249e9a">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::SCEVToValueExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevshiftrewriter/#a94123a099d7fb26bf95c0bb691571567">anonymous{ScalarEvolution.cpp}::SCEVShiftRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a>.</p>

</div>
</div>

### isQuadratic() {#a5e91958e021e28eb6fbd30f76c96b731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVAddRecExpr::isQuadratic ()</td>
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

<p>Return true if this represents an expression A + B*x + C*x^2 where A, B and C are loop invariant values.</p>


<p>This corresponds to an addrec of the form {L,+,M,+,N}</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>.</p>


<p>Referenced by <a href="#a7e688afe102c3fa48ea49cb972a0f00c">getNumIterationsInRange</a>.</p>

</div>
</div>

### setNoWrapFlags() {#a5316a2763777f3670c1606452f4e99d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVAddRecExpr::setNoWrapFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">NoWrapFlags</a> Flags)</td>
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

<p>Set flags for a recurrence without clearing any previously set flags.</p>


<p>For AddRec, either NUW or NSW implies NW. Keep track of this fact here to make it easier to propagate flags.</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8fed3b807739f2ff6942c12407ab00fa">llvm::ScalarEvolution::setFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#ade1f1b89affe842dacd20c7f950e99c9">llvm::SCEV::SubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a248dea99ef1d5a864269ac3a98014b37">llvm::ScalarEvolution::setNoWrapFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### L {#a6cfd1a8d0cabc73cccbbf6fe9bbc8522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* llvm::SCEVAddRecExpr::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a93b096608fec2f6b2c6d5b4fec2dbb6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVAddRecExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#ad4f956914bf94bdcd1058badb5bd90e6">llvm::SCEV::getSCEVType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>.</p>

</div>
</div>

### evaluateAtIteration() {#aa6f92c963408bac18b86bf6f0cfeb06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * SCEVAddRecExpr::evaluateAtIteration (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * It, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Return the value of this chain of recurrences at the specified iteration number.</p>


<p>Takes an explicit list of operands to represent an AddRec.</p>


<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>, definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#adbb1a17a50dcac886c98f6329540e289">llvm::SCEVNAryExpr::Operands</a> and <a href="#a15a0237aaba54972c69acad43448c093">ScalarEvolution</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
