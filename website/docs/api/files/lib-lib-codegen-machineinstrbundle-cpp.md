---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machineinstrbundle-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachineInstrBundle.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">llvm/CodeGen/MachineInstrBundle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machineinstrbundle-cpp-">anonymous{MachineInstrBundle.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineinstrbundle-cpp-/unpackmachinebundles">UnpackMachineBundles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machineinstrbundle-cpp-/finalizemachinebundles">FinalizeMachineBundles</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b6fd964a2982b1b74e4cc2ed6ad8fc">INITIALIZE_PASS</a> (UnpackMachineBundles, "unpack-mi-bundles", "Unpack machine instruction bundles", false, false) bool UnpackMachineBundles</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef27d4ded483240d1aacd7775643cf0">INITIALIZE_PASS</a> (FinalizeMachineBundles, "finalize-mi-bundles", "Finalize machine instruction bundles", false, false) bool FinalizeMachineBundles</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a> (MachineBasicBlock::instr_iterator FirstMI, MachineBasicBlock::instr_iterator LastMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first found <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> that has a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a>, given a range of instructions. <a href="#af44c9b089359803924e0b92bea3b6d03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getDebugLoc() {#af44c9b089359803924e0b92bea3b6d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc getDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> FirstMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> LastMI)</td>
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

<p>Return the first found <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> that has a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a>, given a range of instructions.</p>


<p>The search range is from FirstMI to LastMI (exclusive). If no <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> is found, then an empty location is returned.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp">MachineInstrBundle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a7be7b32d7295ca1bb026c4fb014f0035">llvm::DebugVariable::DebugVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#afbd789ec48caaf1993886b8d5360395f">llvm::DebugVariable::DebugVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariableaggregate/#a8187a78c2aefa6b2f948d02fa8cc9460">llvm::DebugVariableAggregate::DebugVariableAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect/#abdd6bad61c38d00ca2dceda536cd15f9">llvm::DiagnosticInfoMisExpect::DiagnosticInfoMisExpect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a6907f6a41468c8a1f73099a44238ab21">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::HexagonPipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ab72f6c46cf154205814197e0e93b69f7">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a8500015965ef1b86e39cd83fd2fc8dff">llvm::InlineAdvice::InlineAdvice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/arminstructionselector/insertinfo/#ad7539b5e1d3afd907c8656e3e6624343">ARMInstructionSelector::InsertInfo::InsertInfo</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2f2db17683a598ccfcfe8b0ad33f3040">LLVMInstructionGetDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad47eb141a735c9c43d062fe6f931b31b">llvm::AMDGPUTargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a9b7674e7758bfe4a7b4f66ab59c89611">llvm::NVPTXTargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a23badf68951303c8ef0664e24f181100">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/mimetadata/#aa60c5c9d0960e5c16505d14524822ad1">llvm::MIMetadata::MIMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mimetadata/#aaa4b2a471812bfba5b2cbf9a38821ff5">llvm::MIMetadata::MIMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a2ad3eae0e100b9e6eca74ee28144ba1d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a7d0a9378ede1f0821eb273c8e797df06">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a23879092a3f056766816230baa431981">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a4a1143f3929f3258aebb54b4bef12082">llvm::SGPRSpillBuilder::SGPRSpillBuilder</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a34b6fd964a2982b1b74e4cc2ed6ad8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (UnpackMachineBundles, "unpack-mi-bundles", "Unpack machine instruction bundles", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp">MachineInstrBundle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#afef27d4ded483240d1aacd7775643cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (FinalizeMachineBundles, "finalize-mi-bundles", "Finalize machine instruction bundles", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp">MachineInstrBundle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a249400a134382b43c3af83ff731979f9">llvm::finalizeBundles</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
