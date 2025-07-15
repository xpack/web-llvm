---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoadEliminationForLoop` Class Reference

<p>The per-loop class that does most of the work. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f662ef3fb315e615c323a6b8174422">LoadEliminationForLoop</a> (Loop *L, LoopInfo *LI, const LoopAccessInfo &amp;LAI, DominatorTree *DT, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::forward_list&lt; <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad870908842303e62050abc131f00f91f">findStoreToLoadDependences</a> (const LoopAccessInfo &amp;LAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look through the loop-carried and loop-independent dependences in this loop and find store-&gt;load dependences. <a href="#ad870908842303e62050abc131f00f91f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b110fde5b0a649629622b90343fb691">getInstrIndex</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the instruction according to program order. <a href="#a2b110fde5b0a649629622b90343fb691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0600a51b42956b4e041baa101a3c047a">removeDependencesFromMultipleStores</a> (std::forward_list&lt; StoreToLoadForwardingCandidate &gt; &amp;Candidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a load has multiple candidates associated (i.e. <a href="#a0600a51b42956b4e041baa101a3c047a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e12473d43a9493e5189ce72f4ede0c3">needsChecking</a> (unsigned PtrIdx1, unsigned PtrIdx2, const SmallPtrSetImpl&lt; Value * &gt; &amp;PtrsWrittenOnFwdingPath, const SmallPtrSetImpl&lt; Value * &gt; &amp;CandLoadPtrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two pointers operations by their <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> indices, return true if they require an alias check. <a href="#a3e12473d43a9493e5189ce72f4ede0c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec02c6710c255838a2c5f10e078c8ba">findPointersWrittenOnForwardingPath</a> (const SmallVectorImpl&lt; StoreToLoadForwardingCandidate &gt; &amp;Candidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointers that are possibly written to on the path from a forwarding store to a load. <a href="#a8ec02c6710c255838a2c5f10e078c8ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc12092fd1db13a69edf142bcad15556">collectMemchecks</a> (const SmallVectorImpl&lt; StoreToLoadForwardingCandidate &gt; &amp;Candidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the pointer alias checks to prove that there are no intervening stores. <a href="#abc12092fd1db13a69edf142bcad15556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9ee85c11fa2173c85a1ba82797d9fb">propagateStoredValueToLoadUsers</a> (const StoreToLoadForwardingCandidate &amp;Cand, SCEVExpander &amp;SEE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the transformation for a candidate. <a href="#acc9ee85c11fa2173c85a1ba82797d9fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b795b0cd98521a7cf4ab769d9207258">processLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-level driver for each loop: find store-&gt;load forwarding candidates, add run-time checks and perform transformation. <a href="#a1b795b0cd98521a7cf4ab769d9207258">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420bfe1fdc39f564f1c049de250a642a">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9eb503b7c4a91cd24ce43b7ee25710">InstOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps the load/store instructions to their index according to program order. <a href="#aad9eb503b7c4a91cd24ce43b7ee25710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd08b1185a6c58784c21c8f48a660d8">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80cb2bc447eb2579bed5cf042a00dab7">LAI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af459336fec8de1188bbeda8bfaf046b6">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d0d7aed09752c7182ac308335c7bb6">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a060c6f07ba59109849089609c4a94">PSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa408310b2f936957872bea70809378c8">PSE</a></td>
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

<p>The per-loop class that does most of the work.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoadEliminationForLoop() {#a10f662ef3fb315e615c323a6b8174422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::LoadEliminationForLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp; LAI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#a14eeb1cfc5947b2dde03d0d8fd89efc4">eliminateLoadsAcrossLoops</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectMemchecks() {#abc12092fd1db13a69edf142bcad15556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; RuntimePointerCheck, 4 &gt; anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::collectMemchecks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &gt; &amp; Candidates)</td>
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

<p>Determine the pointer alias checks to prove that there are no intervening stores.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h/#a2bb73b5d562083dde29e9091dd81bef3">Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d13fd05401d8eb0c97b9864a0eb6028">llvm::copy_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8ec02c6710c255838a2c5f10e078c8ba">findPointersWrittenOnForwardingPath</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a3e12473d43a9493e5189ce72f4ede0c3">needsChecking</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a1b795b0cd98521a7cf4ab769d9207258">processLoop</a>.</p>

</div>
</div>

### findPointersWrittenOnForwardingPath() {#a8ec02c6710c255838a2c5f10e078c8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt; Value *, 4 &gt; anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::findPointersWrittenOnForwardingPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &gt; &amp; Candidates)</td>
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

<p>Return pointers that are possibly written to on the path from a forwarding store to a load.</p>


<p>These pointers need to be alias-checked against the forwarding candidates.</p>


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2b110fde5b0a649629622b90343fb691">getInstrIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0b1373fa0f76edbe1c0999d7d207c9c4">llvm::min_element</a>.</p>


<p>Referenced by <a href="#abc12092fd1db13a69edf142bcad15556">collectMemchecks</a>.</p>

</div>
</div>

### findStoreToLoadDependences() {#ad870908842303e62050abc131f00f91f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::forward_list&lt; StoreToLoadForwardingCandidate &gt; anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::findStoreToLoadDependences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp; LAI)</td>
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

<p>Look through the loop-carried and loop-independent dependences in this loop and find store-&gt;load dependences.</p>


<p>Note that no candidate is returned if LAA has failed to analyze the loop (e.g. if it's not bottom-tested, contains volatile memops, etc.)</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662">llvm::MemoryDepChecker::Dependence::IndirectUnsafe</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a94f850488e8bda1d1b400821d6d61bd1">llvm::CastInst::isBitOrNoopPointerCastable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a4323c151516742793df95050739d72ab">llvm::SmallPtrSetImpl&lt; PtrType &gt;::remove_if</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab">llvm::MemoryDepChecker::Dependence::Unknown</a>.</p>


<p>Referenced by <a href="#a1b795b0cd98521a7cf4ab769d9207258">processLoop</a>.</p>

</div>
</div>

### getInstrIndex() {#a2b110fde5b0a649629622b90343fb691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::getInstrIndex (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p>Return the index of the instruction according to program order.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a8ec02c6710c255838a2c5f10e078c8ba">findPointersWrittenOnForwardingPath</a> and <a href="#a0600a51b42956b4e041baa101a3c047a">removeDependencesFromMultipleStores</a>.</p>

</div>
</div>

### needsChecking() {#a3e12473d43a9493e5189ce72f4ede0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::needsChecking (unsigned PtrIdx1, unsigned PtrIdx2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; PtrsWrittenOnFwdingPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; CandLoadPtrs)</td>
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

<p>Given two pointers operations by their <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> indices, return true if they require an alias check.</p>


<p>We need a check if one is a pointer for a candidate load and the other is a pointer for a possibly intervening store.</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>.</p>


<p>Referenced by <a href="#abc12092fd1db13a69edf142bcad15556">collectMemchecks</a>.</p>

</div>
</div>

### processLoop() {#a1b795b0cd98521a7cf4ab769d9207258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop ()</td>
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

<p>Top-level driver for each loop: find store-&gt;load forwarding candidates, add run-time checks and perform transformation.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#aeefd30738f7dfce8871907e590774efc">CheckPerElim</a>, <a href="#abc12092fd1db13a69edf142bcad15556">collectMemchecks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#aaf5c3bcafb3f5f0f1a0fd9ddfe9b6e1a">doesStoreDominatesAllLatches</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="#ad870908842303e62050abc131f00f91f">findStoreToLoadDependences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea089e7eb4db258e05f70eef4ed5aa10bb">llvm::IRPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#a7b98d1a31b5292d6b2f4772277c8147f">isLoadConditional</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#a51307482517e908392a567704b219419">LoadElimSCEVCheckThreshold</a>, <a href="#acc9ee85c11fa2173c85a1ba82797d9fb">propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a0600a51b42956b4e041baa101a3c047a">removeDependencesFromMultipleStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa27d4f57d0739004f70aba0719150b57">SEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a65b5f9f4aa48ceb121d65679d8b1a689">llvm::LoopVersioning::versionLoop</a>.</p>

</div>
</div>

### propagateStoredValueToLoadUsers() {#acc9ee85c11fa2173c85a1ba82797d9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; SEE)</td>
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

<p>Perform the transformation for a candidate.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#acdb02479a44bbebcabf8b7b5e1baa921">llvm::CastInst::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a89caf38fb409b0217360689351f3b457">llvm::StoreInst::getValueOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#ac2caa7a270983aba3db7f156957c6adc">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa27d4f57d0739004f70aba0719150b57">SEE</a> and <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af54830aebaed98b40bb2157388e08e36">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Store</a>.</p>


<p>Referenced by <a href="#a1b795b0cd98521a7cf4ab769d9207258">processLoop</a>.</p>

</div>
</div>

### removeDependencesFromMultipleStores() {#a0600a51b42956b4e041baa101a3c047a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::removeDependencesFromMultipleStores (std::forward_list&lt; <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &gt; &amp; Candidates)</td>
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

<p>If a load has multiple candidates associated (i.e.</p>


<p>different stores), it means that it could be forwarding from multiple stores depending on control flow. Remove these candidates.</p>


<p>Here, we rely on LAA to include the relevant loop-independent dependences. LAA is known to omit these in the very simple case when the read and the write within an alias set always takes place using the <em>same</em> pointer.</p>


<p>However, we know that this is not the case here, i.e. we can rely on LAA to provide us with loop-independent dependences for the cases we're interested. Consider the case for example where a loop-independent dependece S1-&gt;S2 invalidates the forwarding S3-&gt;S2.</p>



<pre><code>    A[i]   = ...   (S1)
    ...    = A[i]  (S2)
    A[i+1] = ...   (S3)
</code></pre>


<p>LAA will perform dependence analysis here because there are two <em>different</em> pointers involved in the same alias set (&amp;A[i] and &amp;A[i+1]).</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2b110fde5b0a649629622b90343fb691">getInstrIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#ac2caa7a270983aba3db7f156957c6adc">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Load</a> and <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af54830aebaed98b40bb2157388e08e36">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Store</a>.</p>


<p>Referenced by <a href="#a1b795b0cd98521a7cf4ab769d9207258">processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BFI {#af6d0d7aed09752c7182ac308335c7bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### DT {#af459336fec8de1188bbeda8bfaf046b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### InstOrder {#aad9eb503b7c4a91cd24ce43b7ee25710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, unsigned&gt; anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::InstOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps the load/store instructions to their index according to program order.</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### L {#a420bfe1fdc39f564f1c049de250a642a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### LAI {#a80cb2bc447eb2579bed5cf042a00dab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo&amp; anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::LAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### LI {#a2bd08b1185a6c58784c21c8f48a660d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### PSE {#aa408310b2f936957872bea70809378c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

### PSI {#aa9a060c6f07ba59109849089609c4a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
