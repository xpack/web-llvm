---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Mem2Reg.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/mem2reg-h">llvm/Transforms/Utils/Mem2Reg.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/promotememtoreg-h">llvm/Transforms/Utils/PromoteMemToReg.h</a>"
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mem2reg-cpp-">anonymous{Mem2Reg.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass">PromoteLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55abef45d8a59c2063daa078f60a495">STATISTIC</a> (NumPromoted, "Number of alloca's promoted")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9222048f2d7f5912d8aedb736b56654">promoteMemoryToRegister</a> (Function &amp;F, DominatorTree &amp;DT, AssumptionCache &amp;AC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c73d2613729ae023beb9bb5f0813430">INITIALIZE_PASS_BEGIN</a> (PromoteLegacyPass, "mem2reg", "Promote Memory to " "Register", false, false) INITIALIZE_PASS_END(PromoteLegacyPass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8987508c9bbbcbd92d99cdf22c43aef">mem2reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Promote <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> to</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Promote <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> to</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9fc8569b18a3197708790c362db9b4">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"mem2reg"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#a0c73d2613729ae023beb9bb5f0813430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (PromoteLegacyPass, "mem2reg", "Promote <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> to " "Register", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### promoteMemoryToRegister() {#ab9222048f2d7f5912d8aedb736b56654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool promoteMemoryToRegister (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a4cac84457299517e69ff9764fed2db">llvm::PromoteMemToReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/promotepass/#aca8a105910e7bb81285435f553e71872">llvm::PromotePass::run</a> and <a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass/#a44e2a30df5d10705e2a1a64790ac40a6">anonymous{Mem2Reg.cpp}::PromoteLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### STATISTIC() {#aa55abef45d8a59c2063daa078f60a495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPromoted, "Number of alloca's promoted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a4d9fc8569b18a3197708790c362db9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Promote Memory to false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>

</div>
</div>

### mem2reg {#ad8987508c9bbbcbd92d99cdf22c43aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mem2reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>

</div>
</div>

