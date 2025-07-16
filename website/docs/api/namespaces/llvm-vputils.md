---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/vputils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `vputils` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::vputils { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3c306be8d629a994f3644765421d5f">onlyFirstLaneUsed</a> (const VPValue *Def)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if only the first lane of <span class="doxyComputerOutput">Def</span> is used. <a href="#a5e3c306be8d629a994f3644765421d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513233e0bcf9aaf36f9672eff75514ea">onlyFirstPartUsed</a> (const VPValue *Def)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if only the first part of <span class="doxyComputerOutput">Def</span> is used. <a href="#a513233e0bcf9aaf36f9672eff75514ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064976a6c7458b10c24021b7334cec2a">getOrCreateVPValueForSCEVExpr</a> (VPlan &amp;Plan, const SCEV *Expr, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> that corresponds to the expansion of <span class="doxyComputerOutput">Expr</span>. <a href="#a064976a6c7458b10c24021b7334cec2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5999b0390c92ee4af2544fe9772454bf">getSCEVExprForVPValue</a> (VPValue *V, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for <span class="doxyComputerOutput">V</span>. <a href="#a5999b0390c92ee4af2544fe9772454bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a002a77cdbc23293b8f7a8458ffd0f905">isUniformAfterVectorization</a> (const VPValue *VPV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">VPV</span> is uniform after vectorization. <a href="#a002a77cdbc23293b8f7a8458ffd0f905">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c706ef30193e00ac057bf24cf5719d">isHeaderMask</a> (const VPValue *V, VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">V</span> is a header mask in <span class="doxyComputerOutput">Plan</span>. <a href="#a96c706ef30193e00ac057bf24cf5719d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c663bf15e8398176f591270e7676f96">isUniformAcrossVFsAndUFs</a> (VPValue *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <span class="doxyComputerOutput">V</span> is uniform across all VF lanes and UF parts. <a href="#a0c663bf15e8398176f591270e7676f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getOrCreateVPValueForSCEVExpr() {#a064976a6c7458b10c24021b7334cec2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::vputils::getOrCreateVPValueForSCEVExpr (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> that corresponds to the expansion of <span class="doxyComputerOutput">Expr</span>.</p>


<p>If <span class="doxyComputerOutput">Expr</span> is a <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> or <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a>, return a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> wrapping the live-in value. Otherwise return a <a href="/web-llvm/docs/api/classes/llvm/vpexpandscevrecipe">VPExpandSCEVRecipe</a> to expand <span class="doxyComputerOutput">Expr</span>. If <span class="doxyComputerOutput">Plan's</span> pre-header already contains a recipe expanding <span class="doxyComputerOutput">Expr</span>, return it. If not, create a new one.</p>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vplan/#a65719da7ecac78c4b751d3dbb9f9f2a4">llvm::VPlan::addSCEVExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a23773e962f9a56c9bdf13f7668b063a5">llvm::VPBasicBlock::appendRecipe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aea17e1d416f9187542a9f87745c48e0a">llvm::VPlan::getSCEVExpansion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### getSCEVExprForVPValue() {#a5999b0390c92ee4af2544fe9772454bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::vputils::getSCEVExprForVPValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for <span class="doxyComputerOutput">V</span>.</p>


<p>Returns <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> if no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression could be constructed.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/typeswitch/#a78c545287cbe57529ce7751e25c815a5">llvm::TypeSwitch&lt; T, ResultT &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aaa9b9055fd9c69fe14eb20f0d18d53d5">llvm::ScalarEvolution::getCouldNotCompute</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>.</p>

</div>
</div>

### isHeaderMask() {#a96c706ef30193e00ac057bf24cf5719d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vputils::isHeaderMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">V</span> is a header mask in <span class="doxyComputerOutput">Plan</span>.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a3732ef393569af17c44c36f4e22f2854">llvm::VPlan::getOrCreateBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>.</p>

</div>
</div>

### isUniformAcrossVFsAndUFs() {#a0c663bf15e8398176f591270e7676f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vputils::isUniformAcrossVFsAndUFs (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if <span class="doxyComputerOutput">V</span> is uniform across all VF lanes and UF parts.</p>


<p>It is considered as such if it is either loop invariant (defined outside the vector region) or its operand is known to be uniform across all VFs and UFs (e.g. VPDerivedIV or VPCanonicalIVPHI).</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/typeswitch/#a78c545287cbe57529ce7751e25c815a5">llvm::TypeSwitch&lt; T, ResultT &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a0c663bf15e8398176f591270e7676f96">isUniformAcrossVFsAndUFs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a0c663bf15e8398176f591270e7676f96">isUniformAcrossVFsAndUFs</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#a9965cb8e010ad82f02434a0762cddf1e">anonymous{VPlanUnroll.cpp}::UnrollState::unrollBlock</a>.</p>

</div>
</div>

### isUniformAfterVectorization() {#a002a77cdbc23293b8f7a8458ffd0f905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vputils::isUniformAfterVectorization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * VPV)</td>
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

<p>Returns true if <span class="doxyComputerOutput">VPV</span> is uniform after vectorization.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a26ee9845ed3014dd45095ff2493b51b6">llvm::VPValue::isDefinedOutsideLoopRegions</a>, <a href="#a002a77cdbc23293b8f7a8458ffd0f905">isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a055004cd2c472e5a3de6eb59c5f8d9f5">llvm::VPInstruction::PtrAdd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a2ed5b7b284097278ee4e550897b1f057">llvm::VPReplicateRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a48955fd76dc29a6b4391aef55ce3efd3">llvm::VPTransformState::get</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac239a91075321de19449d54f092ab82a">llvm::VPTransformState::get</a>, <a href="#a002a77cdbc23293b8f7a8458ffd0f905">isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a5e3c306be8d629a994f3644765421d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vputils::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if only the first lane of <span class="doxyComputerOutput">Def</span> is used.</p>

<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a0cf81ee784fd5dea0b9353a51f4f4fee">llvm::VPBlendRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a004ecf8ed4165883d4dfa06716dd72c9">llvm::VPInstruction::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#af1d96b296e589e5d8318e526b5d2ff92">llvm::VPBlendRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a48955fd76dc29a6b4391aef55ce3efd3">llvm::VPTransformState::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#accc830d2b6d4d03922cf5e6a238ae9c1">llvm::VPInstruction::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#a45ddca551682b104bc3cd4a3906507d3">llvm::VPWidenPointerInductionRecipe::onlyScalarsGenerated</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>.</p>

</div>
</div>

### onlyFirstPartUsed() {#a513233e0bcf9aaf36f9672eff75514ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vputils::onlyFirstPartUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if only the first part of <span class="doxyComputerOutput">Def</span> is used.</p>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aa0b84f190dbf600165d9b79f4cf51d6c">llvm::VPInstruction::onlyFirstPartUsed</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-cpp">VPlanUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
