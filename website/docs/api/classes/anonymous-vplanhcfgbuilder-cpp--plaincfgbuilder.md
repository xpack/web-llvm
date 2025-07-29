---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PlainCFGBuilder` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a61fdca1746318506e98ae60713cfa1">PlainCFGBuilder</a> (Loop *Lp, LoopInfo *LI, VPlan &amp;P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">buildPlainCFG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build plain CFG for TheLoop and connects it to Plan's entry. <a href="#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9aa6d0f4fb99acb9217c22ab78b2ed">setVPBBPredsFromBB</a> (VPBasicBlock *VPBB, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9da6e1fb030379d02a1b1fa525d9ac">setRegionPredsFromBB</a> (VPRegionBlock *VPBB, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f587b65024bea03385407d24c328704">fixPhiNodes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1080512922d6e09099094b5faa0e58f">getOrCreateVPBB</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6ad03d6282badf4f0d7d8a9e368cb6">isExternalDef</a> (Value *Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c334be83c7b2d733b64c7375880549a">getOrCreateVPOperand</a> (Value *IRVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585756e0750bd87fd01cff887532cdf4">createVPInstructionsForVPBB</a> (VPBasicBlock *VPBB, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9cafa73fe77b4a559691ac72736b25">TheLoop</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c44ea2f0906b79623db3d5c7986affe">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070e2b54ab815b17e14b20c816cafa41">Plan</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32f19ed8d1efb3a238b78394612eafd">VPIRBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3c0b9c92b0198433e03fcc20d0f36e">BB2VPBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6ac41f14b3bf33745a582c4ab79efa">IRDef2VPValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30fb16a67fd6b239ceb821a4c4100e2">PhisToFix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97052c2145cea987644cd9472f1c2f8">Loop2Region</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps loops in the original IR to their corresponding region. <a href="#ab97052c2145cea987644cd9472f1c2f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PlainCFGBuilder() {#a6a61fdca1746318506e98ae60713cfa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::PlainCFGBuilder (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Lp, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; P)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildPlainCFG() {#a43fb01f4c8f7fbffd8a1cec9ed5b04ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlainCFGBuilder::buildPlainCFG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build plain CFG for TheLoop and connects it to Plan's entry.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#abbad647e343d37f18c1bb642fa424c76">llvm::VPBlockBase::clearPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a9e077642586377d67713ebfc26bceef3">llvm::VPBlockBase::clearSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp/#a134da7bb9ba5fab893e3161841f554bf">isHeaderBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp/#a85f42ae734efbd570ae873ab9aa8edc0">isHeaderVPBB</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksrpo/#aeab06fd248333b13725e55754883b570">llvm::LoopBlocksRPO::perform</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae0ad192a841a53fd3a289320e0958e10">llvm::VPBlockBase::setOneSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a6a02d7faad162c3e17d0c522d032320b">llvm::VPBlockBase::setPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa13d3b4d460075f3bb6a6eeb6a5e9bd7">llvm::VPBlockBase::setTwoSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85da2bdebeeed0bf7fdccfdfc5f1b92c">llvm::succ_size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createVPInstructionsForVPBB() {#a585756e0750bd87fd01cff887532cdf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlainCFGBuilder::createVPInstructionsForVPBB (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### fixPhiNodes() {#a0f587b65024bea03385407d24c328704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlainCFGBuilder::fixPhiNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### getOrCreateVPBB() {#aa1080512922d6e09099094b5faa0e58f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * PlainCFGBuilder::getOrCreateVPBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### getOrCreateVPOperand() {#a6c334be83c7b2d733b64c7375880549a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * PlainCFGBuilder::getOrCreateVPOperand (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IRVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### isExternalDef() {#aac6ad03d6282badf4f0d7d8a9e368cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PlainCFGBuilder::isExternalDef (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### setRegionPredsFromBB() {#a1a9da6e1fb030379d02a1b1fa525d9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlainCFGBuilder::setRegionPredsFromBB (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * VPBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### setVPBBPredsFromBB() {#a2d9aa6d0f4fb99acb9217c22ab78b2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PlainCFGBuilder::setVPBBPredsFromBB (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BB2VPBB {#aeb3c0b9c92b0198433e03fcc20d0f36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, VPBasicBlock *&gt; anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::BB2VPBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### IRDef2VPValue {#a3c6ac41f14b3bf33745a582c4ab79efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, VPValue *&gt; anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::IRDef2VPValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### LI {#a7c44ea2f0906b79623db3d5c7986affe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### Loop2Region {#ab97052c2145cea987644cd9472f1c2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Loop *, VPRegionBlock *&gt; anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::Loop2Region</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps loops in the original IR to their corresponding region.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### PhisToFix {#ac30fb16a67fd6b239ceb821a4c4100e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PHINode *, 8&gt; anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::PhisToFix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### Plan {#a070e2b54ab815b17e14b20c816cafa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan&amp; anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::Plan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### TheLoop {#a6f9cafa73fe77b4a559691ac72736b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

### VPIRBuilder {#ac32f19ed8d1efb3a238b78394612eafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBuilder anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::VPIRBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
