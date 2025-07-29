---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/passes/passbuilderpipelines-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PassBuilderPipelines.cpp` File

<p>This file provides the implementation of the <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> based on our static pass registry as well as related functionality. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">llvm/Analysis/CtxProfAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scopednoaliasaa-h">llvm/Analysis/ScopedNoAliasAA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h">llvm/CodeGen/GlobalMergeFunctions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">llvm/Passes/OptimizationLevel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">llvm/Support/PGOOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/aggressiveinstcombine/aggressiveinstcombine-h">llvm/Transforms/AggressiveInstCombine/AggressiveInstCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroannotationelide-h">llvm/Transforms/Coroutines/CoroAnnotationElide.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corocleanup-h">llvm/Transforms/Coroutines/CoroCleanup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroconditionalwrapper-h">llvm/Transforms/Coroutines/CoroConditionalWrapper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroearly-h">llvm/Transforms/Coroutines/CoroEarly.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroelide-h">llvm/Transforms/Coroutines/CoroElide.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">llvm/Transforms/Coroutines/CoroSplit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/hipstdpar/hipstdpar-h">llvm/Transforms/HipStdPar/HipStdPar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/alwaysinliner-h">llvm/Transforms/IPO/AlwaysInliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/annotation2metadata-h">llvm/Transforms/IPO/Annotation2Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/argumentpromotion-h">llvm/Transforms/IPO/ArgumentPromotion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/calledvaluepropagation-h">llvm/Transforms/IPO/CalledValuePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/constantmerge-h">llvm/Transforms/IPO/ConstantMerge.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/crossdsocfi-h">llvm/Transforms/IPO/CrossDSOCFI.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">llvm/Transforms/IPO/DeadArgumentElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/elimavailextern-h">llvm/Transforms/IPO/ElimAvailExtern.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/embedbitcodepass-h">llvm/Transforms/IPO/EmbedBitcodePass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/expandvariadics-h">llvm/Transforms/IPO/ExpandVariadics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">llvm/Transforms/IPO/ForceFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionattrs-h">llvm/Transforms/IPO/FunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">llvm/Transforms/IPO/GlobalDCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globalopt-h">llvm/Transforms/IPO/GlobalOpt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globalsplit-h">llvm/Transforms/IPO/GlobalSplit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/hotcoldsplitting-h">llvm/Transforms/IPO/HotColdSplitting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">llvm/Transforms/IPO/IROutliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inferfunctionattrs-h">llvm/Transforms/IPO/InferFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">llvm/Transforms/IPO/Inliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">llvm/Transforms/IPO/LowerTypeTests.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">llvm/Transforms/IPO/MemProfContextDisambiguation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/mergefunctions-h">llvm/Transforms/IPO/MergeFunctions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">llvm/Transforms/IPO/ModuleInliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">llvm/Transforms/IPO/OpenMPOpt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/partialinlining-h">llvm/Transforms/IPO/PartialInlining.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">llvm/Transforms/IPO/SCCP.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofile-h">llvm/Transforms/IPO/SampleProfile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofileprobe-h">llvm/Transforms/IPO/SampleProfileProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombine-h">llvm/Transforms/InstCombine/InstCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cgprofile-h">llvm/Transforms/Instrumentation/CGProfile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/controlheightreduction-h">llvm/Transforms/Instrumentation/ControlHeightReduction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/instrorderfile-h">llvm/Transforms/Instrumentation/InstrOrderFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/instrprofiling-h">llvm/Transforms/Instrumentation/InstrProfiling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/memprofiler-h">llvm/Transforms/Instrumentation/MemProfiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoctxprofflattening-h">llvm/Transforms/Instrumentation/PGOCtxProfFlattening.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoctxproflowering-h">llvm/Transforms/Instrumentation/PGOCtxProfLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoforcefunctionattrs-h">llvm/Transforms/Instrumentation/PGOForceFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoinstrumentation-h">llvm/Transforms/Instrumentation/PGOInstrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/adce-h">llvm/Transforms/Scalar/ADCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/alignmentfromassumptions-h">llvm/Transforms/Scalar/AlignmentFromAssumptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/annotationremarks-h">llvm/Transforms/Scalar/AnnotationRemarks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/bdce-h">llvm/Transforms/Scalar/BDCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/callsitesplitting-h">llvm/Transforms/Scalar/CallSiteSplitting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/constraintelimination-h">llvm/Transforms/Scalar/ConstraintElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/correlatedvaluepropagation-h">llvm/Transforms/Scalar/CorrelatedValuePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/dfajumpthreading-h">llvm/Transforms/Scalar/DFAJumpThreading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/deadstoreelimination-h">llvm/Transforms/Scalar/DeadStoreElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/divrempairs-h">llvm/Transforms/Scalar/DivRemPairs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/earlycse-h">llvm/Transforms/Scalar/EarlyCSE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/float2int-h">llvm/Transforms/Scalar/Float2Int.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">llvm/Transforms/Scalar/GVN.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/indvarsimplify-h">llvm/Transforms/Scalar/IndVarSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/inferalignment-h">llvm/Transforms/Scalar/InferAlignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/instsimplifypass-h">llvm/Transforms/Scalar/InstSimplifyPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/jumptabletoswitch-h">llvm/Transforms/Scalar/JumpTableToSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/jumpthreading-h">llvm/Transforms/Scalar/JumpThreading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/licm-h">llvm/Transforms/Scalar/LICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopdeletion-h">llvm/Transforms/Scalar/LoopDeletion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopdistribute-h">llvm/Transforms/Scalar/LoopDistribute.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopflatten-h">llvm/Transforms/Scalar/LoopFlatten.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopidiomrecognize-h">llvm/Transforms/Scalar/LoopIdiomRecognize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">llvm/Transforms/Scalar/LoopInstSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinterchange-h">llvm/Transforms/Scalar/LoopInterchange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looploadelimination-h">llvm/Transforms/Scalar/LoopLoadElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looprotation-h">llvm/Transforms/Scalar/LoopRotation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsimplifycfg-h">llvm/Transforms/Scalar/LoopSimplifyCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">llvm/Transforms/Scalar/LoopSink.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">llvm/Transforms/Scalar/LoopUnrollAndJamPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">llvm/Transforms/Scalar/LoopUnrollPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopversioninglicm-h">llvm/Transforms/Scalar/LoopVersioningLICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerconstantintrinsics-h">llvm/Transforms/Scalar/LowerConstantIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerexpectintrinsic-h">llvm/Transforms/Scalar/LowerExpectIntrinsic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowermatrixintrinsics-h">llvm/Transforms/Scalar/LowerMatrixIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">llvm/Transforms/Scalar/MemCpyOptimizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/mergedloadstoremotion-h">llvm/Transforms/Scalar/MergedLoadStoreMotion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/newgvn-h">llvm/Transforms/Scalar/NewGVN.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">llvm/Transforms/Scalar/Reassociate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/sccp-h">llvm/Transforms/Scalar/SCCP.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/sroa-h">llvm/Transforms/Scalar/SROA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">llvm/Transforms/Scalar/SimpleLoopUnswitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simplifycfg-h">llvm/Transforms/Scalar/SimplifyCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/speculativeexecution-h">llvm/Transforms/Scalar/SpeculativeExecution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/tailrecursionelimination-h">llvm/Transforms/Scalar/TailRecursionElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/warnmissedtransforms-h">llvm/Transforms/Scalar/WarnMissedTransforms.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/adddiscriminators-h">llvm/Transforms/Utils/AddDiscriminators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/assumebundlebuilder-h">llvm/Transforms/Utils/AssumeBundleBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/canonicalizealiases-h">llvm/Transforms/Utils/CanonicalizeAliases.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/countvisits-h">llvm/Transforms/Utils/CountVisits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/entryexitinstrumenter-h">llvm/Transforms/Utils/EntryExitInstrumenter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/extrapassmanager-h">llvm/Transforms/Utils/ExtraPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/injecttlimappings-h">llvm/Transforms/Utils/InjectTLIMappings.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/libcallsshrinkwrap-h">llvm/Transforms/Utils/LibCallsShrinkWrap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/mem2reg-h">llvm/Transforms/Utils/Mem2Reg.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moveautoinit-h">llvm/Transforms/Utils/MoveAutoInit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/nameanonglobals-h">llvm/Transforms/Utils/NameAnonGlobals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/rellookuptableconverter-h">llvm/Transforms/Utils/RelLookupTableConverter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/simplifycfgoptions-h">llvm/Transforms/Utils/SimplifyCFGOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">llvm/Transforms/Vectorize/LoopVectorize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/slpvectorizer-h">llvm/Transforms/Vectorize/SLPVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/vectorcombine-h">llvm/Transforms/Vectorize/VectorCombine.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a> (ModulePassManager &amp;MPM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a> (ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47144f1542bc8c796ab5f24db367b532">getInlineParamsFromOptLevel</a> (OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488fa">InliningAdvisorMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf596ddba11c5164c5952d85904091a">UseInlineAdvisor</a>("enable-ml-inliner", cl::init(InliningAdvisorMode::Default), cl::Hidden, cl::desc("Enable ML policy for inliner. Currently trained for -Oz only"), cl::values(clEnumValN(InliningAdvisorMode::Default, "default", "Heuristics-based inliner version"), clEnumValN(InliningAdvisorMode::Development, "development", "Use development mode (runtime-loadable model)"), clEnumValN(InliningAdvisorMode::Release, "release", "Use release mode (AOT-compiled model)")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a0ad2772eaf276be6d60566679ddc5">EnablePGOInlineDeferral</a>("enable-npm-pgo-inline-deferral", cl::init(true), cl::Hidden, cl::desc("Enable inline deferral during PGO"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to enable inline deferral during PGO. <a href="#ae0a0ad2772eaf276be6d60566679ddc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa556c7cc4c95543e35c32420d9054a06">EnableModuleInliner</a>("enable-module-inliner", cl::init(false), cl::Hidden, cl::desc("Enable module inliner"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fac5b18f0e4f22a34c200f1719b9f4">PerformMandatoryInliningsFirst</a>("mandatory-inlining-first", cl::init(false), cl::Hidden, cl::desc("Perform mandatory inlinings module-wide, before performing " "inlining"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2579919664d84b31b404d697d8ea5a">EnableEagerlyInvalidateAnalyses</a>("eagerly-invalidate-analyses", cl::init(true), cl::Hidden, cl::desc("Eagerly invalidate more analyses in default pipelines"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038daaefae1a34b95cd6f879efba8dac">EnableMergeFunctions</a>("enable-merge-functions", cl::init(false), cl::Hidden, cl::desc("Enable function merging as part of the optimization pipeline"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b42d93b21392e71ca82f6e3531f37a">EnablePostPGOLoopRotation</a>("enable-post-pgo-loop-rotation", cl::init(true), cl::Hidden, cl::desc("Run the loop rotation transformation after PGO instrumentation"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07068e2ce7a7e26efcbd160d919131e0">EnableGlobalAnalyses</a>("enable-global-analyses", cl::init(true), cl::Hidden, cl::desc("Enable inter-procedural analyses"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556f58c089a2d5bf23d908286807155d">RunPartialInlining</a>("enable-partial-inlining", cl::init(false), cl::Hidden, cl::desc("Run Partial inlining pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6260ca0d9be894b56c2dc757856102">ExtraVectorizerPasses</a>("extra-vectorizer-passes", cl::init(false), cl::Hidden, cl::desc("Run cleanup optimization passes after vectorization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174f40086d77810c7576da30090256c7">RunNewGVN</a>("enable-newgvn", cl::init(false), cl::Hidden, cl::desc("Run the NewGVN pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b47f3111c117e5ecf66de241383ace0">EnableLoopInterchange</a>("enable-loopinterchange", cl::init(false), cl::Hidden, cl::desc("Enable the experimental LoopInterchange Pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3846595dce89206a51827ea0e7b5cc">EnableUnrollAndJam</a>("enable-unroll-and-jam", cl::init(false), cl::Hidden, cl::desc("Enable Unroll And Jam Pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2b9f098207a078c00b48f1b7d84c7c">EnableLoopFlatten</a>("enable-loop-flatten", cl::init(false), cl::Hidden, cl::desc("Enable the LoopFlatten Pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ecb8d5f449a43f6e74d393bd07afd4">EnableLoopHeaderDuplication</a>("enable-loop-header-duplication", cl::init(false), cl::Hidden, cl::desc("Enable loop header duplication at any optimization level"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60609c67166415de63f7367a9b0f22c8">EnableDFAJumpThreading</a>("enable-dfa-jump-thread", cl::desc("Enable DFA jump threading"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677d33a7278b4e353580d0d3d1f753f5">EnableHotColdSplit</a>("hot-cold-split", cl::desc("Enable hot-cold splitting pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147973e09ae9cccd4c6535ac4715e57b">EnableIROutliner</a>("ir-outliner", cl::init(false), cl::Hidden, cl::desc("Enable ir outliner pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23a5342771036e3399d503c93bb169a2">DisablePreInliner</a>("disable-preinline", cl::init(false), cl::Hidden, cl::desc("Disable pre-instrumentation inliner"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e49230c36c2f00ec7d045bffbdf441c">PreInlineThreshold</a>("preinline-threshold", cl::Hidden, cl::init(75), cl::desc("Control the amount of inlining in pre-instrumentation inliner " "(default = 75)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53eae0026e1e39f98f02d1a9cb213abf">EnableGVNHoist</a>("enable-gvn-hoist", cl::desc("Enable the GVN hoisting pass (default = off)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a81cb8f842b4e3e1f78700ea2d151b">EnableGVNSink</a>("enable-gvn-sink", cl::desc("Enable the GVN sinking pass (default = off)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9a5c9f225f123cd31f939d2cbc85aec">EnableJumpTableToSwitch</a>("enable-jump-table-to-switch", cl::desc("Enable JumpTableToSwitch pass (default = off)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62062994dbc7f2620661b2754f56e77f">EnableCHR</a>("enable-chr", cl::init(true), cl::Hidden, cl::desc("Enable control height reduction optimization (CHR)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91498eeffa9ef283e2b3f09ce5aecdad">FlattenedProfileUsed</a>("flattened-profile-used", cl::init(false), cl::Hidden, cl::desc("Indicate the sample profile being used is flattened, i.e., " "no inline hierarchy exists in the profile"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab014a9dea3bd22a84ce6f9013e29c9a5">EnableOrderFileInstrumentation</a>("enable-order-file-instrumentation", cl::init(false), cl::Hidden, cl::desc("Enable order file instrumentation (default = off)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8deaf695ec0d3236d60155a49886675">EnableMatrix</a>("enable-matrix", cl::init(false), cl::Hidden, cl::desc("Enable lowering of the matrix intrinsics"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd19b715cb1f5c8367c22f83d7e67074">EnableConstraintElimination</a>("enable-constraint-elimination", cl::init(true), cl::Hidden, cl::desc("Enable pass to eliminate conditions based on linear constraints"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a51e547c2283920aa77da2650a8ee3a7a">AttributorRunOption</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa594268ee5559702b52d2407d79e97">AttributorRun</a>("attributor-enable", cl::Hidden, cl::init(AttributorRunOption::NONE), cl::desc("Enable the attributor inter-procedural deduction pass"), cl::values(clEnumValN(AttributorRunOption::ALL, "all", "enable all attributor runs"), clEnumValN(AttributorRunOption::MODULE, "module", "enable module-wide attributor runs"), clEnumValN(AttributorRunOption::CGSCC, "cgscc", "enable call graph SCC attributor runs"), clEnumValN(AttributorRunOption::NONE, "none", "disable attributor runs")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8e8fe3e8dec1b07d818835eb176097">EnableSampledInstr</a>("enable-sampled-instrumentation", cl::init(false), cl::Hidden, cl::desc("Enable profile instrumentation sampling (default = off)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb43570bd79eef6f5949838628de6dc6">UseLoopVersioningLICM</a>("enable-loop-versioning-licm", cl::init(false), cl::Hidden, cl::desc("Enable the experimental Loop Versioning LICM pass"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f330a9fae040126d941e0a823328fb0">InstrumentColdFuncOnlyPath</a>("instrument-cold-function-only-path", cl::init(""), cl::desc("File path for cold function only instrumentation(requires use " "with --pgo-instrument-cold-function-only)"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac99641888d5b06352c629f38485394">UseCtxProfile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0425acc737a4cb44fe7563204bf72f1">PGOInstrumentColdFunctionOnly</a></td>
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

<p>This file provides the implementation of the <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> based on our static pass registry as well as related functionality.</p>


<p>It also provides helpers to aid in analyzing, debugging, and testing passes and pass pipelines.</p>


<div class="doxySectionDef">

## Functions

### addAnnotationRemarksPass() {#a38315765eaec2665ca76556b908a593d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addAnnotationRemarksPass (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad4548cd9e4b6358214f2e34e5e56112e">llvm::PassBuilder::buildFatLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a546f4259efb4e1629d1d14b8757c52c4">llvm::PassBuilder::buildPerModuleDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab7d260f2f928c81a2d225f2d1aafad0e">llvm::PassBuilder::buildThinLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2832cb00a6c94208b4a06696eeeabf99">llvm::PassBuilder::buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### getInlineParamsFromOptLevel() {#a47144f1542bc8c796ab5f24db367b532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineParams getInlineParamsFromOptLevel (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
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



<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">llvm::getInlineParams</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>.</p>

</div>
</div>

### isLTOPreLink() {#acaebc8d799e882b2896fcee54e070388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLTOPreLink (<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a123c9da36c4ea6b13da1c4dd2e955c3b">llvm::FullLTOPreLink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a94e03b8856e739853a1419da126f1758">llvm::PassBuilder::buildO0DefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a546f4259efb4e1629d1d14b8757c52c4">llvm::PassBuilder::buildPerModuleDefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ab727dbb342900913787fc58840a3c002">llvm::AMDGPUTargetMachine::registerPassBuilderCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AttributorRun {#aaaa594268ee5559702b52d2407d79e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; AttributorRunOption &gt; AttributorRun("attributor-enable", cl::Hidden, cl::init(AttributorRunOption::NONE), cl::desc("Enable the attributor inter-procedural deduction pass"), cl::values(clEnumValN(AttributorRunOption::ALL, "all", "enable all attributor runs"), clEnumValN(AttributorRunOption::MODULE, "module", "enable module-wide attributor runs"), clEnumValN(AttributorRunOption::CGSCC, "cgscc", "enable call graph SCC attributor runs"), clEnumValN(AttributorRunOption::NONE, "none", "disable attributor runs")))</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### DisablePreInliner {#a23a5342771036e3399d503c93bb169a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePreInliner("disable-preinline", cl::init(false), cl::Hidden, cl::desc("Disable pre-instrumentation inliner"))</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### EnableCHR {#a62062994dbc7f2620661b2754f56e77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCHR("enable-chr", cl::init(true), cl::Hidden, cl::desc("Enable control height reduction optimization (CHR)"))</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnableConstraintElimination {#afd19b715cb1f5c8367c22f83d7e67074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableConstraintElimination("enable-constraint-elimination", cl::init(true), cl::Hidden, cl::desc( "Enable pass to eliminate conditions based on linear constraints"))</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>.</p>

</div>
</div>

### EnableDFAJumpThreading {#a60609c67166415de63f7367a9b0f22c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableDFAJumpThreading("enable-dfa-jump-thread", cl::desc("Enable DFA jump threading"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>.</p>

</div>
</div>

### EnableEagerlyInvalidateAnalyses {#a2c2579919664d84b31b404d697d8ea5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEagerlyInvalidateAnalyses("eagerly-invalidate-analyses", cl::init(true), cl::Hidden, cl::desc("Eagerly invalidate more analyses in default pipelines"))</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions/#acb41cc3f45423b2af2334a6e2b0c087e">llvm::PipelineTuningOptions::PipelineTuningOptions</a>.</p>

</div>
</div>

### EnableGlobalAnalyses {#a07068e2ce7a7e26efcbd160d919131e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGlobalAnalyses("enable-global-analyses", cl::init(true), cl::Hidden, cl::desc("Enable inter-procedural analyses"))</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a1d045f9463f65181b84ac5dc7eafafe8">llvm::PassBuilder::buildDefaultAAPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnableGVNHoist {#a53eae0026e1e39f98f02d1a9cb213abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGVNHoist("enable-gvn-hoist", cl::desc("Enable the GVN hoisting pass (default = off)"))</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>.</p>

</div>
</div>

### EnableGVNSink {#a47a81cb8f842b4e3e1f78700ea2d151b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGVNSink("enable-gvn-sink", cl::desc("Enable the GVN sinking pass (default = off)"))</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>.</p>

</div>
</div>

### EnableHotColdSplit {#a677d33a7278b4e353580d0d3d1f753f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableHotColdSplit("hot-cold-split", cl::desc("Enable hot-cold splitting pass"))</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnableIROutliner {#a147973e09ae9cccd4c6535ac4715e57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableIROutliner("ir-outliner", cl::init(false), cl::Hidden, cl::desc("Enable ir outliner pass"))</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnableJumpTableToSwitch {#ae9a5c9f225f123cd31f939d2cbc85aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableJumpTableToSwitch("enable-jump-table-to-switch", cl::desc("Enable JumpTableToSwitch pass (default = off)"))</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>.</p>

</div>
</div>

### EnableLoopFlatten {#aff2b9f098207a078c00b48f1b7d84c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopFlatten("enable-loop-flatten", cl::init(false), cl::Hidden, cl::desc("Enable the LoopFlatten Pass"))</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>.</p>

</div>
</div>

### EnableLoopHeaderDuplication {#a96ecb8d5f449a43f6e74d393bd07afd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopHeaderDuplication("enable-loop-header-duplication", cl::init(false), cl::Hidden, cl::desc("Enable loop header duplication at any optimization level"))</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnableLoopInterchange {#a6b47f3111c117e5ecf66de241383ace0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopInterchange("enable-loopinterchange", cl::init(false), cl::Hidden, cl::desc("Enable the experimental LoopInterchange Pass"))</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>.</p>

</div>
</div>

### EnableMatrix {#aa8deaf695ec0d3236d60155a49886675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMatrix("enable-matrix", cl::init(false), cl::Hidden, cl::desc("Enable lowering of the matrix intrinsics"))</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a94e03b8856e739853a1419da126f1758">llvm::PassBuilder::buildO0DefaultPipeline</a>.</p>

</div>
</div>

### EnableMergeFunctions {#a038daaefae1a34b95cd6f879efba8dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMergeFunctions("enable-merge-functions", cl::init(false), cl::Hidden, cl::desc("Enable function merging as part of the optimization pipeline"))</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions/#acb41cc3f45423b2af2334a6e2b0c087e">llvm::PipelineTuningOptions::PipelineTuningOptions</a>.</p>

</div>
</div>

### EnableModuleInliner {#aa556c7cc4c95543e35c32420d9054a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableModuleInliner("enable-module-inliner", cl::init(false), cl::Hidden, cl::desc("Enable module inliner"))</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### EnableOrderFileInstrumentation {#ab014a9dea3bd22a84ce6f9013e29c9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableOrderFileInstrumentation("enable-order-file-instrumentation", cl::init(false), cl::Hidden, cl::desc("Enable order file instrumentation (default = off)"))</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

### EnablePGOInlineDeferral {#ae0a0ad2772eaf276be6d60566679ddc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePGOInlineDeferral("enable-npm-pgo-inline-deferral", cl::init(true), cl::Hidden, cl::desc("Enable inline deferral during PGO"))</td>
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

<p>Flag to enable inline deferral during PGO.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>.</p>

</div>
</div>

### EnablePostPGOLoopRotation {#a42b42d93b21392e71ca82f6e3531f37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePostPGOLoopRotation("enable-post-pgo-loop-rotation", cl::init(true), cl::Hidden, cl::desc("Run the loop rotation transformation after PGO instrumentation"))</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### EnableSampledInstr {#a7e8e8fe3e8dec1b07d818835eb176097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSampledInstr("enable-sampled-instrumentation", cl::init(false), cl::Hidden, cl::desc("Enable profile instrumentation sampling (default = off)"))</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### EnableUnrollAndJam {#a9e3846595dce89206a51827ea0e7b5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableUnrollAndJam("enable-unroll-and-jam", cl::init(false), cl::Hidden, cl::desc("Enable Unroll And Jam Pass"))</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### ExtraVectorizerPasses {#a2d6260ca0d9be894b56c2dc757856102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ExtraVectorizerPasses("extra-vectorizer-passes", cl::init(false), cl::Hidden, cl::desc("Run cleanup optimization passes after vectorization"))</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### FlattenedProfileUsed {#a91498eeffa9ef283e2b3f09ce5aecdad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; FlattenedProfileUsed("flattened-profile-used", cl::init(false), cl::Hidden, cl::desc("Indicate the sample profile being used is flattened, i.e., " "no inline hierarchy exists in the profile"))</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### InstrumentColdFuncOnlyPath {#a9f330a9fae040126d941e0a823328fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; InstrumentColdFuncOnlyPath("instrument-cold-function-only-path", cl::init(""), cl::desc("File path for cold function only instrumentation(requires use " "with --pgo-instrument-cold-function-only)"), cl::Hidden)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### PerformMandatoryInliningsFirst {#a47fac5b18f0e4f22a34c200f1719b9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PerformMandatoryInliningsFirst("mandatory-inlining-first", cl::init(false), cl::Hidden, cl::desc("Perform mandatory inlinings module-wide, before performing " "inlining"))</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>.</p>

</div>
</div>

### PGOInstrumentColdFunctionOnly {#aa0425acc737a4cb44fe7563204bf72f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; PGOInstrumentColdFunctionOnly</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a31247ee16228c7275b1843cb003c534a">skipPGOGen</a>.</p>

</div>
</div>

### PreInlineThreshold {#a8e49230c36c2f00ec7d045bffbdf441c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; PreInlineThreshold("preinline-threshold", cl::Hidden, cl::init(75), cl::desc("Control the amount of inlining in pre-instrumentation inliner " "(default = 75)"))</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### RunNewGVN {#a174f40086d77810c7576da30090256c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RunNewGVN("enable-newgvn", cl::init(false), cl::Hidden, cl::desc("Run the NewGVN pass"))</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>.</p>

</div>
</div>

### RunPartialInlining {#a556f58c089a2d5bf23d908286807155d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RunPartialInlining("enable-partial-inlining", cl::init(false), cl::Hidden, cl::desc("Run Partial inlining pass"))</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2832cb00a6c94208b4a06696eeeabf99">llvm::PassBuilder::buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### UseCtxProfile {#a5ac99641888d5b06352c629f38485394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;std::string&gt; UseCtxProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### UseInlineAdvisor {#aecf596ddba11c5164c5952d85904091a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; InliningAdvisorMode &gt; UseInlineAdvisor("enable-ml-inliner", cl::init(InliningAdvisorMode::Default), cl::Hidden, cl::desc("Enable ML policy for inliner. Currently trained for -Oz only"), cl::values(clEnumValN(InliningAdvisorMode::Default, "default", "Heuristics-based inliner version"), clEnumValN(InliningAdvisorMode::Development, "development", "Use development mode (runtime-loadable model)"), clEnumValN(InliningAdvisorMode::Release, "release", "Use release mode (AOT-compiled model)")))</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>.</p>

</div>
</div>

### UseLoopVersioningLICM {#abb43570bd79eef6f5949838628de6dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseLoopVersioningLICM("enable-loop-versioning-licm", cl::init(false), cl::Hidden, cl::desc("Enable the experimental Loop Versioning LICM pass"))</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
