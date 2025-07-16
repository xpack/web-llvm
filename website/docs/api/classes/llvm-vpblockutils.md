---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpblockutils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPBlockUtils` Class Reference

<p>Class that provides utilities for VPBlockBases in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPBlockUtils { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">Transforms/Vectorize/VPlanUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81c27f63ab4ba0164e96dbe8dd91b681">VPBlockUtils</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f625b90be26a131061ab1e43740cc81">insertBlockAfter</a> (VPBlockBase *NewBlock, VPBlockBase *BlockPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert disconnected <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> <span class="doxyComputerOutput">NewBlock</span> after <span class="doxyComputerOutput">BlockPtr</span>. <a href="#a1f625b90be26a131061ab1e43740cc81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d51be488551c2983a022bb98494901">insertBlockBefore</a> (VPBlockBase *NewBlock, VPBlockBase *BlockPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert disconnected block <span class="doxyComputerOutput">NewBlock</span> before <span class="doxyComputerOutput">Blockptr</span>. <a href="#a69d51be488551c2983a022bb98494901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a43b6445802190031bda62347e97453">insertTwoBlocksAfter</a> (VPBlockBase *IfTrue, VPBlockBase *IfFalse, VPBlockBase *BlockPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert disconnected VPBlockBases <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> after <span class="doxyComputerOutput">BlockPtr</span>. <a href="#a3a43b6445802190031bda62347e97453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bc7fec35d7093efcdbadf566d6b5ee">connectBlocks</a> (VPBlockBase *From, VPBlockBase *To, unsigned PredIdx=-1u, unsigned SuccIdx=-1u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Connect VPBlockBases <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span> bi-directionally. <a href="#a40bc7fec35d7093efcdbadf566d6b5ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f1451694a3638db85170c7f55d5581">disconnectBlocks</a> (VPBlockBase *From, VPBlockBase *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disconnect VPBlockBases <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span> bi-directionally. <a href="#a61f1451694a3638db85170c7f55d5581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63345282cd67ea46202fb33523be1408">reassociateBlocks</a> (VPBlockBase *Old, VPBlockBase *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociate all the blocks connected to <span class="doxyComputerOutput">Old</span> so that they now point to <span class="doxyComputerOutput">New</span>. <a href="#a63345282cd67ea46202fb33523be1408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BlockTy, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0360eea6cebcb1470f84b11f7ba51f16">blocksOnly</a> (const T &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over <span class="doxyComputerOutput">Range</span> which only includes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a0134180716271c522b7b0e1537ce7d9b">BlockTy</a></span> blocks. <a href="#a0360eea6cebcb1470f84b11f7ba51f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2057d0749eedf6749f9e1cc6694eb1fd">insertOnEdge</a> (VPBlockBase *From, VPBlockBase *To, VPBlockBase *BlockPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts <span class="doxyComputerOutput">BlockPtr</span> on the edge between <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>. <a href="#a2057d0749eedf6749f9e1cc6694eb1fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class that provides utilities for VPBlockBases in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPBlockUtils() {#a81c27f63ab4ba0164e96dbe8dd91b681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBlockUtils::VPBlockUtils ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### blocksOnly() {#a0360eea6cebcb1470f84b11f7ba51f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BlockTy, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::VPBlockUtils::blocksOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Range)</td>
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

<p>Return an iterator range over <span class="doxyComputerOutput">Range</span> which only includes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a0134180716271c522b7b0e1537ce7d9b">BlockTy</a></span> blocks.</p>


<p>The accesses are casted to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a0134180716271c522b7b0e1537ce7d9b">BlockTy</a></span>.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaee5189b9c4db9ad666a88abaf1ee0c4ad7778d0c64b6ba21494c97f77a66885a">llvm::Filter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a63e564d621011fac5978d18138121e5c">llvm::VPlanTransforms::convertToConcreteRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#accb5ce221150790c36b2d96af1be821c">llvm::InnerLoopVectorizer::fixNonInductionPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a85800ca7a821f540ad2d6d4d3c2d4208">llvm::VPlan::getExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#afd081c92500bd333555e7bd6102b4d3e">licm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#aaa122781f91b3e8bc730b2c5b7c07a05">remapOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aaca9dd97d4c523d8c65274654abe4eb9">llvm::VPlanTransforms::removeDeadRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### connectBlocks() {#a40bc7fec35d7093efcdbadf566d6b5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::connectBlocks (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * From, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * To, unsigned PredIdx=-1u, unsigned SuccIdx=-1u)</td>
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

<p>Connect VPBlockBases <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span> bi-directionally.</p>


<p>If <span class="doxyComputerOutput">PredIdx</span> is -1, append <span class="doxyComputerOutput">From</span> to the predecessors of <span class="doxyComputerOutput">To</span>, otherwise set <span class="doxyComputerOutput">To's</span> predecessor at <span class="doxyComputerOutput">PredIdx</span> to <span class="doxyComputerOutput">From</span>. If <span class="doxyComputerOutput">SuccIdx</span> is -1, append <span class="doxyComputerOutput">To</span> to the successors of <span class="doxyComputerOutput">From</span>, otherwise set <span class="doxyComputerOutput">From's</span> successor at <span class="doxyComputerOutput">SuccIdx</span> to <span class="doxyComputerOutput">To</span>. Both VPBlockBases must have the same parent, which can be null. Both VPBlockBases can be already connected to other VPBlockBases.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2c13ffed8c55e1b8dd38fedc7e71e7a8">llvm::VPBlockBase::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="#a1f625b90be26a131061ab1e43740cc81">insertBlockAfter</a>, <a href="#a69d51be488551c2983a022bb98494901">insertBlockBefore</a>, <a href="#a2057d0749eedf6749f9e1cc6694eb1fd">insertOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### disconnectBlocks() {#a61f1451694a3638db85170c7f55d5581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::disconnectBlocks (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * From, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * To)</td>
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

<p>Disconnect VPBlockBases <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span> bi-directionally.</p>


<p>Remove <span class="doxyComputerOutput">To</span> from the successors of <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">From</span> from the predecessors of <span class="doxyComputerOutput">To</span>.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a1f625b90be26a131061ab1e43740cc81">insertBlockAfter</a>, <a href="#a69d51be488551c2983a022bb98494901">insertBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### insertBlockAfter() {#a1f625b90be26a131061ab1e43740cc81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::insertBlockAfter (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * NewBlock, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * BlockPtr)</td>
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

<p>Insert disconnected <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> <span class="doxyComputerOutput">NewBlock</span> after <span class="doxyComputerOutput">BlockPtr</span>.</p>


<p>Add <span class="doxyComputerOutput">NewBlock</span> as successor of <span class="doxyComputerOutput">BlockPtr</span> and <span class="doxyComputerOutput">BlockPtr</span> as predecessor of <span class="doxyComputerOutput">NewBlock</span>, and propagate <span class="doxyComputerOutput">BlockPtr</span> parent to <span class="doxyComputerOutput">NewBlock</span>. <span class="doxyComputerOutput">BlockPtr's</span> successors are moved from <span class="doxyComputerOutput">BlockPtr</span> to <span class="doxyComputerOutput">NewBlock</span>. <span class="doxyComputerOutput">NewBlock</span> must have neither successors nor predecessors.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a40bc7fec35d7093efcdbadf566d6b5ee">connectBlocks</a>, <a href="#a61f1451694a3638db85170c7f55d5581">disconnectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae2be49bdbbda0aeadd51549f4b88c839">llvm::VPBlockBase::setParent</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a37b8fb6b951d671365edaae4b68a2666">llvm::VPBlockBase::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a9b75fcd70de89596b8f04904aa42e2cd">llvm::VPBasicBlock::splitAt</a>.</p>

</div>
</div>

### insertBlockBefore() {#a69d51be488551c2983a022bb98494901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::insertBlockBefore (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * NewBlock, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * BlockPtr)</td>
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

<p>Insert disconnected block <span class="doxyComputerOutput">NewBlock</span> before <span class="doxyComputerOutput">Blockptr</span>.</p>


<p>First disconnects all predecessors of <span class="doxyComputerOutput">BlockPtr</span> and connects them to <span class="doxyComputerOutput">NewBlock</span>. Add <span class="doxyComputerOutput">NewBlock</span> as predecessor of <span class="doxyComputerOutput">BlockPtr</span> and <span class="doxyComputerOutput">BlockPtr</span> as successor of <span class="doxyComputerOutput">NewBlock</span>.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a40bc7fec35d7093efcdbadf566d6b5ee">connectBlocks</a>, <a href="#a61f1451694a3638db85170c7f55d5581">disconnectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2526abff3e6d88edde3f67cc61842e74">llvm::VPBlockBase::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae2be49bdbbda0aeadd51549f4b88c839">llvm::VPBlockBase::setParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a>.</p>

</div>
</div>

### insertOnEdge() {#a2057d0749eedf6749f9e1cc6694eb1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::insertOnEdge (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * From, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * To, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * BlockPtr)</td>
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

<p>Inserts <span class="doxyComputerOutput">BlockPtr</span> on the edge between <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>.</p>


<p>That is, update <span class="doxyComputerOutput">From's</span> successor to <span class="doxyComputerOutput">To</span> to point to <span class="doxyComputerOutput">BlockPtr</span> and <span class="doxyComputerOutput">To's</span> predecessor from <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">BlockPtr</span>. <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span> are added to <span class="doxyComputerOutput">BlockPtr's</span> predecessors and successors respectively. There must be a single edge between <span class="doxyComputerOutput">From</span> and <span class="doxyComputerOutput">To</span>.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a40bc7fec35d7093efcdbadf566d6b5ee">connectBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>.</p>

</div>
</div>

### insertTwoBlocksAfter() {#a3a43b6445802190031bda62347e97453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::insertTwoBlocksAfter (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * IfTrue, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * IfFalse, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * BlockPtr)</td>
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

<p>Insert disconnected VPBlockBases <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> after <span class="doxyComputerOutput">BlockPtr</span>.</p>


<p>Add <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> as succesors of <span class="doxyComputerOutput">BlockPtr</span> and <span class="doxyComputerOutput">BlockPtr</span> as predecessor of <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span>. Propagate <span class="doxyComputerOutput">BlockPtr</span> parent to <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span>. <span class="doxyComputerOutput">BlockPtr</span> must have no successors and <span class="doxyComputerOutput">IfTrue</span> and <span class="doxyComputerOutput">IfFalse</span> must have neither successors nor predecessors.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae2be49bdbbda0aeadd51549f4b88c839">llvm::VPBlockBase::setParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a6a02d7faad162c3e17d0c522d032320b">llvm::VPBlockBase::setPredecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa13d3b4d460075f3bb6a6eeb6a5e9bd7">llvm::VPBlockBase::setTwoSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>.</p>

</div>
</div>

### reassociateBlocks() {#a63345282cd67ea46202fb33523be1408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockUtils::reassociateBlocks (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * New)</td>
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

<p>Reassociate all the blocks connected to <span class="doxyComputerOutput">Old</span> so that they now point to <span class="doxyComputerOutput">New</span>.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#abbad647e343d37f18c1bb642fa424c76">llvm::VPBlockBase::clearPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a9e077642586377d67713ebfc26bceef3">llvm::VPBlockBase::clearSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
