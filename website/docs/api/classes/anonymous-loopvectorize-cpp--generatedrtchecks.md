---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GeneratedRTChecks` Class

<p>Helper struct to manage generating runtime checks for vectorization. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopVectorize.cpp}::GeneratedRTChecks { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2139ed08d8dfd3185f12ff7ffb7f0f3e">GeneratedRTChecks</a> (PredicatedScalarEvolution &amp;PSE, DominatorTree *DT, LoopInfo *LI, TargetTransformInfo *TTI, const DataLayout &amp;DL, bool AddBranchWeights, TTI::TargetCostKind CostKind)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b83b5242219a4536c997c7dc2062c4">~GeneratedRTChecks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the created <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; memory runtime check blocks &amp; instructions, if unused. <a href="#a13b83b5242219a4536c997c7dc2062c4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3714d6fe11a1e8c559880caf67fbc7">create</a> (Loop *L, const LoopAccessInfo &amp;LAI, const SCEVPredicate &amp;UnionPred, ElementCount VF, unsigned IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate runtime checks in SCEVCheckBlock and MemCheckBlock, so we can accurately estimate the cost of the runtime checks. <a href="#aae3714d6fe11a1e8c559880caf67fbc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b44d9befce70f070d4355d10ffc419">getCost</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55563b1c40f6c6c94622a87dd7b5dcb">emitSCEVChecks</a> (BasicBlock *Bypass, BasicBlock *LoopVectorPreHeader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the generated SCEVCheckBlock before <span class="doxyComputerOutput">LoopVectorPreHeader</span> and adjusts the branches to branch to the vector preheader or <span class="doxyComputerOutput">Bypass</span>, depending on the generated condition. <a href="#aa55563b1c40f6c6c94622a87dd7b5dcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15e3fefdfa2f5ea86ef5b8eacfa3517">emitMemRuntimeChecks</a> (BasicBlock *Bypass, BasicBlock *LoopVectorPreHeader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the generated MemCheckBlock before <span class="doxyComputerOutput">LoopVectorPreHeader</span> and adjusts the branches to branch to the vector preheader or <span class="doxyComputerOutput">Bypass</span>, depending on the generated condition. <a href="#af15e3fefdfa2f5ea86ef5b8eacfa3517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a4afb2c0e34b915d8efba7837134db">SCEVCheckBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic block which contains the generated <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks, if any. <a href="#ad0a4afb2c0e34b915d8efba7837134db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc24fbbd077821a7da2fada83176ccaa">SCEVCheckCond</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value representing the result of the generated <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks. <a href="#afc24fbbd077821a7da2fada83176ccaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc125b2285f88ca1aa079d55980c2c4a">MemCheckBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic block which contains the generated memory runtime checks, if any. <a href="#acc125b2285f88ca1aa079d55980c2c4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f29b56921c6e8ab37b93d00b731e91f">MemRuntimeCheckCond</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value representing the result of the generated memory runtime checks. <a href="#a0f29b56921c6e8ab37b93d00b731e91f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7d99753d2c05ea180b470fc57787a2">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf86795d89b24e9a90c6401a75d3635d">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f27516a76bae9e7ad363960ce825f2">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58a2350f119b0ad7bad4f20b51541cf">SCEVExp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c33f5654e2562d9f2cb1870b67c3f8">MemCheckExp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a97c26b9be28ef86a8dbbfe19fea9d9">CostTooHigh</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe26d95736fae614e7be4b63b7efe369">AddBranchWeights</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc0bdf9ccb54877589253166c7467e5">OuterLoop</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8d20496939f41454dd08f7a63c9123">PSE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fe7ca74c3887282c0af4045729332d">CostKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of cost that we are calculating. <a href="#af6fe7ca74c3887282c0af4045729332d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct to manage generating runtime checks for vectorization.</p>


<p>The runtime checks are created up-front in temporary blocks to allow better estimating the cost and un-linked from the existing IR. After deciding to vectorize, the checks are moved back. If deciding not to vectorize, the temporary blocks are completely removed.</p>


<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GeneratedRTChecks() {#a2139ed08d8dfd3185f12ff7ffb7f0f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::GeneratedRTChecks (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool AddBranchWeights, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
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



<p>Definition at line 1839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GeneratedRTChecks() {#a13b83b5242219a4536c997c7dc2062c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::~GeneratedRTChecks ()</td>
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

<p>Remove the created <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; memory runtime check blocks &amp; instructions, if unused.</p>

<p>Definition at line 2024 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevexpandercleaner/#ab714e94c2ba068bbd6882e560cef94e2">llvm::SCEVExpanderCleaner::cleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpandercleaner/#adebccfabab3d98cd238936760a34a15d">llvm::SCEVExpanderCleaner::markResultUsed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### create() {#aae3714d6fe11a1e8c559880caf67fbc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp; LAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &amp; UnionPred, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, unsigned IC)</td>
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

<p>Generate runtime checks in SCEVCheckBlock and MemCheckBlock, so we can accurately estimate the cost of the runtime checks.</p>


<p>The blocks are un-linked from the IR and are added back during vector code generation. If there is no vector code generation, the check blocks are removed completely.</p>


<p>Definition at line 1852 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad4f572b4f4bf6aa2dbf10a0bd160280d">llvm::addDiffRuntimeChecks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076304d81553bb834b6d64f72e0fe055">llvm::addRuntimeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a76ffc71fcd432b9a2a15b11c3144397d">llvm::LoopAccessInfo::getNumRuntimePointerChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a3aedf5694dc5b1e81a79658b126a9b43">llvm::LoopAccessInfo::getRuntimePointerChecking</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizerparams/#af0d74538c9c155e8b7899a962e12a68f">llvm::VectorizerParams::HoistRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#ac43f5102232a1e1819b0763536f2937a">llvm::SCEVPredicate::isAlwaysTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a1293f02da7fffb33096a44f1b1768b3f">VectorizeMemoryCheckThreshold</a>.</p>

</div>
</div>

### emitMemRuntimeChecks() {#af15e3fefdfa2f5ea86ef5b8eacfa3517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopVectorPreHeader)</td>
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

<p>Adds the generated MemCheckBlock before <span class="doxyComputerOutput">LoopVectorPreHeader</span> and adjusts the branches to branch to the vector preheader or <span class="doxyComputerOutput">Bypass</span>, depending on the generated condition.</p>

<p>Definition at line 2093 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a502070b20fa467fb54ba49d6736cf2d3">MemCheckBypassWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a657e5d1f0907b46daf10219e2b9b5ae5">llvm::Instruction::replaceSuccessorWith</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>.</p>

</div>
</div>

### emitSCEVChecks() {#aa55563b1c40f6c6c94622a87dd7b5dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitSCEVChecks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopVectorPreHeader)</td>
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

<p>Adds the generated SCEVCheckBlock before <span class="doxyComputerOutput">LoopVectorPreHeader</span> and adjusts the branches to branch to the vector preheader or <span class="doxyComputerOutput">Bypass</span>, depending on the generated condition.</p>

<p>Definition at line 2056 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a968a5c2971ffa9e8ef81ff86eebaf514">SCEVCheckBypassWeights</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>.</p>

</div>
</div>

### getCost() {#ad7b44d9befce70f070d4355d10ffc419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost anonymous{LoopVectorize.cpp}::GeneratedRTChecks::getCost ()</td>
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



<p>Definition at line 1943 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a9b642067999075ba996ecdee40b52b68">llvm::InstructionCost::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddBranchWeights {#abe26d95736fae614e7be4b63b7efe369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{LoopVectorize.cpp}::GeneratedRTChecks::AddBranchWeights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### CostKind {#af6fe7ca74c3887282c0af4045729332d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::TargetCostKind anonymous{LoopVectorize.cpp}::GeneratedRTChecks::CostKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of cost that we are calculating.</p>

<p>Definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### CostTooHigh {#a2a97c26b9be28ef86a8dbbfe19fea9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopVectorize.cpp}::GeneratedRTChecks::CostTooHigh = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1828 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### DT {#a4d7d99753d2c05ea180b470fc57787a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### LI {#abf86795d89b24e9a90c6401a75d3635d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MemCheckBlock {#acc125b2285f88ca1aa079d55980c2c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::MemCheckBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic block which contains the generated memory runtime checks, if any.</p>

<p>Definition at line 1814 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MemCheckExp {#ac0c33f5654e2562d9f2cb1870b67c3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVExpander anonymous{LoopVectorize.cpp}::GeneratedRTChecks::MemCheckExp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MemRuntimeCheckCond {#a0f29b56921c6e8ab37b93d00b731e91f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::MemRuntimeCheckCond = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value representing the result of the generated memory runtime checks.</p>


<p>If it is nullptr, either no memory runtime checks have been generated or they have been used.</p>


<p>Definition at line 1819 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### OuterLoop {#a2bc0bdf9ccb54877589253166c7467e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::OuterLoop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1831 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### PSE {#a3c8d20496939f41454dd08f7a63c9123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; anonymous{LoopVectorize.cpp}::GeneratedRTChecks::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1833 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### SCEVCheckBlock {#ad0a4afb2c0e34b915d8efba7837134db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::SCEVCheckBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic block which contains the generated <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks, if any.</p>

<p>Definition at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### SCEVCheckCond {#afc24fbbd077821a7da2fada83176ccaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::SCEVCheckCond = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value representing the result of the generated <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks.</p>


<p>If it is nullptr, either no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks have been generated or they have been used.</p>


<p>Definition at line 1811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### SCEVExp {#ac58a2350f119b0ad7bad4f20b51541cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVExpander anonymous{LoopVectorize.cpp}::GeneratedRTChecks::SCEVExp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### TTI {#a29f27516a76bae9e7ad363960ce825f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* anonymous{LoopVectorize.cpp}::GeneratedRTChecks::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
