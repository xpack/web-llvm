---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPUDelayedMCExpr.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-h">AMDGPUDelayedMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a> (msgpack::DocNode DN, msgpack::Type Type, MCValue Val)</td>
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

### getNode() {#a3b9e43a5529fa7d4adb2bad70198c9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode getNode (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> DN, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">msgpack::Type</a> Type, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Val)</td>
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



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp">AMDGPUDelayedMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a58d0878f182d83be836a4081448a16b1">llvm::msgpack::Document::getEmptyNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#a463e5963bd9b6fdcbb33e4fd003d2863">llvm::DelayedMCExprs::assignDocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a205e1f9d2dc81b91902dce526a77c5c7">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::calculateCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac05ba7b36777c445fb76f15011abf487">llvm::PPCTargetLowering::CollectTargetIntrinsicOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a8018dafd83274830a0be46656f73d2f7">anonymous{DAGCombiner.cpp}::DAGCombiner::CombineTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a3d6a0c2358ffb53de76d93e49e66ee2d">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a2dea266109363b32fed08d85efa46523">llvm::msgpack::MapDocNode::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a1a14301103c8d97e52ed0ca117ea6b65">llvm::PPC::get_VSPLTI_elt</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl/#ae87d24146ddae3b92a07246e2a63aa8b">llvm::BlockFrequencyInfoImpl&lt; BasicBlock &gt;::getBlockFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl/#a31905a32a4b7c89a7485afdf59c134bc">llvm::BlockFrequencyInfoImpl&lt; BasicBlock &gt;::getBlockProfileCount</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff/#aa88d3fb317c2360c096818fe691c2cf2">anonymous{StandardInstrumentations.cpp}::DotCfgDiff::getEdgeSourceLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#a9e60d1094e1e14e5404509f6df580a79">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::getFieldType</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl/#a756b682b6d9fd9641480076412b99885">llvm::BlockFrequencyInfoImpl&lt; BasicBlock &gt;::getFloatingBlockFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a46743167f5c496ace9d15f3504584735">llvm::LazyCallGraph::Edge::getFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#a2f835547f118580b4ed9aca9cfed9b8e">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::getNumFields</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl/#a058de37a3c739f4c59a0f238f0741766">llvm::BlockFrequencyInfoImpl&lt; BasicBlock &gt;::isIrrLoopHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a308a98eacddb4eaa55f1ab3723416253">isShuffleFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#ac68db929c1a5815b6be1c0a5e47e562b">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ada7b65032d37287aa8fff70763d86b51">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::properlyDominates</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/regdefiter/#a6e7a3b904f789436ffa4c1d046e03f60">llvm::ScheduleDAGSDNodes::RegDefIter::RegDefIter</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a75d2b594fff24fcfffe9a72415deddb4">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a67ef64ef7639ff3e2f43230a0623d33c">llvm::SelectionDAGISel::ReplaceUses</a>, <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#afde1d15893de3e2295907d9d88911f08">llvm::DelayedMCExprs::resolveDelayedExpressions</a>, <a href="/web-llvm/docs/api/classes/llvm/sdloc/#a535048fa70ac1c49d6a6d8a23e92f25a">llvm::SDLoc::SDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae4d7d58593a9d0b5337f8089ee1946f6">llvm::HvxSelector::selectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl/#ab92a33fa61ab3c963e850d2ff5b59063">llvm::BlockFrequencyInfoImpl&lt; BT &gt;::setBlockFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#a52e0a0634f9ecde5ce054d6d6bcd2761">willShiftRightEliminate</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
