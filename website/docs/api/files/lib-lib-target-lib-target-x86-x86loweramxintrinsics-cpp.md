---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86LowerAMXIntrinsics.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86-h">X86.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "llvm/IR/IntrinsicsX86.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86loweramxintrinsics-cpp-">anonymous{X86LowerAMXIntrinsics.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics">X86LowerAMXIntrinsics</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass">X86LowerAMXIntrinsicsLegacyPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c08ee0c063916d061cf1d064a2e97f">isV256I32Ty</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae652287d9b56224da1497ec0c3fe455a">INITIALIZE_PASS_BEGIN</a> (X86LowerAMXIntrinsicsLegacyPass, DEBUG_TYPE, PassName, false, false) INITIALIZE_PASS_END(X86LowerAMXIntrinsicsLegacyPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42599f193380ef3118a218893b14713">X86ScalarizeAMX</a>("enable-x86-scalar-amx", cl::init(false), cl::Hidden, cl::desc("X86: enable AMX scalarizition."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb9257105a403ef9d0773b87693f7779">PassName</a>[] = "Lower AMX intrinsics"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c865df784842196d411c1466b01686">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"lower-amx-intrinsics"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#ae652287d9b56224da1497ec0c3fe455a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (X86LowerAMXIntrinsicsLegacyPass, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#adb9257105a403ef9d0773b87693f7779">PassName</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a> and <a href="#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### isV256I32Ty() {#ac5c08ee0c063916d061cf1d064a2e97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isV256I32Ty (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>.</p>

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



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### false {#ae6c865df784842196d411c1466b01686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### PassName {#adb9257105a403ef9d0773b87693f7779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassName = "Lower AMX intrinsics"</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks/#aa873fdcd4cdc152f84a4cec7f00ff4b7">llvm::PassInstrumentationCallbacks::addClassToPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitter/#a6a43a7e6e9af2d21b402eb6a76b25799">llvm::MachineOptimizationRemarkEmitter::allowExtraAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#a19c3c3d0ac78d71ea5d4c759c8c8db9d">llvm::OptimizationRemarkEmitter::allowExtraAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#af6dacb86673ab0eec1cbbcdc1a031c77">llvm::OptimizationRemarkEmitter::allowExtraAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#a74b26949a0dd7a5fab2ba1b0da204e50">llvm::OptimizationRemarkEmitter::allowExtraAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1722ea06b072db7df9423d31e810c455">llvm::callDefaultCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a0d95457b7af7593624ad31405198d59d">llvm::PassBuilder::checkParametrizedPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#afec6951f3043e25ada2b61437bd60725">createLVAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ce71d047dc00014a965d0907a0aabde">llvm::emitInlinedInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83035d5c2bb6a64f3c35b716a994b586">llvm::emitInlinedIntoBasedOnCost</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab3115ef36979b45874f244f374e79d98">llvm::PMDataManager::emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a3c5faae50cf1ccc5bf0d1936557030ec">getPassIDFromName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a4d52a5b3d278b07fa7992477cc3c5474">getPassNameAndInstanceNum</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-passtiminginfo-cpp-/legacy/passtiminginfo/#a6a4d99a79c2bcaaf0e30b92826156793">llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::getPassTimer</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>, <a href="#ae652287d9b56224da1497ec0c3fe455a">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a2137b1559a07e8633b8c8ee6dcec8fc0">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a9491283253671daad4d7d6cebbba3df2">llvm::DiagnosticHandler::isAnalysisRemarkEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#ab057d53fef7c0851c7313dc26b2aa4eb">llvm::DiagnosticHandler::isAnyRemarkEnabled</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#aedc4f4ea606ac0d1b036400c31d43da9">anonymous{StandardInstrumentations.cpp}::isInteresting</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#aa7f8497579cb50322178c9b6e1daacaa">llvm::DiagnosticHandler::isMissedOptRemarkEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a03d19acbb7c39a4b3c8f818e5b467cf2">llvm::DiagnosticHandler::isPassedOptRemarkEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059a29de9752b72c252ece47fdb42b0">llvm::isPassInPrintList</a>, <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga03d12c9d1603fb8ceafb3957e1fefd70">LLVMRemarkEntryGetPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#abfdf1e9171811abf703f9a03c1534569">mapRemarkHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad552dcd2825d0f59fae310931b7813bb">llvm::PassBuilder::parsePassParameters</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adc2db790282de50547f17992a5dece6b">llvm::PassBuilder::parseSinglePassOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a69226e2a3cc621d634b8c3d3e0023b13">printPassName</a>, <a href="/web-llvm/docs/api/structs/llvm/invalidateanalysispass/#a04c9ac03e284c891cf872820d63eb63f">llvm::InvalidateAnalysisPass&lt; AnalysisT &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#aa4cc9f41bee4680f8bc4dce320d8f7c7">llvm::PassInfoMixin&lt; DerivedT &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/structs/llvm/requireanalysispass/#a52cbd06bde6a2e128df765fb23691658">llvm::RequireAnalysisPass&lt; AnalysisT, IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/structs/llvm/requireanalysispass-498ca4f351a1bdb57b4c30b5c00bae4c/#a00f058ae717dd0dbb12e51e00e1c0246">llvm::RequireAnalysisPass&lt; AnalysisT, LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ab2b73a9eaecb02a4ec3beebaa431b972">llvm::OptPassGateInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2b71d462b14e085a6a1d4b0a1d5e82">llvm::reportGISelFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ae62ce11c6238e393618108540027706f">llvm::OptPassGateInstrumentation::shouldRun</a>, <a href="/web-llvm/docs/api/classes/llvm/optbisect/#a0f286bb86d244482b2f03ac4f1943423">llvm::OptBisect::shouldRunPass</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgate/#a59de8deea51271200bbfc1e5be45ee3c">llvm::OptPassGate::shouldRunPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a8eb4d536e570cc08e82d91095b892ed2">writeJSON</a> and <a href="/web-llvm/docs/api/classes/llvm/optbisect/#af1feac61c73583a592d7a88e288f996f">llvm::OptBisect::~OptBisect</a>.</p>

</div>
</div>

### X86ScalarizeAMX {#aa42599f193380ef3118a218893b14713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; X86ScalarizeAMX("enable-x86-scalar-amx", cl::init(false), cl::Hidden, cl::desc("X86: enable AMX scalarizition."))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#a3676b694f0f141994877ccf4564027ef">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::runOnFunction</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"lower-amx-intrinsics"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