### Register {#a6fde3eb6ca09ddf2fd76432176d817bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Promote Memory to Register</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#aca1317aace2f68d72f2501db4e246017">llvm::LanaiInstrInfo::analyzeCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a86c872d6942793868e63eea201d0d8af">llvm::SIInstrInfo::analyzeCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a9a3a1e74e92fbb2346d4cd0b396d85b9">llvm::VirtRegOrUnit::asVirtualReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad914aa705137aa18db88ae760f534f25">llvm::buildAtomicInitInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e86010cc9381660c973391ab0034e00">llvm::buildAtomicStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6ab34a535b1441b48a0ede2c2aa6fb98">llvm::MachineIRBuilder::buildConstDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpandermve/#a8b570f6c1b94d49245ad3cee2887acf3">llvm::ModuloScheduleExpanderMVE::canApply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc6c42a7b5fe244fad430ca7df32d346">llvm::LegalizerHelper::coerceToScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a08a17634afdbaf2ee268be6118014845">llvm::CCValAssign::convertToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a01fce66601f12ad1b3bd219ff02c3426">llvm::VirtRegAuxInfo::copyHint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#add47e6d974ce584ea3fa3fc80ee34259">llvm::LiveRangeEdit::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acbd4fee4d18fa2066d758dff7168ef36">llvm::X86FrameLowering::emitCalleeSavedFrameMovesFullCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvduplicatestrackerbase/#a1fabb3f6b6435a52df7f3235848234a5">llvm::SPIRVDuplicatesTrackerBase&lt; KeyTy &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a81a328aa5781f7c744daa43c44df83c6">findImplicitSGPRRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#a401f6f1cca375064dd45ff964e5d0694">findLocalRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a98385033fc4d8cc660c0b3689f3ed51a">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromDef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aed0535a6ce0e4e5969a60a1635d0b18a">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51e652265b0217f8fdba9f95129c0d47">getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afc1af790923d299c9f6c0b631034dbc6">llvm::AMDGPU::getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0ea645bf4979099839a35654aac5d755">llvm::ARMTargetLowering::getExceptionPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ade4c9edab20f271644c8678ae6764c69">llvm::TargetLoweringBase::getExceptionPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab0632dd0936481e952514e2f8e18db07">llvm::ARMTargetLowering::getExceptionSelectorRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af00cd85bb1e2d2286212e74352c0a191">llvm::TargetLoweringBase::getExceptionSelectorRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a317bd7480ba741300b70f6243d33ff1f">llvm::SIRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#acf7cd68bf3ebca5b731b601c8bba1d64">llvm::SPIRV::ModuleAnalysisInfo::getFuncReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a565000e767f6a2f5381abbb683853bbe">llvm::SIMachineFunctionInfo::getGITPtrLoReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a9cc1aea4b14234362915bdb5c776573f">llvm::MachineRegisterInfo::getLiveInVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a50a1e1a9de471f2ababb7bfa3f3b7fdf">getLoadInfo</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a00b889b10d5eaeb7be44d959e67263c6">LiveDebugValues::MLocTracker::getLocSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8bc629292d5cf14604e9b35b42ac4706">llvm::MachineRegisterInfo::getRegAllocationHint</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#a042607ec02c65862f1bddded07e23082">llvm::SPIRV::ModuleAnalysisInfo::getRegisterAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae7573ce36a4dba9654c530165584e450">llvm::HexagonTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21a0e970e98d8f88cee991fe790e1fe9">llvm::MipsTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697cb1debe6ad1be7e59990072185844">llvm::SITargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a021a3cabd072c6984bf30b0f8a3fc0a6">llvm::MachineRegisterInfo::getSimpleHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb39eef3d8e7cf19a9145c51a5e46253">llvm::getSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a0256194175f52db6cc06eb379bd412dc">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a3bea0d2df6224f7191466538e5ef0c9f">getWaveAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a4af3414dbf16e5eb1b862c7cf35ed83c">llvm::VirtRegMap::hasPreferredPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a92cd11abfd541caadc1fc825b78f9903">llvm::Register::index2StackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertreadwritecsr-cpp/#a93ca2859094e3f43227290d2f88472c9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">llvm::FunctionLoweringInfo::InitializeRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#abb8f23e350645aee0d5c95e93bc59253">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::insertReloadBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/coalescerpair/#aa94992e6e4022b1175f8015cde4e60b9">llvm::CoalescerPair::isCoalescable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#aaa2bd04c34b59b5b2a2c0189c58bc55b">isCopyOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aac9bf357fe1b75c63b4b789a93b0a7a7">llvm::SIInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a5b40db147e6d8fc29370404415cca355">llvm::XtensaInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#afb5a8099c7351303ef337ec57d5e8e24">llvm::SIInstrInfo::isStackAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a207df7ea2d140c874d9b1d93d60774c7">llvm::SIInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a14f47af4e76891b8f52ba893feb90733">llvm::XtensaInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab0873d6f5bfe8490b5ef6be3a84dd805">llvm::AMDGPULegalizerInfo::legalizeWaveID</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a43b22ba78d684fd69b551c4c04426e3d">LookForIdenticalPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a56f7f2867c8f943ceb672823c013df28">llvm::TargetRegisterInfo::lookThruSingleUseCopyChain</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aaf88f3025beeaebb5bd345ebe277711c">llvm::CombinerHelper::matchRedundantBinOpInEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a92451ecb6973ca4c1190514f75618d40">matchZeroExtendFromS32</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ab7155d5feabf02f01c4d3b7d9c422">llvm::LegalizerHelper::narrowScalarShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aeaeffb171ae383d18f217fbd278c8717">llvm::RISCVInstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/structs/scopedscavengeorspill/#ab0ac2a9aa1075f3e566bf2e74dafa8b7">ScopedScavengeOrSpill::ScopedScavengeOrSpill</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/coalescerpair/#acf12cb8b07d5443c8777257d1b9a1dc7">llvm::CoalescerPair::setRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a757685f42fe19ad1375d53c7e5aa95b1">llvm::XtensaFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a7c833b32f9576a77193082ed28b7a5cf">AMDGPURegBankLegalizeCombiner::tryMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a> and <a href="/web-llvm/docs/api/structs/scopedscavengeorspill/#ae1cc730fd485ab330afad97706ccd60d">ScopedScavengeOrSpill::~ScopedScavengeOrSpill</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"mem2reg"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp">Mem2Reg.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
