---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/mlregallocevictadvisor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MLRegAllocEvictAdvisor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/allocationorder-h">AllocationOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/interactivemodelrunner-h">llvm/Analysis/InteractiveModelRunner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlmodelrunner-h">llvm/Analysis/MLModelRunner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/tensorspec-h">llvm/Analysis/TensorSpec.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-h">MLRegAllocEvictAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">llvm/Analysis/ReleaseModeModelRunner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">llvm/CodeGen/CalcSpillWeights.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerclassinfo-h">llvm/CodeGen/RegisterClassInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;array&gt;
#include &lt;bitset&gt;
#include &lt;memory&gt;
#include &lt;unordered_map&gt;
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regallocscoring">RegAllocScoring</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a> (RegAllocScoring, "regallocscoringpass", "Register Allocation Scoring Pass", false, false) namespace</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad904d7c5db4368de2766221c7c03e95e">InteractiveChannelBaseName</a>("regalloc-evict-interactive-channel-base", cl::Hidden, cl::desc("Base file path for the interactive mode. The incoming filename should " "have the name <regalloc-evict-interactive-channel-base>.in, while the " "outgoing name should be " "<regalloc-evict-interactive-channel-base>.out"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355f5fc8494549856ee56ba8d3cb5173">MaxEvictionCount</a>("mlregalloc-max-eviction-count", cl::Hidden, cl::desc("The maximum number of times a live range can be " "evicted before preventing it from being evicted"), cl::init(100))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e3c3a1aceecf0319f384dcaf5d1527">EnableDevelopmentFeatures</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ml-regalloc"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515fc759914affb744a8051ad8893317">RA_EVICT_FEATURES_LIST</a>(M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1c56a8bf40ac46f8f6a82fb6df6f01">RA_EVICT_FIRST_DEVELOPMENT_FEATURE</a>(M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3b7ffbb843818bc5c832eb3d3c00c5">RA_EVICT_REST_DEVELOPMENT_FEATURES</a>(M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e2460c58b78f9becd283f9f0dc70ee">DecisionName</a>&nbsp;&nbsp;&nbsp;"index_to_evict"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4023a440ae3369f07938e6d8756ed6">_FEATURE_IDX_SIMPLE</a>(_, name, __, ___)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2211171ff38facca1425f046da3358">_FEATURE_IDX</a>(A, B, C, D)&nbsp;&nbsp;&nbsp;<a href="#a5f4023a440ae3369f07938e6d8756ed6">_FEATURE_IDX_SIMPLE</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>),</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a7ac0b4d52374987b65476b4097bc5">_RESET</a>(TYPE, NAME, SHAPE, __)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5207224175d6dbe81f39fbae5ab0375">_DECL_FEATURES</a>(type, name, shape, _)&nbsp;&nbsp;&nbsp;  TensorSpec::createSpec&lt;type&gt;(#<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, shape),</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89522bf7a3fed31fd598afa139a2462c">SET</a>(ID, TYPE, VAL)&nbsp;&nbsp;&nbsp;...</td>
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

### INITIALIZE\_PASS() {#a4035cde766164dedab4604c02b29e045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/regallocscoring">RegAllocScoring</a>, "regallocscoringpass", "Register Allocation Scoring Pass", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>References <a href="#af5207224175d6dbe81f39fbae5ab0375">_DECL_FEATURES</a>, <a href="#aed2211171ff38facca1425f046da3358">_FEATURE_IDX</a>, <a href="#a5f4023a440ae3369f07938e6d8756ed6">_FEATURE_IDX_SIMPLE</a>, <a href="#a95a7ac0b4d52374987b65476b4097bc5">_RESET</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a12fa23ba554defbd00ab700ffece0eb5">llvm::RegAllocEvictionAdvisor::canEvictHintInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/tensorspec/#a48971e85ac1ac4e1598a6815bec525ab">llvm::TensorSpec::createSpec</a>, <a href="#af5e2460c58b78f9becd283f9f0dc70ee">DecisionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5594c85e0f17cd7a06c2efa5b5d8d2f5">llvm::DecisionSpec</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ab007d6c51634eb65e4f4f9dab4eb6a8c">llvm::Pass::doInitialization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a4447dfc5ac5a8784a0a933a5be56bbf5">llvm::LLVMContext::emitError</a>, <a href="#a26e3c3a1aceecf0319f384dcaf5d1527">EnableDevelopmentFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28437d232d14dd144fb44e8300e0f515a3520b48b0e451316168b36f113668638">llvm::FeatureCount</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#ae5482596d863d8c79a9fbbedc54ebd65">llvm::RegAllocEvictionAdvisorAnalysis::getAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#a005390fe88a690353da791886d6c1dcd">llvm::RegAllocEvictionAdvisorAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afcfb1380ec9ff3f6106193a6ea9313c6">llvm::Register::id</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b0a8e1d7f3ce779ed3aaf1150b37ad5">llvm::InputFeatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#a9e1d79b99b2115a50ef0d8ce2f31c990">InteractiveChannelBaseName</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#af85a271d5272cd8436126e7954862f30">llvm::RegAllocEvictionAdvisorAnalysis::logRewardIfNeeded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad14e5d0def0abedca4ae24afdef519c1">llvm::NumberOfInterferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6062cfafa5452a41fb3fc68aa52b423">llvm::PerLiveRangeShape</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="#a515fc759914affb744a8051ad8893317">RA_EVICT_FEATURES_LIST</a>, <a href="#a6d1c56a8bf40ac46f8f6a82fb6df6f01">RA_EVICT_FIRST_DEVELOPMENT_FEATURE</a>, <a href="#aaf3b7ffbb843818bc5c832eb3d3c00c5">RA_EVICT_REST_DEVELOPMENT_FEATURES</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#a569f300915b37b41ea6be1f09ec7c0af">llvm::RegAllocEvictionAdvisorAnalysis::RegAllocEvictionAdvisorAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a4788ed56977563b684675e9394cbb56f">llvm::RegAllocEvictionAdvisor::tryFindEvictionCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableDevelopmentFeatures {#a26e3c3a1aceecf0319f384dcaf5d1527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool EnableDevelopmentFeatures = false</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### InteractiveChannelBaseName {#ad904d7c5db4368de2766221c7c03e95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; InteractiveChannelBaseName("regalloc-evict-interactive-channel-base", cl::Hidden, cl::desc( "Base file path for the interactive mode. The incoming filename should " "have the name &lt;regalloc-evict-interactive-channel-base&gt;.in, while the " "outgoing name should be " "&lt;regalloc-evict-interactive-channel-base&gt;.out"))</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>

</div>
</div>

### MaxEvictionCount {#a355f5fc8494549856ee56ba8d3cb5173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxEvictionCount("mlregalloc-max-eviction-count", cl::Hidden, cl::desc("The maximum number of times a live range can be " "evicted before preventing it from being evicted"), cl::init(100))</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### \_DECL\_FEATURES {#af5207224175d6dbe81f39fbae5ab0375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _DECL_FEATURES(type, name, shape, _)&nbsp;&nbsp;&nbsp;  TensorSpec::createSpec&lt;type&gt;(#<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, shape),</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### \_FEATURE\_IDX {#aed2211171ff38facca1425f046da3358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _FEATURE_IDX(A, B, C, D)&nbsp;&nbsp;&nbsp;<a href="#a5f4023a440ae3369f07938e6d8756ed6">_FEATURE_IDX_SIMPLE</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>),</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### \_FEATURE\_IDX\_SIMPLE {#a5f4023a440ae3369f07938e6d8756ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _FEATURE_IDX_SIMPLE(_, name, __, ___)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### \_RESET {#a95a7ac0b4d52374987b65476b4097bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _RESET(TYPE, NAME, SHAPE, __)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  std::memset(Runner.getTensorUntyped(FeatureIDs::NAME), 0,                    \
              getTotalSize&lt;TYPE&gt;(SHAPE));
</div>
</dd>
</dl>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ml-regalloc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>

</div>
</div>

### DecisionName {#af5e2460c58b78f9becd283f9f0dc70ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DecisionName&nbsp;&nbsp;&nbsp;"index_to_evict"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### RA\_EVICT\_FEATURES\_LIST {#a515fc759914affb744a8051ad8893317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RA_EVICT_FEATURES_LIST(M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### RA\_EVICT\_FIRST\_DEVELOPMENT\_FEATURE {#a6d1c56a8bf40ac46f8f6a82fb6df6f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RA_EVICT_FIRST_DEVELOPMENT_FEATURE(M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### RA\_EVICT\_REST\_DEVELOPMENT\_FEATURES {#aaf3b7ffbb843818bc5c832eb3d3c00c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RA_EVICT_REST_DEVELOPMENT_FEATURES(M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>


<p>Referenced by <a href="#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### SET {#a89522bf7a3fed31fd598afa139a2462c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET(ID, TYPE, VAL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    Runner-&gt;getTensor&lt;TYPE&gt;(FeatureIDs::ID)[Pos] = static_cast&lt;TYPE&gt;(VAL);     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!<a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">DoNotNormalize.test</a>(FeatureIDs::ID))                                  \
      Largest[FeatureIDs::ID] =                                                \
          std::max(Largest[FeatureIDs::ID], static_cast&lt;float&gt;(VAL));          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp">MLRegAllocEvictAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
