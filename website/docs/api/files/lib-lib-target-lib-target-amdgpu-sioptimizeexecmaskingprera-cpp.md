---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SIOptimizeExecMaskingPreRA.cpp` File Reference

<p>This pass performs exec mask handling peephole optimizations which needs to be done before register allocation to reduce register pressure. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sioptimizeexecmaskingprera-cpp-">anonymous{SIOptimizeExecMaskingPreRA.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera">SIOptimizeExecMaskingPreRA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adf5343de747616c8d71ea58ec06f25">INITIALIZE_PASS_BEGIN</a> (SIOptimizeExecMaskingPreRA, DEBUG_TYPE, "SI optimize exec mask operations pre-RA", false, false) INITIALIZE_PASS_END(SIOptimizeExecMaskingPreRA</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a> (const LiveRange &amp;LR, SlotIndex AndIdx, SlotIndex SelIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a> (const SIRegisterInfo &amp;TRI, LiveIntervals *LIS, Register Reg, const MachineInstr &amp;Sel, const MachineInstr &amp;And)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a10fde6bea2f819ef87db20d8fe3085c7">SI</a> optimize exec mask <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a41f299460d380acb533b0d91dca4d45a">operations</a> pre</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e47bdb3e296b00df96eff7896fa57bf">RA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a10fde6bea2f819ef87db20d8fe3085c7">SI</a> optimize exec mask <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a41f299460d380acb533b0d91dca4d45a">operations</a> pre</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9254bb3f96a2b7d23f1cf3355c7e6f41">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"si-optimize-exec-masking-pre-ra"</td>
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

<p>This pass performs exec mask handling peephole optimizations which needs to be done before register allocation to reduce register pressure.</p>

<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS\_BEGIN() {#a3adf5343de747616c8d71ea58ec06f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (SIOptimizeExecMaskingPreRA, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "SI optimize exec mask <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a41f299460d380acb533b0d91dca4d45a">operations</a> pre-RA", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isDefBetween() {#ab52ab15874c8fda9ecc6bae0bcd42444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDefBetween (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> AndIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> SelIdx)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#af155aeaffc7607f4f27ab4cfcbb39a64">llvm::LiveQueryResult::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a8c9627b7e8bbfa4fbd02f6644907147f">llvm::LiveQueryResult::valueOut</a>.</p>


<p>Referenced by <a href="#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>.</p>

</div>
</div>

### isDefBetween() {#aa0224ce6f8dd63f7674a2a1f032e23ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDefBetween (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Sel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; And)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a7b2ec2588cc48710e468563a0e71d24a">llvm::LiveIntervals::getRegUnit</a>, <a href="#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>

</div>
</div>

### false {#a9254bb3f96a2b7d23f1cf3355c7e6f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI optimize exec mask operations pre false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>

</div>
</div>

### RA {#a3e47bdb3e296b00df96eff7896fa57bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI optimize exec mask operations pre RA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a9dad4dca6c149dcc5a2138f9c3ca50d6">llvm::rdf::PhysicalRegisterInfo::alias</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4c7ab56ddc8e8b9a4f7903e9268c10e9">llvm::rdf::DeadCodeElimination::collect</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#ac020365416d380fdc2b913c0daf4691b">llvm::rdf::Liveness::computeLiveIns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#af94b831a7ac08e60af047cb152eb11c8">createPPCMCRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#a4ca5ad26bd6f05539ea46021582c30ba">createX86MCRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#ac9dc6dd66dabbaf46fe4d72655758f4a">llvm::rdf::DeadCodeElimination::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#ae5482596d863d8c79a9fbbedc54ebd65">llvm::RegAllocEvictionAdvisorAnalysis::getAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a7f4c9b6d8a72709c186c17043f62df58">llvm::RegAllocPriorityAdvisorAnalysis::getAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a3c2cf12c2f59217e967e76435b45a798">llvm::rdf::RefNode::getNextRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">llvm::rdf::DataFlowGraph::getNextRelated</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a4f334bed0e58d5470180436d28993035">llvm::rdf::DataFlowGraph::getNextShadow</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a7010e9f697823cc5a40876345bab137e">llvm::rdf::DataFlowGraph::getRelatedRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#a9b33d70eb77e44e553ac5aa79a3da589">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a773b83ede7cbfdce567311d244b956a4">llvm::MCRegisterInfo::InitMCRegisterInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aebb69ff57b201dee748ce7fe7f22ff1b">llvm::rdf::RegisterAggr::isCoverOf</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#acd6b8a57e9cc0d8ccf8e91a08937bbdf">llvm::MCSubtargetInfo::MCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0c2da232cc1ad3f4633cb297c134e056">llvm::MCSubtargetInfo::MCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adff587a1699cce6d11b70ee64d8a76a0">llvm::MipsRegisterInfo::MipsRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac079965aedb7c7c181c6d74a659c0781">llvm::rdf::printRefHeader</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#af147b385bf71cd50563c0d23b0f9baf7">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::removeOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab9b40d2264d063b8f78959a95e476640">llvm::object::resolveRISCV</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#a2fdc22ba5c1d80ca60c2adcd35b3cd41">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#acafdda56460913cf106b4c9b3a66096d">llvm::SystemZRegisterInfo::SystemZRegisterInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a7850b7517ef8d967cbda198d068f2c0e">llvm::TargetSubtargetInfo::TargetSubtargetInfo</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"si-optimize-exec-masking-pre-ra"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp">SIOptimizeExecMaskingPreRA.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
