---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/removeloadsintofakeuses-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RemoveLoadsIntoFakeUses.cpp` File Reference

<p>The FAKE_USE instruction is used to preserve certain values through optimizations for the sake of debugging. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregunits-h">llvm/CodeGen/LiveRegUnits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/removeloadsintofakeuses">RemoveLoadsIntoFakeUses</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2230515e71bb9ac71cfad28e35f6f0eb">STATISTIC</a> (NumLoadsDeleted, "Number of dead load instructions deleted")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5e1cbb7b0c22f18b814b2adb8cad85">STATISTIC</a> (NumFakeUsesDeleted, "Number of FAKE_USE instructions deleted")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554d5aafa81f51447a0cf25184ccef8e">INITIALIZE_PASS_BEGIN</a> (RemoveLoadsIntoFakeUses, DEBUG_TYPE, "Remove Loads Into Fake Uses", false, false) INITIALIZE_PASS_END(RemoveLoadsIntoFakeUses</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Remove Loads Into Fake</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Remove Loads Into Fake</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe007459002dc8996741cd929b731cea">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"remove-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a5414f76815c8f01cd360c99ff6fb27a7">loads</a>-into-fake-uses"</td>
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

<p>The FAKE_USE instruction is used to preserve certain values through optimizations for the sake of debugging.</p>


<p>This may result in spilled values being loaded into registers that are only used by FAKE_USEs; this is not necessary for debugging purposes, because at that point the value must be on the stack and hence available for debugging. Therefore, this pass removes loads that are only used by FAKE_USEs.</p>


<p>This pass should run very late, to ensure that we don't inadvertently shorten stack lifetimes by removing these loads, since the FAKE_USEs will also no longer be in effect. Running immediately before <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> ensures that LDV will have accurate information of the machine location of debug values.</p>


<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS\_BEGIN() {#a554d5aafa81f51447a0cf25184ccef8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/removeloadsintofakeuses">RemoveLoadsIntoFakeUses</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Remove Loads Into Fake Uses", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

### STATISTIC() {#a2230515e71bb9ac71cfad28e35f6f0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumLoadsDeleted, "Number of dead <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> deleted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aba5e1cbb7b0c22f18b814b2adb8cad85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFakeUsesDeleted, "Number of FAKE_USE <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> deleted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>

</div>
</div>

### false {#afe007459002dc8996741cd929b731cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remove Loads Into Fake false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>

</div>
</div>

### Uses {#a0b427ca665b192edbeb8d6ca3c8f19fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remove Loads Into Fake Uses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a5c54a34ab3372d252d9e9341bdff3dd3">addArgumentAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8e68884ca018dde6dfadf535637290d0">allUsesOfLoadAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a00301689820a26a9f3b438f6dece6ef0">llvm::CombinerHelper::applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2itblockpass-cpp/#a8e9bc607d4404b54c7bc4f650da97008">ClearKillFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a9cca2a73983809b9fca957ca14027bd5">collectAllocaUses</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a67391278875db8d144d4b6bb6e6a09b8">llvm::ReachingDefAnalysis::collectKilledOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae5fdb7e682e1d04dab7282c473a3641b">llvm::PeelingModuloScheduleExpander::CreateLCSSAExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a48595fc4feb49d51ed2eecbf73dadc24">llvm::X86RegisterInfo::findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae9089253a8c971c8429d201735c81ed6">findHoistingInsertPosAndDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab88eabb9aada899a03069797171cd2d5">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::findNonPHIUsesInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a25bb1b65c9a916d968fcc66158103506">findUses</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#acf71d4170b64e15a937f8c8ed61cbd68">anonymous{AttributorAttributes.cpp}::followUsesInContext</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a4acb22dc4402babad62f8b4815129809">anonymous{AttributorAttributes.cpp}::followUsesInMBEC</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#af948ed7c1cd7c55a1e8cb255d8742936">llvm::rdf::Liveness::getAllReachedUses</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a5594932b56f2e0629b440a3c14de9eda">llvm::ReachingDefAnalysis::getGlobalUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8df84affb5990931981f71008a7cd522">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getInstrUses</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#abbea737b469ca04dfced1aa6c87d55c8">llvm::ReachingDefAnalysis::getLiveInUses</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ad474bae3c06f9ecee664f61b236e2ffb">llvm::ReachingDefAnalysis::getReachingLocalUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aef3003e70b3cb1d2dc2659796b546ca2">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a14d72f43eb0c681f84fc9a00c9621941">if</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ac153a9af74f3b0bb72e5f95a7654574e">llvm::ReachingDefAnalysis::isSafeToDefRegAt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ab72dca1e43d1dae61c5f16bd623723fd">parseOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#a73e2e0a493c8182115c57c5901b648f3">propagateLocalCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2869d5459dca008c1c7a1e824e7faf5e">llvm::SelectionDAG::ReplaceAllUsesOfValuesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a2b9c0ec6595f7f4b7d737415a8cb0aaf">llvm::ReplaceableMetadataImpl::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a8adfe0bbfa83dcbab95c4bcea9705e9d">llvm::ReplaceableMetadataImpl::resolveAllUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a26887fb6f8b3127e6b28c2075dacbc11">llvm::ReplaceableMetadataImpl::SalvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a1d6e16608b64f29f9a4d1483507317b5">llvm::coro::BaseCloner::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2itblockpass-cpp/#adc8d1d32a1860d5e21f283b913ac0880">TrackDefUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a05ac0dbbd44f86b9fe34282e8109c1ee">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInThenRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5109075f25d18bf4127922f2ab403dca">UpdateSSA</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"remove-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a5414f76815c8f01cd360c99ff6fb27a7">loads</a>-into-fake-uses"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp">RemoveLoadsIntoFakeUses.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
