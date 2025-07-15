---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/regallocevictionadvisor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RegAllocEvictionAdvisor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/allocationorder-h">AllocationOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerclassinfo-h">llvm/CodeGen/RegisterClassInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b33d70eb77e44e553ac5aa79a3da589">INITIALIZE_PASS</a> (RegAllocEvictionAdvisorAnalysis, "regalloc-evict", "Regalloc eviction policy", false, true) namespace</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#a02472e81dfeca389aba455abdef60a09">RegAllocEvictionAdvisorAnalysis::AdvisorMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef71c4b21823f236e70cc6d62375adcd">Mode</a>("regalloc-enable-advisor", cl::Hidden, cl::init(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Default), cl::desc("Enable regalloc advisor mode"), cl::values(clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Default, "default", "Default"), clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Release, "release", "precompiled"), clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Development, "development", "for training")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f42a1d485da3b65571ba06322d8c3d">EnableLocalReassignment</a>("enable-local-reassign", cl::Hidden, cl::desc("Local reassignment can yield better allocation decisions, but " "may be compile time intensive"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"regalloc"</td>
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

### INITIALIZE\_PASS() {#a9b33d70eb77e44e553ac5aa79a3da589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis">RegAllocEvictionAdvisorAnalysis</a>, "regalloc-evict", "Regalloc eviction policy", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#ab007d6c51634eb65e4f4f9dab4eb6a8c">llvm::Pass::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#ae5482596d863d8c79a9fbbedc54ebd65">llvm::RegAllocEvictionAdvisorAnalysis::getAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#a569f300915b37b41ea6be1f09ec7c0af">llvm::RegAllocEvictionAdvisorAnalysis::RegAllocEvictionAdvisorAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableLocalReassignment {#ae0f42a1d485da3b65571ba06322d8c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLocalReassignment("enable-local-reassign", cl::Hidden, cl::desc("Local reassignment can yield better allocation decisions, but " "may be compile time intensive"), cl::init(false))</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a15d0d898ba65160068451253f5cd0a11">llvm::RegAllocEvictionAdvisor::RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### Mode {#aef71c4b21823f236e70cc6d62375adcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RegAllocEvictionAdvisorAnalysis::AdvisorMode &gt; Mode("regalloc-enable-advisor", cl::Hidden, cl::init(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Default), cl::desc("Enable regalloc advisor mode"), cl::values( clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Default, "default", "Default"), clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Release, "release", "precompiled"), clEnumValN(RegAllocEvictionAdvisorAnalysis::AdvisorMode::Development, "development", "for training")))</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a592297dd80c13e993380e2bf972721ac">llvm::sys::fs::access</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a66d4f6a60a7224a7e828e9c2cfc549d6">applyDebugify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#adbd6553c180df1ec067adf91c8cbc0da">applyDebugify</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a204614db7296af6e2492c48c3a8ffd03">ARM64EmitUnwindCode</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a070a51abfeee0b0cab556479590ab7c6">llvm::AAResults::canInstructionRangeModRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63b3ac6067f94151d39d197391477436">canReduceVMulWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#ac80bee275658d4cea6785d8b997308ef">createCheckDebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a8d798f3ea7f1752372e198b55679d68b">createCheckDebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#adbed89a81d48a6b50e870dd57c48a53b">createDebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a852b17c1bcf77c05da7b100159512462">createDebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#ab567e593dcf755d782527311e9b300fa">createInMemoryBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp/#a29c8f00b8e38e6ff83c39923934de954">createUniqueEntity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4cc99e81f7cfa524bf4bba0f0cc3362">llvm::denormalModeKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3e8b7d7b4d4abd86ab48a0f51f8a6c80">ExpandHorizontalBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#a2a2cd943c672fd604c2837f01a7db49f">flushDenormalConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#aacbd97f1443d5a400a39b1899b363812">flushDenormalConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a093153573aa0758fa34bf50a930fb27f">foldFabsWithFcmpZero</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a19dce49c9c18898b9f4ca348fa3c89ec">llvm::GCNTTIImpl::GCNTTIImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#ae0e4646b896b1964b2964a1c10d01650">llvm::ARM_AM::getAM4SubMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3821ce1ee2c302ab18b25205a06ca327">llvm::ARM_AM::getAMSubModeStr</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a785285b13b67a380426876b52ae4d811">llvm::SIModeRegisterDefaults::getDefaultForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a83bfc4b182ec83019d681c1555c3c33c">getFPMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a3761b2e0f118a382aeb4c9dc8ffa4838">getLoadStoreMultipleOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1bdd94719d38df63af695f07092750ca">getPostIndexedLoadStoreOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a71b3987a20a22fe47772c3c670dce48a">getPreIndexedLoadStoreOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab026557e78590060ce851bf04f1f37c8">getSPDenormModeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a89e60908750fd1cca69d96e7aa41ba5b">llvm::TargetLowering::getSqrtInputTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ad4d87d5c3928215d18c662c8519af439">getUpdatingLSMultipleOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa9faa711a4588962345896fd7e672e78">getVectorComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a43c0c57ea81b6bb34fdaab6528e09b23">getVectorComparisonOrInvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp/#a0eee13989797c0d4612066f84ff7a7b8">INITIALIZE_PASS_END</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad4ffc03696c5fb25276e989e15970960">inputDenormalIsIEEEOrPosZero</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#a651bb66b388bdec1e6b008e4b67ac54b">llvm::TargetTransformInfo::Concept::isIndexedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a81b1d5bcab6aefdff27cab2e4e9241a5">llvm::TargetTransformInfoImplBase::isIndexedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#afcc4fc68b799cb2c385c2152adbd755f">llvm::TargetTransformInfo::Concept::isIndexedStoreLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#aa067e93305b9e8997fa274bc369966ec">llvm::TargetTransformInfoImplBase::isIndexedStoreLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a4ff4587317327e576c1edb8aa61234fc">isMemberPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a4585a4281eeceb0ebb18437056cdfc85">llvm::RISCVFPRndMode::isValidRoundingMode</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa025b4042992fcb4ee0a8495cebb32ba">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#gae6639bf7d67999ecdf8a81cf44e9c22e">LLVMSetTargetMachineGlobalISelAbort</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga1862f0ecae626310ed6b8d8401cfd48b">LLVMSetThreadLocalMode</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04af5a7e9a7e6429c317f65059acd5d/#a5375c5d577f84cf80808edad654056f9">llvm::yaml::MappingTraits&lt; SIMode &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericdylibmanager/#aa8ff17813ed881db4af1f6ef52300519">llvm::orc::EPCGenericDylibManager::open</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#a89babf245d443732b10c16ced7ca9c08">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::open</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a41461f685c104525ad436905851e4ef9">llvm::sys::fs::openFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a1ec43af01f0dd39a262169ec4109692b">llvm::sys::fs::openFileForReadWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aaa20e3a6a1473b383695503e0b5eb871">llvm::sys::fs::openFileForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a9dd05e067933397282c8f2b12374e26e">llvm::sys::fs::openNativeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a9c6a326cce84918de3996872b97f59c6">llvm::sys::fs::openNativeFileForReadWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a79b2823c3f2fae973d042ea09ab0aea1">llvm::sys::fs::openNativeFileForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cf91b4710cf2945f98c3786ce5eb705">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a1494d07aa891cb1dfc4f10de230fe2ab">outputDenormalIsIEEEOrPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3b7e007d72635d0f8c320a122f71947">llvm::parseDenormalFPAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab81263b19a504166d5c027a21cc15740">reduceVMULWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#a01decced737c074204373053cbf3febb">llvm::TargetOptions::setFP32DenormalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#a479c8c348a2ac67bcaf04394a8bf9bf1">llvm::TargetOptions::setFPDenormalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a72a03eaf18d396eb46f4c1a41bec628c">llvm::TargetMachine::setGlobalISelAbort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a853a1693caf74a6f250655800e136595">setXFormForUnalignedFI</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a1434db91cde03725c1860922f7f85ea8">llvm::yaml::SIMode::SIMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#abceca15aff80aa1ea3b5e7603981f878">toggleSPDenormMode</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a9b2b4ffb1b87b8ed16ab9c16cf645892">llvm::codeview::TypeIndex::TypeIndex</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"regalloc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
