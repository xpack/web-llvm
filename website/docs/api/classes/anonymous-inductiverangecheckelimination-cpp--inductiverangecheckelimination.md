---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InductiveRangeCheckElimination` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca8fd7220625f7847e2b364a6b23d74">GetBFIFunc</a> = std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">llvm::BlockFrequencyInfo</a> &amp;()&gt; &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29ae5777abb94e5c296e45ea3be250a">InductiveRangeCheckElimination</a> (ScalarEvolution &amp;SE, BranchProbabilityInfo *BPI, DominatorTree &amp;DT, LoopInfo &amp;LI, GetBFIFunc GetBFI=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56db9cf79e7501bf38278f849774369">run</a> (Loop *L, function_ref&lt; void(Loop *, bool)&gt; LPMAddNewLoop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80347be74276f4578a8fec6921ab3149">estimatedTripCount</a> (const Loop &amp;L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd16fae067dbb3de26f283930a0b71a1">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641a9c254c07d34055a82b532f6f4e0a">BPI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fed5b1ab7c974e92a8f65bf073f0c11">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0147865e3bf0541f6f1b7084fb8dea77">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">GetBFIFunc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea9f7288ab5414d4f1955225c49bc24">GetBFI</a></td>
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


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### GetBFIFunc {#aaca8fd7220625f7847e2b364a6b23d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::GetBFIFunc = 
      std::optional&lt;llvm::function_ref&lt;llvm::BlockFrequencyInfo &amp;()&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InductiveRangeCheckElimination() {#ad29ae5777abb94e5c296e45ea3be250a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::InductiveRangeCheckElimination (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, GetBFIFunc GetBFI=std::nullopt)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#af56db9cf79e7501bf38278f849774369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductiveRangeCheckElimination::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, bool)&gt; LPMAddNewLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a0e0bc3ef0820cacee5dcac4ba57226c9">AllowUnsignedLatchCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a446af5357a9d75c1c6230bb23792a9f8">IntersectSignedRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aac7331d34e77a2d041b4ecc387db1318">IntersectUnsignedRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a2bec6d7cd41654d71a6d9fa597376d82">LoopSizeCutoff</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aa07defc33639893337faf0ae57cb7471">MinEliminatedChecks</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aa39a9321e2213895b5c2a7b8e495a0f8">PrintChangedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a0d1c86bd19eb2f052d30afc7a9285f92">PrintRangeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ab2f89054e1154b0ed16bd7574a78c264">SkipProfitabilityChecks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### estimatedTripCount() {#a80347be74276f4578a8fec6921ab3149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; InductiveRangeCheckElimination::estimatedTripCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BPI {#a641a9c254c07d34055a82b532f6f4e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### DT {#a9fed5b1ab7c974e92a8f65bf073f0c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### GetBFI {#a2ea9f7288ab5414d4f1955225c49bc24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetBFIFunc anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::GetBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### LI {#a0147865e3bf0541f6f1b7084fb8dea77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

</div>
</div>

### SE {#afd16fae067dbb3de26f283930a0b71a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp">InductiveRangeCheckElimination.cpp</a>.</p>

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
