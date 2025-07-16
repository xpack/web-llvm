---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InductiveRangeCheck` Class Reference

<p>An inductive range check is conditional branch in a loop with a condition that is provably true for some contiguous range of values taken by the containing loop's induction variable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6709b9851ee55f06c9515f022c53ec33">getBegin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b56801b98967c4e4b2663fb711b050f">getStep</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c6e032de04288a634c923fe14fef30">getEnd</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c214fb3a816311a94117f81591e4d7b">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c4682962d0f4e7322c6a703adaa7ee">dump</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb2c4daaa7a8ccddfad1c7eb17ccf60">getCheckUse</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4324a3390e32d07742ff391a206783">getPassingDirection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the value the condition of the branch needs to evaluate to for the branch to take the hot successor (see (1) above). <a href="#afc4324a3390e32d07742ff391a206783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/range">Range</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5591acf152c652226d89a2b5ea436d05">computeSafeIterationSpace</a> (ScalarEvolution &amp;SE, const SCEVAddRecExpr *IndVar, bool IsLatchSigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes a range for the induction variable (IndVar) in which the range check is redundant and can be constant-folded away. <a href="#a5591acf152c652226d89a2b5ea436d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e5408ce0347360619eca1e93001519">Begin</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49cbfee95fde6b171ff412cd58d89c1b">Step</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9043fc7455978e7f06f06c782885685">End</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475e4d73306204789103a35c2c1407fc">CheckUse</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715a08cb04246d426e200c8196ecf0ea">extractRangeChecksFromBranch</a> (BranchInst *BI, Loop *L, ScalarEvolution &amp;SE, BranchProbabilityInfo *BPI, std::optional&lt; uint64_t &gt; EstimatedTripCount, SmallVectorImpl&lt; InductiveRangeCheck &gt; &amp;Checks, bool &amp;Changed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse out a set of inductive range checks from <span class="doxyComputerOutput">BI</span> and append them to <span class="doxyComputerOutput">Checks</span>. <a href="#a715a08cb04246d426e200c8196ecf0ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af080850b5b14a209bf3fa2aef6da2725">parseRangeCheckICmp</a> (Loop *L, ICmpInst *ICI, ScalarEvolution &amp;SE, const SCEVAddRecExpr *&amp;Index, const SCEV *&amp;End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a single ICmp instruction, <span class="doxyComputerOutput">ICI</span>, into a range check. <a href="#af080850b5b14a209bf3fa2aef6da2725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bea49f4c2beb0b1dfb7025774358bfd">extractRangeChecksFromCond</a> (Loop *L, ScalarEvolution &amp;SE, Use &amp;ConditionUse, SmallVectorImpl&lt; InductiveRangeCheck &gt; &amp;Checks, SmallPtrSetImpl&lt; Value * &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab9cae0e71492181c837df1e4b6d0ef">parseIvAgaisntLimit</a> (Loop *L, Value *LHS, Value *RHS, ICmpInst::Predicate Pred, ScalarEvolution &amp;SE, const SCEVAddRecExpr *&amp;Index, const SCEV *&amp;End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c6d7336a6e3520dbdb02d9bcf6114f">reassociateSubLHS</a> (Loop *L, Value *VariantLHS, Value *InvariantRHS, ICmpInst::Predicate Pred, ScalarEvolution &amp;SE, const SCEVAddRecExpr *&amp;Index, const SCEV *&amp;End)</td>
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

<p>An inductive range check is conditional branch in a loop with a condition that is provably true for some contiguous range of values taken by the containing loop's induction variable.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### computeSafeIterationSpace() {#a5591acf152c652226d89a2b5ea436d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InductiveRangeCheck::Range &gt; InductiveRangeCheck::computeSafeIterationSpace (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * IndVar, bool IsLatchSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes a range for the induction variable (IndVar) in which the range check is redundant and can be constant-folded away.</p>


<p>Computes and returns a range of values for the induction variable (IndVar) in which the range check can be safely elided.</p>


<p>The induction variable is not required to be the canonical {0,+,1} induction variable.</p>


<p>If it cannot compute such a range, returns std::nullopt.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="#a6709b9851ee55f06c9515f022c53ec33">getBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="#aa3c6e032de04288a634c923fe14fef30">getEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8bcb86d8d126d95b0dc05f09e8f3df96">llvm::ScalarEvolution::getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a083bb1deb1d2ba244a99ceae9e734bc1">llvm::ScalarEvolution::getNegativeSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3fbe8f529d36d76730550905d730a2a7">llvm::ScalarEvolution::getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ab26bea71791cf347c631d2072e41cfb5">llvm::ScalarEvolution::getSignExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0d1d4b1c8787f465ce2c144757731f12">llvm::ScalarEvolution::getSMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a223d678f85ac9b7f03157edb6111e42e">llvm::ScalarEvolution::getSMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="#a1b56801b98967c4e4b2663fb711b050f">getStep</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a83c084b0947edf4ae748f9a73babf7b8">llvm::ScalarEvolution::getTruncateExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/range/#aca7849060290983d710c6194671546f2">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::Range::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2579491850c605c8b7cf3439a907fbed">llvm::ScalarEvolution::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc1d309b62fc59309659ac3fa7f3f68f">llvm::isKnownNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af042aac9d86aacb5ee9e1af24590f4c2">llvm::isKnownNonNegativeInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a07d028b54d5d81f7eb266f852632d86b">NoopOrExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#af47d800c628b33c20b0c6bf2031d3fdf">PrintScaledBoundaryRangeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### dump() {#a74c4682962d0f4e7322c6a703adaa7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::dump ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### getBegin() {#a6709b9851ee55f06c9515f022c53ec33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::getBegin ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>Referenced by <a href="#a5591acf152c652226d89a2b5ea436d05">computeSafeIterationSpace</a>.</p>

</div>
</div>

### getCheckUse() {#abeb2c4daaa7a8ccddfad1c7eb17ccf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::getCheckUse ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>Referenced by <a href="#a2c214fb3a816311a94117f81591e4d7b">print</a>.</p>

</div>
</div>

### getEnd() {#aa3c6e032de04288a634c923fe14fef30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::getEnd ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>Referenced by <a href="#a5591acf152c652226d89a2b5ea436d05">computeSafeIterationSpace</a>.</p>

</div>
</div>

### getPassingDirection() {#afc4324a3390e32d07742ff391a206783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::getPassingDirection ()</td>
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

<p>This is the value the condition of the branch needs to evaluate to for the branch to take the hot successor (see (1) above).</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### getStep() {#a1b56801b98967c4e4b2663fb711b050f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::getStep ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>Referenced by <a href="#a5591acf152c652226d89a2b5ea436d05">computeSafeIterationSpace</a>.</p>

</div>
</div>

### print() {#a2c214fb3a816311a94117f81591e4d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>Reference <a href="#abeb2c4daaa7a8ccddfad1c7eb17ccf60">getCheckUse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Begin {#a41e5408ce0347360619eca1e93001519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::Begin = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### CheckUse {#a475e4d73306204789103a35c2c1407fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::CheckUse = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### End {#aa9043fc7455978e7f06f06c782885685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### Step {#a49cbfee95fde6b171ff412cd58d89c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::Step = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### extractRangeChecksFromBranch() {#a715a08cb04246d426e200c8196ecf0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InductiveRangeCheck::extractRangeChecksFromBranch (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * BI, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, std::optional&lt; uint64_t &gt; EstimatedTripCount, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck">InductiveRangeCheck</a> &gt; &amp; Checks, bool &amp; Changed)</td>
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

<p>Parse out a set of inductive range checks from <span class="doxyComputerOutput">BI</span> and append them to <span class="doxyComputerOutput">Checks</span>.</p>


<p>NB! There may be conditions feeding into <span class="doxyComputerOutput">BI</span> that aren't inductive range checks, and hence don't end up in <span class="doxyComputerOutput">Checks</span>.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a46502d648608aa13cb485ed4af447d88">llvm::BranchProbabilityInfo::getEdgeProbability</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aa07defc33639893337faf0ae57cb7471">MinEliminatedChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ab2f89054e1154b0ed16bd7574a78c264">SkipProfitabilityChecks</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#aa4f2ab60e1bb687cc5d9999ca97d57c2">llvm::BranchProbabilityInfo::swapSuccEdgesProbabilities</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination/#af56db9cf79e7501bf38278f849774369">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### extractRangeChecksFromCond() {#a8bea49f4c2beb0b1dfb7025774358bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InductiveRangeCheck::extractRangeChecksFromCond (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; ConditionUse, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck">InductiveRangeCheck</a> &gt; &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Visited)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### parseIvAgaisntLimit() {#a6ab9cae0e71492181c837df1e4b6d0ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductiveRangeCheck::parseIvAgaisntLimit (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *&amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; End)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### parseRangeCheckICmp() {#af080850b5b14a209bf3fa2aef6da2725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductiveRangeCheck::parseRangeCheckICmp (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *&amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; End)</td>
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

<p>Parse a single ICmp instruction, <span class="doxyComputerOutput">ICI</span>, into a range check.</p>


<p>If <span class="doxyComputerOutput">ICI</span> cannot be interpreted as a range check, return false. Otherwise set <span class="doxyComputerOutput">Index</span> to the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> being range checked, and set <span class="doxyComputerOutput">End</span> to the upper or lower limit <span class="doxyComputerOutput">Index</span> is being range checked.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### reassociateSubLHS() {#a93c6d7336a6e3520dbdb02d9bcf6114f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductiveRangeCheck::reassociateSubLHS (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VariantLHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InvariantRHS, ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *&amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; End)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
