---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-looppredication-cpp-/looppredication
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopPredication` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LoopPredication.cpp}::LoopPredication { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615feddef0ecda2973aa96a6050d8d30">LoopPredication</a> (AliasAnalysis *AA, DominatorTree *DT, ScalarEvolution *SE, LoopInfo *LI, MemorySSAUpdater *MSSAU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037f8481d5dc0c43741972ede1461d86">runOnLoop</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e42a32e9b9c7d28452950578e0b4990">isSupportedStep</a> (const SCEV *Step)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e98d99db5d2f0193c8a17e0975b896">parseLoopICmp</a> (ICmpInst *ICI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac124a9e4f698f0af683aa213a5ff73a4">parseLoopLatchICmp</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2552852df498fdb18e9bfb9774ff333e">findInsertPt</a> (Instruction *User, ArrayRef&lt; Value * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an insertion point suitable for inserting a safe to speculate instruction whose only user will be '<a href="/web-llvm/docs/api/classes/llvm/user">User</a>' which has operands 'Ops'. <a href="#a2552852df498fdb18e9bfb9774ff333e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc50a70ad2840e71929161c96ed1b41">findInsertPt</a> (const SCEVExpander &amp;Expander, Instruction *User, ArrayRef&lt; const SCEV * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above, <em>except</em> that this uses the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> definition of invariant which is that an expression <em>can be made</em> invariant via <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a>. <a href="#a4fc50a70ad2840e71929161c96ed1b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1747a50d5388e6c2cd5feca8cbfd9b05">isLoopInvariantValue</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the value is known to produce a single fixed value across all iterations on which it executes. <a href="#a1747a50d5388e6c2cd5feca8cbfd9b05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8278c48f2003b339fb1a60eb72c780d4">expandCheck</a> (SCEVExpander &amp;Expander, Instruction *Guard, ICmpInst::Predicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9bcfd081a08ab4013c9e96984fd3f8">widenICmpRangeCheck</a> (ICmpInst *ICI, SCEVExpander &amp;Expander, Instruction *Guard)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If ICI can be widened to a loop invariant condition emits the loop invariant condition in the loop preheader and return it, otherwise returns std::nullopt. <a href="#a2f9bcfd081a08ab4013c9e96984fd3f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1f0cfba90fbd609f116d566a3fa57b">widenICmpRangeCheckIncrementingLoop</a> (LoopICmp LatchCheck, LoopICmp RangeCheck, SCEVExpander &amp;Expander, Instruction *Guard)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5743fcc074ef11d2ddd784cc2e69dcd">widenICmpRangeCheckDecrementingLoop</a> (LoopICmp LatchCheck, LoopICmp RangeCheck, SCEVExpander &amp;Expander, Instruction *Guard)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91e1ec874eab4f1672864199b59c124">widenChecks</a> (SmallVectorImpl&lt; Value * &gt; &amp;Checks, SmallVectorImpl&lt; Value * &gt; &amp;WidenedChecks, SCEVExpander &amp;Expander, Instruction *Guard)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a292e4c4aac4b8f5692bb68c0bd7de0">widenGuardConditions</a> (IntrinsicInst *II, SCEVExpander &amp;Expander)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d75daf0a264b1cf0fc2b56abb3bbd11">widenWidenableBranchGuardConditions</a> (BranchInst *Guard, SCEVExpander &amp;Expander)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f5f7d8998de6cef69d5a3ab2a4d3ad">isLoopProfitableToPredicate</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dbfb31c12bba10204f15c1bd8c1117">predicateLoopExits</a> (Loop *L, SCEVExpander &amp;Rewriter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements an analogous, but entirely distinct transform from the main loop predication transform. <a href="#a83dbfb31c12bba10204f15c1bd8c1117">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ae903bb3bbf4d6c70c0e658de91b53">AA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5840b4152d83a0b9ad7ab3ee7461df91">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30d7c92ea0b19b73d44f0b60eb3c577">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503e82bdfda594d9fcefd8b86cf2f2be">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01279fa3fe8b1e9a233723fee60e41af">MSSAU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6253f79f903386d93a02147f7e9e28">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4092e86c74ce6bf566170fb85319ac01">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0438f51015342b9760b8dabf7579961">Preheader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af313f400d5d72487b7d69b2e50ec57ec">LatchCheck</a></td>
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


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopPredication() {#a615feddef0ecda2973aa96a6050d8d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopPredication.cpp}::LoopPredication::LoopPredication (<a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnLoop() {#a037f8481d5dc0c43741972ede1461d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::runOnLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656efdcee3deb029763304d3e741a2d1">llvm::isGuard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa36af57c5a44173f32eb7b4c9011c298">llvm::isGuardAsWidenableBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#aaa904c7d58e452f6371316ed0f5fec68">PredicateWidenableBranchGuards</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expandCheck() {#a8278c48f2003b339fb1a60eb72c780d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LoopPredication::expandCheck (<a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Guard, ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### findInsertPt() {#a2552852df498fdb18e9bfb9774ff333e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{LoopPredication.cpp}::LoopPredication::findInsertPt (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an insertion point suitable for inserting a safe to speculate instruction whose only user will be '<a href="/web-llvm/docs/api/classes/llvm/user">User</a>' which has operands 'Ops'.</p>


<p>A trivial result would be the at the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> itself, but we try to return a loop invariant location if possible.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### findInsertPt() {#a4fc50a70ad2840e71929161c96ed1b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{LoopPredication.cpp}::LoopPredication::findInsertPt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above, <em>except</em> that this uses the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> definition of invariant which is that an expression <em>can be made</em> invariant via <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a>.</p>


<p>Thus, this version is only suitable for finding an insert point to be passed to SCEVExpander!</p>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### isLoopInvariantValue() {#a1747a50d5388e6c2cd5feca8cbfd9b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::isLoopInvariantValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the value is known to produce a single fixed value across all iterations on which it executes.</p>


<p>Note that this does not imply speculation safety. That must be established separately.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### isLoopProfitableToPredicate() {#ac5f5f7d8998de6cef69d5a3ab2a4d3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::isLoopProfitableToPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### isSupportedStep() {#a6e42a32e9b9c7d28452950578e0b4990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::isSupportedStep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### parseLoopICmp() {#a88e98d99db5d2f0193c8a17e0975b896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LoopICmp &gt; LoopPredication::parseLoopICmp (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### parseLoopLatchICmp() {#ac124a9e4f698f0af683aa213a5ff73a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LoopICmp &gt; LoopPredication::parseLoopLatchICmp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### predicateLoopExits() {#a83dbfb31c12bba10204f15c1bd8c1117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::predicateLoopExits (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Rewriter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This implements an analogous, but entirely distinct transform from the main loop predication transform.</p>


<p>This one is phrased in terms of using a widenable branch <em>outside</em> the loop to allow us to simplify loop exits in a following loop. This is close in spirit to the IndVarSimplify transform of the same name, but is materially different widening loosens legality sharply.</p>


<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenChecks() {#ae91e1ec874eab4f1672864199b59c124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopPredication::widenChecks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; WidenedChecks, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Guard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenGuardConditions() {#a8a292e4c4aac4b8f5692bb68c0bd7de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::widenGuardConditions (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenICmpRangeCheck() {#a2f9bcfd081a08ab4013c9e96984fd3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; LoopPredication::widenICmpRangeCheck (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICI, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Guard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If ICI can be widened to a loop invariant condition emits the loop invariant condition in the loop preheader and return it, otherwise returns std::nullopt.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenICmpRangeCheckDecrementingLoop() {#ad5743fcc074ef11d2ddd784cc2e69dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; LoopPredication::widenICmpRangeCheckDecrementingLoop (<a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> LatchCheck, <a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> RangeCheck, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Guard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenICmpRangeCheckIncrementingLoop() {#a0d1f0cfba90fbd609f116d566a3fa57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; LoopPredication::widenICmpRangeCheckIncrementingLoop (<a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> LatchCheck, <a href="/web-llvm/docs/api/structs/anonymous-looppredication-cpp-/loopicmp">LoopICmp</a> RangeCheck, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Guard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### widenWidenableBranchGuardConditions() {#a4d75daf0a264b1cf0fc2b56abb3bbd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopPredication::widenWidenableBranchGuardConditions (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * Guard, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Expander)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a25ae903bb3bbf4d6c70c0e658de91b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{LoopPredication.cpp}::LoopPredication::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### DL {#a4092e86c74ce6bf566170fb85319ac01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{LoopPredication.cpp}::LoopPredication::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### DT {#a5840b4152d83a0b9ad7ab3ee7461df91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopPredication.cpp}::LoopPredication::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### L {#a1e6253f79f903386d93a02147f7e9e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopPredication.cpp}::LoopPredication::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### LatchCheck {#af313f400d5d72487b7d69b2e50ec57ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopICmp anonymous{LoopPredication.cpp}::LoopPredication::LatchCheck</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### LI {#a503e82bdfda594d9fcefd8b86cf2f2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopPredication.cpp}::LoopPredication::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### MSSAU {#a01279fa3fe8b1e9a233723fee60e41af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* anonymous{LoopPredication.cpp}::LoopPredication::MSSAU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### Preheader {#ab0438f51015342b9760b8dabf7579961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopPredication.cpp}::LoopPredication::Preheader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

### SE {#aa30d7c92ea0b19b73d44f0b60eb3c577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{LoopPredication.cpp}::LoopPredication::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp">LoopPredication.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
