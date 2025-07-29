---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-adce-cpp-/aggressivedeadcodeelimination
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AggressiveDeadCodeElimination` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ADCE.cpp}::AggressiveDeadCodeElimination { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad28d9c0a369fc2fe8559186101d6d1ac">AggressiveDeadCodeElimination</a> (Function &amp;F, DominatorTree *DT, PostDominatorTree &amp;PDT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-adce-cpp-/adcechanged">ADCEChanged</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74ecd2f7f8f87c927fd55c6c61b3220">performDeadCodeElimination</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a41d9b63d0976834deb5538f5537c4c">isLive</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c333d5d40a9147ec8a9aa05c6aa4c95">isLive</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5941468ec42052b218c4974f97e5fdb6">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up auxiliary data structures for Instructions and BasicBlocks and initialize the Worklist to the set of must-be-live Instruscions. <a href="#a5941468ec42052b218c4974f97e5fdb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26df3fc15696e4941bd994054c289ad8">isAlwaysLive</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for operations which are always treated as live. <a href="#a26df3fc15696e4941bd994054c289ad8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be8d0ff49ef92e4c052505b3b75064c">isInstrumentsConstant</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for instrumentation instructions for value profiling. <a href="#a0be8d0ff49ef92e4c052505b3b75064c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e3a950a26df5f94b9ecca48b9f2174">markLiveInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate liveness to reaching definitions. <a href="#a80e3a950a26df5f94b9ecca48b9f2174">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34d47344dfbf1b3950aa6aea0fb235a">markLive</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an instruction as live. <a href="#ab34d47344dfbf1b3950aa6aea0fb235a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcad81272a0d40ba40cbf091a067448">markLive</a> (BlockInfoType &amp;BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark a block as live. <a href="#a0dcad81272a0d40ba40cbf091a067448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f11088967b2f8c07de216d6a089d30e">markLive</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a21f864653863b242f23a433682e624">markPhiLive</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark terminators of control predecessors of a PHI node live. <a href="#a4a21f864653863b242f23a433682e624">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f661327cb54fee6c8b36025b30a287">collectLiveScopes</a> (const DILocalScope &amp;LS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the Debug Scopes which surround live debug information. <a href="#a59f661327cb54fee6c8b36025b30a287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3760f3b638b57134f84fb113011d8ceb">collectLiveScopes</a> (const DILocation &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f22a172addfb474d18f8560cc4717a">markLiveBranchesFromControlDependences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze dead branches to find those whose branches are the sources of control dependences impacting a live block. <a href="#ae9f22a172addfb474d18f8560cc4717a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-adce-cpp-/adcechanged">ADCEChanged</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca45a06cca0f481472844b6e9155b78">removeDeadInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove instructions not marked live, return if any instruction was removed. <a href="#adca45a06cca0f481472844b6e9155b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc62f663aeb290bb4f56758cdeb3bb96">updateDeadRegions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify connected sections of the control flow graph which have dead terminators and rewrite the control flow graph to remove them. <a href="#abc62f663aeb290bb4f56758cdeb3bb96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb9b8731e2a8b5414fcf24bcabd31ab">computeReversePostOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the BlockInfo::PostOrder field based on a post-order numbering of the reverse control flow graph. <a href="#a9bb9b8731e2a8b5414fcf24bcabd31ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbc4dbdff877e85da3dd499126113b3">makeUnconditional</a> (BasicBlock *BB, BasicBlock *Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make the terminator of this block an unconditional branch to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span>. <a href="#afcbc4dbdff877e85da3dd499126113b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b384d8164be8ad33678a18aadd50fd1">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0dec26c37f9982314d3bc5dc09b741">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f45928207db640a5de8b26d36fbef05">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/structs/anonymous-adce-cpp-/blockinfotype">BlockInfoType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b205965b07a4b8bd56e855a454d1f33">BlockInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of blocks to associated information, an element in BlockInfoVec. <a href="#a5b205965b07a4b8bd56e855a454d1f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/structs/anonymous-adce-cpp-/instinfotype">InstInfoType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e19f7b5a415afcaf34f31f378ab8e0">InstInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of instructions to associated information. <a href="#ab8e19f7b5a415afcaf34f31f378ab8e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5959f1284692aed513c5c906c5816b73">Worklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions known to be live where we need to mark reaching definitions as live. <a href="#a5959f1284692aed513c5c906c5816b73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15394dbb72b9dbc550d4b984ca32c01f">AliveScopes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug info scopes around a live instruction. <a href="#a15394dbb72b9dbc550d4b984ca32c01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327149282b658c9722e3c2c35df67be0">BlocksWithDeadTerminators</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of blocks with not known to have live terminators. <a href="#a327149282b658c9722e3c2c35df67be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4b96750ab11d7cb9592f0f96ea7d42">NewLiveBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of blocks which we have determined whose control dependence sources must be live and which have not had those dependences analyzed. <a href="#afd4b96750ab11d7cb9592f0f96ea7d42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AggressiveDeadCodeElimination() {#ad28d9c0a369fc2fe8559186101d6d1ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::AggressiveDeadCodeElimination (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### performDeadCodeElimination() {#ad74ecd2f7f8f87c927fd55c6c61b3220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ADCEChanged AggressiveDeadCodeElimination::performDeadCodeElimination ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectLiveScopes() {#a59f661327cb54fee6c8b36025b30a287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::collectLiveScopes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> &amp; LS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the Debug Scopes which surround live debug information.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### collectLiveScopes() {#a3760f3b638b57134f84fb113011d8ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::collectLiveScopes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### computeReversePostOrder() {#a9bb9b8731e2a8b5414fcf24bcabd31ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::computeReversePostOrder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the BlockInfo::PostOrder field based on a post-order numbering of the reverse control flow graph.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### initialize() {#a5941468ec42052b218c4974f97e5fdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up auxiliary data structures for Instructions and BasicBlocks and initialize the Worklist to the set of must-be-live Instruscions.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### isAlwaysLive() {#a26df3fc15696e4941bd994054c289ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveDeadCodeElimination::isAlwaysLive (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true for operations which are always treated as live.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### isInstrumentsConstant() {#a0be8d0ff49ef92e4c052505b3b75064c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveDeadCodeElimination::isInstrumentsConstant (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true for instrumentation instructions for value profiling.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### isLive() {#a9a41d9b63d0976834deb5538f5537c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::isLive (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### isLive() {#a0c333d5d40a9147ec8a9aa05c6aa4c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::isLive (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### makeUnconditional() {#afcbc4dbdff877e85da3dd499126113b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::makeUnconditional (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make the terminator of this block an unconditional branch to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span>.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markLive() {#ab34d47344dfbf1b3950aa6aea0fb235a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::markLive (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark an instruction as live.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markLive() {#a0dcad81272a0d40ba40cbf091a067448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::markLive (<a href="/web-llvm/docs/api/structs/anonymous-adce-cpp-/blockinfotype">BlockInfoType</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark a block as live.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markLive() {#a4f11088967b2f8c07de216d6a089d30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::markLive (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markLiveBranchesFromControlDependences() {#ae9f22a172addfb474d18f8560cc4717a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::markLiveBranchesFromControlDependences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze dead branches to find those whose branches are the sources of control dependences impacting a live block.</p>


<p>Those branches are marked live.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markLiveInstructions() {#a80e3a950a26df5f94b9ecca48b9f2174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::markLiveInstructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Propagate liveness to reaching definitions.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### markPhiLive() {#a4a21f864653863b242f23a433682e624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveDeadCodeElimination::markPhiLive (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark terminators of control predecessors of a PHI node live.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### removeDeadInstructions() {#adca45a06cca0f481472844b6e9155b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ADCEChanged AggressiveDeadCodeElimination::removeDeadInstructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove instructions not marked live, return if any instruction was removed.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### updateDeadRegions() {#abc62f663aeb290bb4f56758cdeb3bb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveDeadCodeElimination::updateDeadRegions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify connected sections of the control flow graph which have dead terminators and rewrite the control flow graph to remove them.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliveScopes {#a15394dbb72b9dbc550d4b984ca32c01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Metadata *, 32&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::AliveScopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug info scopes around a live instruction.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### BlockInfo {#a5b205965b07a4b8bd56e855a454d1f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;BasicBlock *, BlockInfoType&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::BlockInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of blocks to associated information, an element in BlockInfoVec.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> to get deterministic iteration order.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### BlocksWithDeadTerminators {#a327149282b658c9722e3c2c35df67be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;BasicBlock *, 16&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::BlocksWithDeadTerminators</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of blocks with not known to have live terminators.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### DT {#a8b0dec26c37f9982314d3bc5dc09b741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### F {#a7b384d8164be8ad33678a18aadd50fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### InstInfo {#ab8e19f7b5a415afcaf34f31f378ab8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, InstInfoType&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::InstInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of instructions to associated information.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### NewLiveBlocks {#afd4b96750ab11d7cb9592f0f96ea7d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 16&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::NewLiveBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of blocks which we have determined whose control dependence sources must be live and which have not had those dependences analyzed.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### PDT {#a1f45928207db640a5de8b26d36fbef05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree&amp; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### Worklist {#a5959f1284692aed513c5c906c5816b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 128&gt; anonymous{ADCE.cpp}::AggressiveDeadCodeElimination::Worklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions known to be live where we need to mark reaching definitions as live.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
