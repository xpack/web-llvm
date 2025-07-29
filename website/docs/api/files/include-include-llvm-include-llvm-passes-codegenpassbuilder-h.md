---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CodeGenPassBuilder.h` File

<p>Interfaces for producing common pass manager configurations. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scopednoaliasaa-h">llvm/Analysis/ScopedNoAliasAA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">llvm/CodeGen/AssignmentTrackingAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callbrprepare-h">llvm/CodeGen/CallBrPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegenprepare-h">llvm/CodeGen/CodeGenPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/deadmachineinstructionelim-h">llvm/CodeGen/DeadMachineInstructionElim.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfehprepare-h">llvm/CodeGen/DwarfEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/earlyifconversion-h">llvm/CodeGen/EarlyIfConversion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargedivrem-h">llvm/CodeGen/ExpandLargeDivRem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargefpconvert-h">llvm/CodeGen/ExpandLargeFpConvert.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandmemcmp-h">llvm/CodeGen/ExpandMemCmp.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandreductions-h">llvm/CodeGen/ExpandReductions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/finalizeisel-h">llvm/CodeGen/FinalizeISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmerge-h">llvm/CodeGen/GlobalMerge.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h">llvm/CodeGen/GlobalMergeFunctions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectbrexpand-h">llvm/CodeGen/IndirectBrExpand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/interleavedaccess-h">llvm/CodeGen/InterleavedAccess.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/interleavedloadcombine-h">llvm/CodeGen/InterleavedLoadCombine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/jmcinstrumenter-h">llvm/CodeGen/JMCInstrumenter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/localstackslotallocation-h">llvm/CodeGen/LocalStackSlotAllocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/loweremutls-h">llvm/CodeGen/LowerEmuTLS.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/mirprinter-h">llvm/CodeGen/MIRPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinecse-h">llvm/CodeGen/MachineCSE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionanalysis-h">llvm/CodeGen/MachineFunctionAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinelicm-h">llvm/CodeGen/MachineLICM.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassmanager-h">llvm/CodeGen/MachinePassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineverifier-h">llvm/CodeGen/MachineVerifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/optimizephis-h">llvm/CodeGen/OptimizePHIs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/phielimination-h">llvm/CodeGen/PHIElimination.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">llvm/CodeGen/PeepholeOptimizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/preiselintrinsiclowering-h">llvm/CodeGen/PreISelIntrinsicLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocfast-h">llvm/CodeGen/RegAllocFast.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regusageinfocollector-h">llvm/CodeGen/RegUsageInfoCollector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regusageinfopropagate-h">llvm/CodeGen/RegUsageInfoPropagate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">llvm/CodeGen/RegisterUsageInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/replacewithveclib-h">llvm/CodeGen/ReplaceWithVeclib.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/safestack-h">llvm/CodeGen/SafeStack.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectoptimize-h">llvm/CodeGen/SelectOptimize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/shadowstackgclowering-h">llvm/CodeGen/ShadowStackGCLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sjljehprepare-h">llvm/CodeGen/SjLjEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackcoloring-h">llvm/CodeGen/StackColoring.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">llvm/CodeGen/StackProtector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplication-h">llvm/CodeGen/TailDuplication.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/twoaddressinstructionpass-h">llvm/CodeGen/TwoAddressInstructionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/unreachableblockelim-h">llvm/CodeGen/UnreachableBlockElim.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/wasmehprepare-h">llvm/CodeGen/WasmEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/winehprepare-h">llvm/CodeGen/WinEHPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/irprinter/irprintingpasses-h">llvm/IRPrinter/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/cgpassbuilderoption-h">llvm/Target/CGPassBuilderOption.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/cfguard-h">llvm/Transforms/CFGuard.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/constanthoisting-h">llvm/Transforms/Scalar/ConstantHoisting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopstrengthreduce-h">llvm/Transforms/Scalar/LoopStrengthReduce.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerconstantintrinsics-h">llvm/Transforms/Scalar/LowerConstantIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/mergeicmps-h">llvm/Transforms/Scalar/MergeICmps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/partiallyinlinelibcalls-h">llvm/Transforms/Scalar/PartiallyInlineLibCalls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizemaskedmemintrin-h">llvm/Transforms/Scalar/ScalarizeMaskedMemIntrin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/entryexitinstrumenter-h">llvm/Transforms/Utils/EntryExitInstrumenter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerinvoke-h">llvm/Transforms/Utils/LowerInvoke.h</a>"
#include &lt;cassert&gt;
#include &lt;type_traits&gt;
#include &lt;utility&gt;
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

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder">CodeGenPassBuilder&lt;DerivedT, TargetMachineT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides access to building LLVM's passes. <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0525cb3566bdbf29dc3342e8843b661">DUMMY_FUNCTION_PASS</a>(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7780c5ffce7e036a2c2175fae760e1b9">DUMMY_MACHINE_MODULE_PASS</a>(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd2f29317c7707a12411b947e2dfcc2">DUMMY_MACHINE_FUNCTION_PASS</a>(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
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

<p>Interfaces for producing common pass manager configurations.</p>

<div class="doxySectionDef">

## Macro Definitions

### DUMMY\_FUNCTION\_PASS {#aa0525cb3566bdbf29dc3342e8843b661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DUMMY_FUNCTION_PASS(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  struct <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a> : public PassInfoMixin&lt;<a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&gt; {                         \
    template &lt;typename... Ts&gt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>(Ts &amp;&amp;...) {}                           \
    PreservedAnalyses run(Function &amp;, FunctionAnalysisManager &amp;) {             \
      return PreservedAnalyses::all();                                         \
    }                                                                          \
  };
</div>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### DUMMY\_MACHINE\_FUNCTION\_PASS {#afbd2f29317c7707a12411b947e2dfcc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DUMMY_MACHINE_FUNCTION_PASS(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  struct <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a> : public PassInfoMixin&lt;<a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&gt; {                         \
    template &lt;typename... Ts&gt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>(Ts &amp;&amp;...) {}                           \
    PreservedAnalyses run(MachineFunction &amp;,                                   \
                          MachineFunctionAnalysisManager &amp;) {                  \
      return PreservedAnalyses::all();                                         \
    }                                                                          \
  };
</div>
</dd>
</dl>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### DUMMY\_MACHINE\_MODULE\_PASS {#a7780c5ffce7e036a2c2175fae760e1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DUMMY_MACHINE_MODULE_PASS(NAME, PASS_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  struct <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a> : public PassInfoMixin&lt;<a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&gt; {                         \
    template &lt;typename... Ts&gt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>(Ts &amp;&amp;...) {}                           \
    PreservedAnalyses run(<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a> &amp;, ModuleAnalysisManager &amp;) {                 \
      return PreservedAnalyses::all();                                         \
    }                                                                          \
  };
</div>
</dd>
</dl>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
