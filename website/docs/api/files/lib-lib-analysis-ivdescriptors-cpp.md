---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/ivdescriptors-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `IVDescriptors.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">llvm/Analysis/IVDescriptors.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">llvm/Analysis/DemandedBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78d689f88c58652639663f07a64ca41">lookThroughAnd</a> (PHINode *Phi, Type *&amp;RT, SmallPtrSetImpl&lt; Instruction * &gt; &amp;Visited, SmallPtrSetImpl&lt; Instruction * &gt; &amp;CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines if Phi may have been type-promoted. <a href="#aa78d689f88c58652639663f07a64ca41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af481dabda60939ffaa5c0da35892dc96">computeRecurrenceType</a> (Instruction *Exit, DemandedBits *DB, AssumptionCache *AC, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the minimal bit width needed to represent a reduction whose exit instruction is given by Exit. <a href="#af481dabda60939ffaa5c0da35892dc96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586a0928ddd8c387ebb2032e9f61e55b">collectCastInstrs</a> (Loop *TheLoop, Instruction *Exit, Type *RecurrenceType, SmallPtrSetImpl&lt; Instruction * &gt; &amp;Casts, unsigned &amp;MinWidthCastToRecurTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect cast instructions that can be ignored in the vectorizer's cost model, given a reduction exit value and the minimal type in which the. <a href="#a586a0928ddd8c387ebb2032e9f61e55b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65aa908de5625be851aa7b97327d194b">checkOrderedReduction</a> (RecurKind Kind, Instruction *ExactFPMathInst, Instruction *Exit, PHINode *Phi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a> (PredicatedScalarEvolution &amp;PSE, const SCEVUnknown *PhiScev, const SCEVAddRecExpr *AR, SmallVectorImpl&lt; Instruction * &gt; &amp;CastInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is called when we suspect that the update-chain of a phi node (whose symbolic <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression sin <span class="doxyComputerOutput">PhiScev</span>) contains redundant casts, that can be ignored. <a href="#a1890db236ee0485fd31d3d99d6ad09b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"iv-descriptors"</td>
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


<div class="doxySectionDef">

## Functions

### checkOrderedReduction() {#a65aa908de5625be851aa7b97327d194b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkOrderedReduction (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExactFPMathInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaa7dad289ea38506fb1c9b5b148405d0c">llvm::FMulAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a08416fb970e8c177c7d78452d927c606">llvm::RecurrenceDescriptor::isFMulAddIntrinsic</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>.</p>

</div>
</div>

### collectCastInstrs() {#a586a0928ddd8c387ebb2032e9f61e55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void collectCastInstrs (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RecurrenceType, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Casts, unsigned &amp; MinWidthCastToRecurTy)</td>
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

<p>Collect cast instructions that can be ignored in the vectorizer's cost model, given a reduction exit value and the minimal type in which the.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>.</p>

</div>
</div>

### computeRecurrenceType() {#af481dabda60939ffaa5c0da35892dc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Type *, bool &gt; computeRecurrenceType (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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

<p>Compute the minimal bit width needed to represent a reduction whose exit instruction is given by Exit.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>.</p>

</div>
</div>

### getCastsForInductionPHI() {#a1890db236ee0485fd31d3d99d6ad09b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getCastsForInductionPHI (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * PhiScev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; CastInsts)</td>
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

<p>This function is called when we suspect that the update-chain of a phi node (whose symbolic <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression sin <span class="doxyComputerOutput">PhiScev</span>) contains redundant casts, that can be ignored.</p>


<p>(This can happen when the PSCEV rewriter adds a runtime predicate P under which the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the phi can be the AddRecurrence <span class="doxyComputerOutput">AR</span>; See createAddRecFromPHIWithCast). We want to find the cast instructions that are involved in the update-chain of this induction. A caller that adds the required runtime predicate can be free to drop these cast instructions, and compute the phi using <span class="doxyComputerOutput">AR</span> (instead of some scev expression with casts).</p>


<p>For example, without a predicate the scev expression can take the following form: (Ext ix (Trunc iy ( Start + i*Step ) to ix) to iy)</p>


<p>It corresponds to the following IR sequence: for.body: x = phi i64 [ 0, ph ], [ add, for.body ] casted_phi = "ExtTrunc i64 %x" add = add i64 casted_phi, step</p>


<p>where x is given in <span class="doxyComputerOutput">PN</span>, PSE.getSCEV(x) is equal to PSE.getSCEV(casted_phi) under a predicate, and the IR sequence that "ExtTrunc i64 %x" represents can take one of several forms, for example, such as: ExtTrunc1: casted_phi = and x, 2^n-1 or: ExtTrunc2: t = shl x, m casted_phi = ashr t, m</p>


<p>If we are able to find such sequence, we return the instructions we found, namely casted_phi and the instructions on its use-def chain up to the phi (not including the phi).</p>


<p>Definition at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aa1aac224801967b8ca7361a4a71b36f7">llvm::PredicatedScalarEvolution::areAddRecsEqualWithPreds</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#ae0994d8207b94ad22ecebc1a6bc580f1">llvm::PredicatedScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>.</p>

</div>
</div>

### lookThroughAnd() {#aa78d689f88c58652639663f07a64ca41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * lookThroughAnd (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; RT, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; CI)</td>
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

<p>Determines if Phi may have been type-promoted.</p>


<p>If Phi has a single user that ANDs the Phi with a type mask, return the user. RT is updated to account for the narrower bit width represented by the mask, and the AND instruction is added to CI.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2adca0e23c974dbb32019dccb22547bc">llvm::PatternMatch::m_Instruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"iv-descriptors"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
