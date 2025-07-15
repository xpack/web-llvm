---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/passes/passbuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PassBuilder.cpp` File Reference

<p>This file provides the implementation of the <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> based on our static pass registry as well as related functionality. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysisevaluator-h">llvm/Analysis/AliasAnalysisEvaluator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">llvm/Analysis/AliasSetTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">llvm/Analysis/CFGPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgsccprinter-h">llvm/Analysis/CFGSCCPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">llvm/Analysis/CallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callprinter-h">llvm/Analysis/CallPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/costmodel-h">llvm/Analysis/CostModel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">llvm/Analysis/CtxProfAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cycleanalysis-h">llvm/Analysis/CycleAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">llvm/Analysis/DDG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddgprinter-h">llvm/Analysis/DDGPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">llvm/Analysis/DXILMetadataAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/delinearization-h">llvm/Analysis/Delinearization.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">llvm/Analysis/DemandedBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">llvm/Analysis/DependenceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domprinter-h">llvm/Analysis/DomPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dominancefrontier-h">llvm/Analysis/DominanceFrontier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">llvm/Analysis/FunctionPropertiesAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">llvm/Analysis/IVUsers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinesizeestimatoranalysis-h">llvm/Analysis/InlineSizeEstimatorAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instcount-h">llvm/Analysis/InstCount.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">llvm/Analysis/LastRunTrackingAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyvalueinfo-h">llvm/Analysis/LazyValueInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lint-h">llvm/Analysis/Lint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">llvm/Analysis/LoopCacheAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">llvm/Analysis/LoopNestAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memderefprinter-h">llvm/Analysis/MemDerefPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">llvm/Analysis/MemoryDependenceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/moduledebuginfoprinter-h">llvm/Analysis/ModuleDebugInfoPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/modulesummaryanalysis-h">llvm/Analysis/ModuleSummaryAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">llvm/Analysis/ObjCARCAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phivalues-h">llvm/Analysis/PhiValues.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/postdominators-h">llvm/Analysis/PostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionaliasanalysis-h">llvm/Analysis/ScalarEvolutionAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scopednoaliasaa-h">llvm/Analysis/ScopedNoAliasAA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">llvm/Analysis/StackLifetime.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">llvm/Analysis/StackSafetyAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/structuralhash-h">llvm/Analysis/StructuralHash.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">llvm/Analysis/UniformityAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">llvm/CodeGen/AssignmentTrackingAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/atomicexpand-h">llvm/CodeGen/AtomicExpand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callbrprepare-h">llvm/CodeGen/CallBrPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegenprepare-h">llvm/CodeGen/CodeGenPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/complexdeinterleavingpass-h">llvm/CodeGen/ComplexDeinterleavingPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/deadmachineinstructionelim-h">llvm/CodeGen/DeadMachineInstructionElim.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfehprepare-h">llvm/CodeGen/DwarfEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/earlyifconversion-h">llvm/CodeGen/EarlyIfConversion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/edgebundles-h">llvm/CodeGen/EdgeBundles.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargedivrem-h">llvm/CodeGen/ExpandLargeDivRem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargefpconvert-h">llvm/CodeGen/ExpandLargeFpConvert.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandmemcmp-h">llvm/CodeGen/ExpandMemCmp.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/finalizeisel-h">llvm/CodeGen/FinalizeISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmerge-h">llvm/CodeGen/GlobalMerge.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h">llvm/CodeGen/GlobalMergeFunctions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/hardwareloops-h">llvm/CodeGen/HardwareLoops.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectbrexpand-h">llvm/CodeGen/IndirectBrExpand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/interleavedaccess-h">llvm/CodeGen/InterleavedAccess.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/interleavedloadcombine-h">llvm/CodeGen/InterleavedLoadCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/jmcinstrumenter-h">llvm/CodeGen/JMCInstrumenter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">llvm/CodeGen/LiveDebugVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livestacks-h">llvm/CodeGen/LiveStacks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/localstackslotallocation-h">llvm/CodeGen/LocalStackSlotAllocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/loweremutls-h">llvm/CodeGen/LowerEmuTLS.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/mirprinter-h">llvm/CodeGen/MIRPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinecse-h">llvm/CodeGen/MachineCSE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionanalysis-h">llvm/CodeGen/MachineFunctionAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinelicm-h">llvm/CodeGen/MachineLICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassmanager-h">llvm/CodeGen/MachinePassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">llvm/CodeGen/MachinePostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">llvm/CodeGen/MachineTraceMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineverifier-h">llvm/CodeGen/MachineVerifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/optimizephis-h">llvm/CodeGen/OptimizePHIs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/phielimination-h">llvm/CodeGen/PHIElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">llvm/CodeGen/PeepholeOptimizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/preiselintrinsiclowering-h">llvm/CodeGen/PreISelIntrinsicLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocfast-h">llvm/CodeGen/RegAllocFast.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regusageinfocollector-h">llvm/CodeGen/RegUsageInfoCollector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regusageinfopropagate-h">llvm/CodeGen/RegUsageInfoPropagate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">llvm/CodeGen/RegisterUsageInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/safestack-h">llvm/CodeGen/SafeStack.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectoptimize-h">llvm/CodeGen/SelectOptimize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/shadowstackgclowering-h">llvm/CodeGen/ShadowStackGCLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sjljehprepare-h">llvm/CodeGen/SjLjEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">llvm/CodeGen/SlotIndexes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">llvm/CodeGen/SpillPlacement.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackcoloring-h">llvm/CodeGen/StackColoring.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">llvm/CodeGen/StackProtector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplication-h">llvm/CodeGen/TailDuplication.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/twoaddressinstructionpass-h">llvm/CodeGen/TwoAddressInstructionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/typepromotion-h">llvm/CodeGen/TypePromotion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/wasmehprepare-h">llvm/CodeGen/WasmEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/winehprepare-h">llvm/CodeGen/WinEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/printpasses-h">llvm/IR/PrintPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/safepointirverifier-h">llvm/IR/SafepointIRVerifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/irprinter/irprintingpasses-h">llvm/IRPrinter/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/optimizationlevel-h">llvm/Passes/OptimizationLevel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">llvm/Support/Regex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/aggressiveinstcombine/aggressiveinstcombine-h">llvm/Transforms/AggressiveInstCombine/AggressiveInstCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/cfguard-h">llvm/Transforms/CFGuard.h</a>"
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
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/blockextractor-h">llvm/Transforms/IPO/BlockExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/calledvaluepropagation-h">llvm/Transforms/IPO/CalledValuePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/constantmerge-h">llvm/Transforms/IPO/ConstantMerge.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/crossdsocfi-h">llvm/Transforms/IPO/CrossDSOCFI.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">llvm/Transforms/IPO/DeadArgumentElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/elimavailextern-h">llvm/Transforms/IPO/ElimAvailExtern.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/embedbitcodepass-h">llvm/Transforms/IPO/EmbedBitcodePass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/expandvariadics-h">llvm/Transforms/IPO/ExpandVariadics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">llvm/Transforms/IPO/ForceFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionattrs-h">llvm/Transforms/IPO/FunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">llvm/Transforms/IPO/FunctionImport.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">llvm/Transforms/IPO/GlobalDCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globalopt-h">llvm/Transforms/IPO/GlobalOpt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globalsplit-h">llvm/Transforms/IPO/GlobalSplit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/hotcoldsplitting-h">llvm/Transforms/IPO/HotColdSplitting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">llvm/Transforms/IPO/IROutliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inferfunctionattrs-h">llvm/Transforms/IPO/InferFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">llvm/Transforms/IPO/Inliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/internalize-h">llvm/Transforms/IPO/Internalize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/loopextractor-h">llvm/Transforms/IPO/LoopExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">llvm/Transforms/IPO/LowerTypeTests.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">llvm/Transforms/IPO/MemProfContextDisambiguation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/mergefunctions-h">llvm/Transforms/IPO/MergeFunctions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">llvm/Transforms/IPO/ModuleInliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">llvm/Transforms/IPO/OpenMPOpt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/partialinlining-h">llvm/Transforms/IPO/PartialInlining.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">llvm/Transforms/IPO/SCCP.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofile-h">llvm/Transforms/IPO/SampleProfile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofileprobe-h">llvm/Transforms/IPO/SampleProfileProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/stripdeadprototypes-h">llvm/Transforms/IPO/StripDeadPrototypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/stripsymbols-h">llvm/Transforms/IPO/StripSymbols.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombine-h">llvm/Transforms/InstCombine/InstCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizer-h">llvm/Transforms/Instrumentation/AddressSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/boundschecking-h">llvm/Transforms/Instrumentation/BoundsChecking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cgprofile-h">llvm/Transforms/Instrumentation/CGProfile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/controlheightreduction-h">llvm/Transforms/Instrumentation/ControlHeightReduction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/dataflowsanitizer-h">llvm/Transforms/Instrumentation/DataFlowSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/gcovprofiler-h">llvm/Transforms/Instrumentation/GCOVProfiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/hwaddresssanitizer-h">llvm/Transforms/Instrumentation/HWAddressSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/instrorderfile-h">llvm/Transforms/Instrumentation/InstrOrderFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/instrprofiling-h">llvm/Transforms/Instrumentation/InstrProfiling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/kcfi-h">llvm/Transforms/Instrumentation/KCFI.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/lowerallowcheckpass-h">llvm/Transforms/Instrumentation/LowerAllowCheckPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/memprofiler-h">llvm/Transforms/Instrumentation/MemProfiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/memorysanitizer-h">llvm/Transforms/Instrumentation/MemorySanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/numericalstabilitysanitizer-h">llvm/Transforms/Instrumentation/NumericalStabilitySanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoctxprofflattening-h">llvm/Transforms/Instrumentation/PGOCtxProfFlattening.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoctxproflowering-h">llvm/Transforms/Instrumentation/PGOCtxProfLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoforcefunctionattrs-h">llvm/Transforms/Instrumentation/PGOForceFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/pgoinstrumentation-h">llvm/Transforms/Instrumentation/PGOInstrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/realtimesanitizer-h">llvm/Transforms/Instrumentation/RealtimeSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/sanitizerbinarymetadata-h">llvm/Transforms/Instrumentation/SanitizerBinaryMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/sanitizercoverage-h">llvm/Transforms/Instrumentation/SanitizerCoverage.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/threadsanitizer-h">llvm/Transforms/Instrumentation/ThreadSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/typesanitizer-h">llvm/Transforms/Instrumentation/TypeSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/objcarc-h">llvm/Transforms/ObjCARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/adce-h">llvm/Transforms/Scalar/ADCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/alignmentfromassumptions-h">llvm/Transforms/Scalar/AlignmentFromAssumptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/annotationremarks-h">llvm/Transforms/Scalar/AnnotationRemarks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/bdce-h">llvm/Transforms/Scalar/BDCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/callsitesplitting-h">llvm/Transforms/Scalar/CallSiteSplitting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/constanthoisting-h">llvm/Transforms/Scalar/ConstantHoisting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/constraintelimination-h">llvm/Transforms/Scalar/ConstraintElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/correlatedvaluepropagation-h">llvm/Transforms/Scalar/CorrelatedValuePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/dce-h">llvm/Transforms/Scalar/DCE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/dfajumpthreading-h">llvm/Transforms/Scalar/DFAJumpThreading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/deadstoreelimination-h">llvm/Transforms/Scalar/DeadStoreElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/divrempairs-h">llvm/Transforms/Scalar/DivRemPairs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/earlycse-h">llvm/Transforms/Scalar/EarlyCSE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/flattencfg-h">llvm/Transforms/Scalar/FlattenCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/float2int-h">llvm/Transforms/Scalar/Float2Int.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">llvm/Transforms/Scalar/GVN.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/guardwidening-h">llvm/Transforms/Scalar/GuardWidening.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/ivusersprinter-h">llvm/Transforms/Scalar/IVUsersPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/indvarsimplify-h">llvm/Transforms/Scalar/IndVarSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/inductiverangecheckelimination-h">llvm/Transforms/Scalar/InductiveRangeCheckElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/inferaddressspaces-h">llvm/Transforms/Scalar/InferAddressSpaces.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/inferalignment-h">llvm/Transforms/Scalar/InferAlignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/instsimplifypass-h">llvm/Transforms/Scalar/InstSimplifyPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/jumptabletoswitch-h">llvm/Transforms/Scalar/JumpTableToSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/jumpthreading-h">llvm/Transforms/Scalar/JumpThreading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/licm-h">llvm/Transforms/Scalar/LICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopaccessanalysisprinter-h">llvm/Transforms/Scalar/LoopAccessAnalysisPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopboundsplit-h">llvm/Transforms/Scalar/LoopBoundSplit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopdataprefetch-h">llvm/Transforms/Scalar/LoopDataPrefetch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopdeletion-h">llvm/Transforms/Scalar/LoopDeletion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopdistribute-h">llvm/Transforms/Scalar/LoopDistribute.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopflatten-h">llvm/Transforms/Scalar/LoopFlatten.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopfuse-h">llvm/Transforms/Scalar/LoopFuse.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopidiomrecognize-h">llvm/Transforms/Scalar/LoopIdiomRecognize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">llvm/Transforms/Scalar/LoopInstSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinterchange-h">llvm/Transforms/Scalar/LoopInterchange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looploadelimination-h">llvm/Transforms/Scalar/LoopLoadElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppredication-h">llvm/Transforms/Scalar/LoopPredication.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looprotation-h">llvm/Transforms/Scalar/LoopRotation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsimplifycfg-h">llvm/Transforms/Scalar/LoopSimplifyCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">llvm/Transforms/Scalar/LoopSink.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopstrengthreduce-h">llvm/Transforms/Scalar/LoopStrengthReduce.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looptermfold-h">llvm/Transforms/Scalar/LoopTermFold.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">llvm/Transforms/Scalar/LoopUnrollAndJamPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">llvm/Transforms/Scalar/LoopUnrollPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopversioninglicm-h">llvm/Transforms/Scalar/LoopVersioningLICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loweratomicpass-h">llvm/Transforms/Scalar/LowerAtomicPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerconstantintrinsics-h">llvm/Transforms/Scalar/LowerConstantIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerexpectintrinsic-h">llvm/Transforms/Scalar/LowerExpectIntrinsic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerguardintrinsic-h">llvm/Transforms/Scalar/LowerGuardIntrinsic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowermatrixintrinsics-h">llvm/Transforms/Scalar/LowerMatrixIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerwidenablecondition-h">llvm/Transforms/Scalar/LowerWidenableCondition.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/makeguardsexplicit-h">llvm/Transforms/Scalar/MakeGuardsExplicit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">llvm/Transforms/Scalar/MemCpyOptimizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/mergeicmps-h">llvm/Transforms/Scalar/MergeICmps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/mergedloadstoremotion-h">llvm/Transforms/Scalar/MergedLoadStoreMotion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/naryreassociate-h">llvm/Transforms/Scalar/NaryReassociate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/newgvn-h">llvm/Transforms/Scalar/NewGVN.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/partiallyinlinelibcalls-h">llvm/Transforms/Scalar/PartiallyInlineLibCalls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/placesafepoints-h">llvm/Transforms/Scalar/PlaceSafepoints.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">llvm/Transforms/Scalar/Reassociate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reg2mem-h">llvm/Transforms/Scalar/Reg2Mem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/rewritestatepointsforgc-h">llvm/Transforms/Scalar/RewriteStatepointsForGC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/sccp-h">llvm/Transforms/Scalar/SCCP.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/sroa-h">llvm/Transforms/Scalar/SROA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizemaskedmemintrin-h">llvm/Transforms/Scalar/ScalarizeMaskedMemIntrin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">llvm/Transforms/Scalar/Scalarizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/separateconstoffsetfromgep-h">llvm/Transforms/Scalar/SeparateConstOffsetFromGEP.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">llvm/Transforms/Scalar/SimpleLoopUnswitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simplifycfg-h">llvm/Transforms/Scalar/SimplifyCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/sink-h">llvm/Transforms/Scalar/Sink.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/speculativeexecution-h">llvm/Transforms/Scalar/SpeculativeExecution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/straightlinestrengthreduce-h">llvm/Transforms/Scalar/StraightLineStrengthReduce.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/structurizecfg-h">llvm/Transforms/Scalar/StructurizeCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/tailrecursionelimination-h">llvm/Transforms/Scalar/TailRecursionElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/warnmissedtransforms-h">llvm/Transforms/Scalar/WarnMissedTransforms.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/adddiscriminators-h">llvm/Transforms/Utils/AddDiscriminators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/assumebundlebuilder-h">llvm/Transforms/Utils/AssumeBundleBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/breakcriticaledges-h">llvm/Transforms/Utils/BreakCriticalEdges.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/canonicalizealiases-h">llvm/Transforms/Utils/CanonicalizeAliases.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/canonicalizefreezeinloops-h">llvm/Transforms/Utils/CanonicalizeFreezeInLoops.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/countvisits-h">llvm/Transforms/Utils/CountVisits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/dxilupgrade-h">llvm/Transforms/Utils/DXILUpgrade.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">llvm/Transforms/Utils/Debugify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/entryexitinstrumenter-h">llvm/Transforms/Utils/EntryExitInstrumenter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/extrapassmanager-h">llvm/Transforms/Utils/ExtraPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/fixirreducible-h">llvm/Transforms/Utils/FixIrreducible.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/helloworld-h">llvm/Transforms/Utils/HelloWorld.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/irnormalizer-h">llvm/Transforms/Utils/IRNormalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/injecttlimappings-h">llvm/Transforms/Utils/InjectTLIMappings.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instructionnamer-h">llvm/Transforms/Utils/InstructionNamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lcssa-h">llvm/Transforms/Utils/LCSSA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/libcallsshrinkwrap-h">llvm/Transforms/Utils/LibCallsShrinkWrap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopsimplify-h">llvm/Transforms/Utils/LoopSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">llvm/Transforms/Utils/LoopVersioning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerglobaldtors-h">llvm/Transforms/Utils/LowerGlobalDtors.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerifunc-h">llvm/Transforms/Utils/LowerIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerinvoke-h">llvm/Transforms/Utils/LowerInvoke.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerswitch-h">llvm/Transforms/Utils/LowerSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/mem2reg-h">llvm/Transforms/Utils/Mem2Reg.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/metarenamer-h">llvm/Transforms/Utils/MetaRenamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moveautoinit-h">llvm/Transforms/Utils/MoveAutoInit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/nameanonglobals-h">llvm/Transforms/Utils/NameAnonGlobals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/predicateinfo-h">llvm/Transforms/Utils/PredicateInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/rellookuptableconverter-h">llvm/Transforms/Utils/RelLookupTableConverter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/stripgcrelocates-h">llvm/Transforms/Utils/StripGCRelocates.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/stripnonlinetabledebuginfo-h">llvm/Transforms/Utils/StripNonLineTableDebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">llvm/Transforms/Utils/SymbolRewriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unifyfunctionexitnodes-h">llvm/Transforms/Utils/UnifyFunctionExitNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unifyloopexits-h">llvm/Transforms/Utils/UnifyLoopExits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loadstorevectorizer-h">llvm/Transforms/Vectorize/LoadStoreVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopidiomvectorize-h">llvm/Transforms/Vectorize/LoopIdiomVectorize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">llvm/Transforms/Vectorize/LoopVectorize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/slpvectorizer-h">llvm/Transforms/Vectorize/SLPVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-h">llvm/Transforms/Vectorize/SandboxVectorizer/SandboxVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/vectorcombine-h">llvm/Transforms/Vectorize/VectorCombine.h</a>"
#include &lt;optional&gt;
#include "PassRegistry.def"
#include "llvm/Passes/MachinePassRegistry.def"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-">anonymous{PassBuilder.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggercrashmodulepass">TriggerCrashModulePass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggercrashfunctionpass">TriggerCrashFunctionPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass">TriggerVerifierErrorPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/requireallmachinefunctionpropertiespass">RequireAllMachineFunctionPropertiesPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; bool, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f0170bee89e1dc229f2710a4728b0b">parseFunctionPipelineName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca27e51919faf466ef7adbf6a2a2d7e">parseDevirtPassName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7557cb4189c1a1f2b5c9bd250f2189f1">startsWithDefaultPipelineAliasPrefix</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether a pass name starts with a valid prefix for a default pipeline alias. <a href="#a7557cb4189c1a1f2b5c9bd250f2189f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassManagerT, typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a> (StringRef Name, CallbacksT &amp;Callbacks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether registered callbacks will accept a given pass name. <a href="#a39083de9ca15e7350b75526552814775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26572aa6efaea4ae6ce610c3b93f0210">isModulePassName</a> (StringRef Name, CallbacksT &amp;Callbacks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac53000397de89cf36fbf956d1e18a44">isCGSCCPassName</a> (StringRef Name, CallbacksT &amp;Callbacks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5234ac115ac4f2c23622b4eede40d78">isFunctionPassName</a> (StringRef Name, CallbacksT &amp;Callbacks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83144269c5f447f53e524b0b5633c80a">isMachineFunctionPassName</a> (StringRef Name, CallbacksT &amp;Callbacks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8130b07a44ca5c11ae1aac80d5129a7a">isLoopNestPassName</a> (StringRef Name, CallbacksT &amp;Callbacks, bool &amp;UseMemorySSA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallbacksT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa54f2a3ed5acad7fd2b7b55141319525">isLoopPassName</a> (StringRef Name, CallbacksT &amp;Callbacks, bool &amp;UseMemorySSA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a> (StringRef PassName, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69226e2a3cc621d634b8c3d3e0023b13">printPassName</a> (StringRef PassName, StringRef Params, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae700d6ec154eef82b2e319039943d84e">DefaultAliasRegex</a>("^(default|thinlto-pre-link|thinlto|lto-pre-link|lto)<(O[0123sz])>$")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  MAM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  CGAM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  FAM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  MFAM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  LAM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5381422a21b46a82cd1d97cab202e193">MACHINE_MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697ee2ac392dc5138226c3ecdc3911b">MODULE_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8c394c2bc847b6edfaa8198479504">CGSCC_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65a1f20815d319aaf747edf98f21eb">CGSCC_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a60182eceb2044f9f954d467c0b55">CGSCC_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b54cc7175a3db7762198844fd930eb">LOOPNEST_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8505689e565a292578d3caf1ba4485">LOOP_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5381422a21b46a82cd1d97cab202e193">MACHINE_MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
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

### callbacksAcceptPassName() {#a39083de9ca15e7350b75526552814775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassManagerT, typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool callbacksAcceptPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks)</td>
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

<p>Tests whether registered callbacks will accept a given pass name.</p>


<p>When parsing a pipeline text, the type of the outermost pipeline may be omitted, in which case the type is automatically determined from the first pass name in the text. This may be a name that is handled through one of the callbacks. We check this through the oridinary parsing callbacks by setting up a dummy <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> in order to not force the client to also handle this type of query.</p>


<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aac53000397de89cf36fbf956d1e18a44">isCGSCCPassName</a>, <a href="#ac5234ac115ac4f2c23622b4eede40d78">isFunctionPassName</a>, <a href="#a8130b07a44ca5c11ae1aac80d5129a7a">isLoopNestPassName</a>, <a href="#aa54f2a3ed5acad7fd2b7b55141319525">isLoopPassName</a>, <a href="#a83144269c5f447f53e524b0b5633c80a">isMachineFunctionPassName</a> and <a href="#a26572aa6efaea4ae6ce610c3b93f0210">isModulePassName</a>.</p>

</div>
</div>

### isCGSCCPassName() {#aac53000397de89cf36fbf956d1e18a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCGSCCPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks)</td>
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



<p>Definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a> and <a href="#a5ca27e51919faf466ef7adbf6a2a2d7e">parseDevirtPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a581197bc2dbbef326892f5ff08761f54">llvm::PassBuilder::parsePassPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### isFunctionPassName() {#ac5234ac115ac4f2c23622b4eede40d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFunctionPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks)</td>
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



<p>Definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ac3231081094bc7fdda779c6b73f9f706">llvm::PassBuilder::parsePassPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### isLoopNestPassName() {#a8130b07a44ca5c11ae1aac80d5129a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoopNestPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks, bool &amp; UseMemorySSA)</td>
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



<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a0d95457b7af7593624ad31405198d59d">llvm::PassBuilder::checkParametrizedPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### isLoopPassName() {#aa54f2a3ed5acad7fd2b7b55141319525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoopPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks, bool &amp; UseMemorySSA)</td>
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



<p>Definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a> and <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a0d95457b7af7593624ad31405198d59d">llvm::PassBuilder::checkParametrizedPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### isMachineFunctionPassName() {#a83144269c5f447f53e524b0b5633c80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMachineFunctionPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks)</td>
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



<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### isModulePassName() {#a26572aa6efaea4ae6ce610c3b93f0210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallbacksT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isModulePassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, CallbacksT &amp; Callbacks)</td>
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



<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a39083de9ca15e7350b75526552814775">callbacksAcceptPassName</a>, <a href="#ae700d6ec154eef82b2e319039943d84e">DefaultAliasRegex</a> and <a href="#a7557cb4189c1a1f2b5c9bd250f2189f1">startsWithDefaultPipelineAliasPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>.</p>

</div>
</div>

### parseDevirtPassName() {#a5ca27e51919faf466ef7adbf6a2a2d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; parseDevirtPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="#aac53000397de89cf36fbf956d1e18a44">isCGSCCPassName</a>.</p>

</div>
</div>

### parseFunctionPipelineName() {#aa7f0170bee89e1dc229f2710a4728b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; bool, bool &gt; &gt; parseFunctionPipelineName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseOptLevel() {#a9e4f6112c778d883860155c39c4d3594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; OptimizationLevel &gt; parseOptLevel (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#acfab17afad8d19eb90de02e684900ccd">llvm::OptimizationLevel::O1</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a9c0836ff9219a0b737a11979991c3389">llvm::OptimizationLevel::O2</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a73679792a87ec44543a1cc09a5d8c3cc">llvm::OptimizationLevel::Os</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a1e916712888d6a2d3952834c126460e7">llvm::OptimizationLevel::Oz</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af05832a87891b7d9d07bce3c339bc934">anonymous{PassBuilder.cpp}::parseFunctionSimplificationPipelineOptions</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### printPassName() {#aad325f3a872ff970403f3cdac458a6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 2401 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### printPassName() {#a69226e2a3cc621d634b8c3d3e0023b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Params, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 2404 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### startsWithDefaultPipelineAliasPrefix() {#a7557cb4189c1a1f2b5c9bd250f2189f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool startsWithDefaultPipelineAliasPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Tests whether a pass name starts with a valid prefix for a default pipeline alias.</p>

<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a26572aa6efaea4ae6ce610c3b93f0210">isModulePassName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefaultAliasRegex {#ae700d6ec154eef82b2e319039943d84e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Regex DefaultAliasRegex("^(default|thinlto-pre-link|thinlto|lto-pre-link|lto)&lt;(O[0123sz])&gt;$")</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a26572aa6efaea4ae6ce610c3b93f0210">isModulePassName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  CGAM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;" || Name == "invalidate&lt;" NAME "&gt;")           \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1485 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;") {                                           \
    CGPM.addPass(RequireAnalysisPass&lt;                                          \
                 std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;,               \
                 LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;,    \
                 CGSCCUpdateResult &amp;&gt;());                                      \
    return Error::success();                                                   \
  }                                                                            \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "invalidate&lt;" NAME "&gt;") {                                        \
    CGPM.addPass(InvalidateAnalysisPass&lt;                                       \
                 std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;());           \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2439 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_ANALYSIS {#a7ee8c394c2bc847b6edfaa8198479504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1479 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MPM.addPass(createModuleToPostOrderCGSCCPassAdaptor(CREATE_PASS));         \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    CGPM.addPass(CREATE_PASS);                                                 \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1860 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2430 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS {#aab65a1f20815d319aaf747edf98f21eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME))                      \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    MPM.addPass(                                                               \
        createModuleToPostOrderCGSCCPassAdaptor(CREATE_PASS(Params.get())));   \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    CGPM.addPass(CREATE_PASS(Params.get()));                                   \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2434 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### CGSCC\_PASS\_WITH\_PARAMS {#a594a60182eceb2044f9f954d467c0b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CGSCC_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    AA.registerFunctionAnalysis&lt;                                               \
        std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;();                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 2161 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2456 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  FAM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;" || Name == "invalidate&lt;" NAME "&gt;")           \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;") {                                           \
    FPM.addPass(                                                               \
        RequireAnalysisPass&lt;                                                   \
            std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;, Function&gt;());      \
    return Error::success();                                                   \
  }                                                                            \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "invalidate&lt;" NAME "&gt;") {                                        \
    FPM.addPass(InvalidateAnalysisPass&lt;                                        \
                std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;());            \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1994 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2452 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MPM.addPass(createModuleToFunctionPassAdaptor(CREATE_PASS));               \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    CGPM.addPass(createCGSCCToFunctionPassAdaptor(CREATE_PASS));               \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1886 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    FPM.addPass(CREATE_PASS);                                                  \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2443 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME))                      \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    MPM.addPass(createModuleToFunctionPassAdaptor(CREATE_PASS(Params.get()))); \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    CGPM.addPass(createCGSCCToFunctionPassAdaptor(CREATE_PASS(Params.get()))); \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1891 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    FPM.addPass(CREATE_PASS(Params.get()));                                    \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1986 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2447 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  LAM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;" || Name == "invalidate&lt;" NAME "&gt;")           \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1573 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;") {                                           \
    LPM.addPass(RequireAnalysisPass&lt;                                           \
                std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;, Loop,          \
                LoopAnalysisManager, LoopStandardAnalysisResults &amp;,            \
                LPMUpdater &amp;&gt;());                                              \
    return Error::success();                                                   \
  }                                                                            \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "invalidate&lt;" NAME "&gt;") {                                        \
    LPM.addPass(InvalidateAnalysisPass&lt;                                        \
                std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;());            \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2084 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2473 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MPM.addPass(createModuleToFunctionPassAdaptor(                             \
        createFunctionToLoopPassAdaptor(CREATE_PASS, false, false)));          \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    CGPM.addPass(createCGSCCToFunctionPassAdaptor(                             \
        createFunctionToLoopPassAdaptor(CREATE_PASS, false, false)));          \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    FPM.addPass(createFunctionToLoopPassAdaptor(CREATE_PASS, false, false));   \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2015 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    LPM.addPass(CREATE_PASS);                                                  \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2071 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2464 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME))                      \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    MPM.addPass(                                                               \
        createModuleToFunctionPassAdaptor(createFunctionToLoopPassAdaptor(     \
            CREATE_PASS(Params.get()), false, false)));                        \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    CGPM.addPass(                                                              \
        createCGSCCToFunctionPassAdaptor(createFunctionToLoopPassAdaptor(      \
            CREATE_PASS(Params.get()), false, false)));                        \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1911 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    FPM.addPass(createFunctionToLoopPassAdaptor(CREATE_PASS(Params.get()),     \
                                                false, false));                \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2020 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    LPM.addPass(CREATE_PASS(Params.get()));                                    \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2076 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2468 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOP\_PASS\_WITH\_PARAMS {#a9c8505689e565a292578d3caf1ba4485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1549 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MPM.addPass(createModuleToFunctionPassAdaptor(                             \
        createFunctionToLoopPassAdaptor(CREATE_PASS, false, false)));          \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    CGPM.addPass(createCGSCCToFunctionPassAdaptor(                             \
        createFunctionToLoopPassAdaptor(CREATE_PASS, false, false)));          \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    FPM.addPass(createFunctionToLoopPassAdaptor(CREATE_PASS, false, false));   \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2010 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    LPM.addPass(CREATE_PASS);                                                  \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2460 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### LOOPNEST\_PASS {#a05b54cc7175a3db7762198844fd930eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOPNEST_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  MFAM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;" || Name == "invalidate&lt;" NAME "&gt;")           \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;") {                                           \
    MFPM.addPass(                                                              \
        RequireAnalysisPass&lt;std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;,    \
                            MachineFunction&gt;());                               \
    return Error::success();                                                   \
  }                                                                            \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "invalidate&lt;" NAME "&gt;") {                                        \
    MFPM.addPass(InvalidateAnalysisPass&lt;                                       \
                 std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;());           \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2132 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MFPM.addPass(CREATE_PASS);                                                 \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2118 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2481 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME))                      \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    MFPM.addPass(CREATE_PASS(Params.get()));                                   \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2124 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_MODULE\_PASS {#a5381422a21b46a82cd1d97cab202e193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MFPM.addPass(CREATE_PASS);                                                 \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MACHINE\_MODULE\_PASS {#a5381422a21b46a82cd1d97cab202e193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2477 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    AA.registerModuleAnalysis&lt;                                                 \
        std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;();                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2426 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ALIAS\_ANALYSIS {#aa697ee2ac392dc5138226c3ecdc3911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  MAM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;" || Name == "invalidate&lt;" NAME "&gt;")           \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1458 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "require&lt;" NAME "&gt;") {                                           \
    MPM.addPass(                                                               \
        RequireAnalysisPass&lt;                                                   \
            std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>&gt;());        \
    return Error::success();                                                   \
  }                                                                            \
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == "invalidate&lt;" NAME "&gt;") {                                        \
    MPM.addPass(InvalidateAnalysisPass&lt;                                        \
                std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;());            \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2422 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME)                                                            \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1452 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    MPM.addPass(CREATE_PASS);                                                  \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2413 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME))                      \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 1455 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (checkParametrizedPassName(Name, NAME)) {                                 \
    auto Params = parsePassParameters(PARSER, Name, NAME);                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params)                                                               \
      return Params.takeError();                                               \
    MPM.addPass(CREATE_PASS(Params.get()));                                    \
    return Error::success();                                                   \
  }
</div>
</dd>
</dl>

<p>Definition at line 1737 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="#aad325f3a872ff970403f3cdac458a6e6">printPassName</a>(NAME, PARAMS, OS);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2417 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
