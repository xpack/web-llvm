---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SelectionDAGISel.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagisel-h">llvm/CodeGen/SelectionDAGISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfg-h">llvm/Analysis/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyblockfrequencyinfo-h">llvm/Analysis/LazyBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">llvm/Analysis/UniformityAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">llvm/CodeGen/AssignmentTrackingAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">llvm/CodeGen/CodeGenCommonISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">llvm/CodeGen/FastISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassregistry-h">llvm/CodeGen/MachinePassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">llvm/CodeGen/SchedulerRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagtargetinfo-h">llvm/CodeGen/SelectionDAGTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">llvm/CodeGen/StackProtector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/swifterrorvaluetracking-h">llvm/CodeGen/SwiftErrorValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/winehfuncinfo-h">llvm/CodeGen/WinEHFuncInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/ehpersonalities-h">llvm/IR/EHPersonalities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsWebAssembly.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/printpasses-h">llvm/IR/PrintPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">llvm/Support/Timer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">llvm/Target/TargetIntrinsicInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;limits&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-selectiondagisel-cpp-">anonymous{SelectionDAGISel.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optlevelchanger">OptLevelChanger</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is used by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> to temporarily override the optimization level on a per-function basis. <a href="/web-llvm/docs/api/classes/llvm/optlevelchanger/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater">ISelUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater">ISelUpdater</a> - helper class to handle updates of the instruction selection graph. <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-selectiondagisel-cpp-/matchscope">MatchScope</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater">MatchStateUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\A DAG update listener to keep the matching state (i.e. <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86b9a266a6b20065efd529aad768608">STATISTIC</a> (NumFastIselFailures, "Number of instructions fast isel failed on")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9805b0bbd8f8390ae9649b189bc0d148">STATISTIC</a> (NumFastIselSuccess, "Number of instructions fast isel selected")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad286fd7c3b789d38d762600a70adecd1">STATISTIC</a> (NumFastIselBlocks, "Number of blocks selected entirely by fast isel")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee452fede10d0fbe5b777015d17a5c3">STATISTIC</a> (NumDAGBlocks, "Number of blocks selected using DAG")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d237256bcb5b26f8dc10aa8212a35d">STATISTIC</a> (NumDAGIselRetries,"Number of times dag isel has to try another path")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b53c2ab01eb828cf84fdd36487c82ce">STATISTIC</a> (NumEntryBlocks, "Number of entry blocks encountered")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d2cbeca32ee1e338c4fe49b4025d42">STATISTIC</a> (NumFastIselFailLowerArguments, "Number of entry blocks where fast isel failed to lower arguments")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc70f4d5f07cada554efd4e2c8386c4">dontUseFastISelFor</a> (const Function &amp;Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292edc681e4846f695d627a99cb1560d">reportFastISelFailure</a> (MachineFunction &amp;MF, OptimizationRemarkEmitter &amp;ORE, OptimizationRemarkMissed &amp;R, bool ShouldAbort)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b32e4502abf6ca6e3e14df151cff6a8">preserveFakeUses</a> (BasicBlock::iterator Begin, BasicBlock::iterator End)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f525d3e208af9a6e3e547fb58196e2">hasExceptionPointerOrCodeUser</a> (const CatchPadInst *CPI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49830d163fb836dbd4d3af87150b1bd9">mapWasmLandingPadIndex</a> (MachineBasicBlock *MBB, const CatchPadInst *CPI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcde51fb6ab9a2fa51688c8558976c95">isFoldedOrDeadInstruction</a> (const Instruction *I, const FunctionLoweringInfo &amp;FuncInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFoldedOrDeadInstruction - Return true if the specified instruction is side-effect free and is either dead or folded into a generated instruction. <a href="#afcde51fb6ab9a2fa51688c8558976c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80eff7852e73a149806fca03c7df37b0">processIfEntryValueDbgDeclare</a> (FunctionLoweringInfo &amp;FuncInfo, const Value *Arg, DIExpression *Expr, DILocalVariable *Var, DebugLoc DbgLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e6a4fdd6c500cf5a2a6f253cd05e65">processDbgDeclare</a> (FunctionLoweringInfo &amp;FuncInfo, const Value *Address, DIExpression *Expr, DILocalVariable *Var, DebugLoc DbgLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7021d757eccab56a01319353ebe04f">processDbgDeclares</a> (FunctionLoweringInfo &amp;FuncInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect llvm.dbg.declare information. <a href="#a8a7021d757eccab56a01319353ebe04f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3d084d08365c418611e1002a444016">processSingleLocVars</a> (FunctionLoweringInfo &amp;FuncInfo, FunctionVarLocs const *FnVarLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect single location variable information generated with assignment tracking. <a href="#a4e3d084d08365c418611e1002a444016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a> (SDNode *Root, SDNode *Def, SDNode *ImmedUse, bool IgnoreChains)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findNonImmUse - Return true if "Def" is a predecessor of "Root" via a path beyond "ImmedUse". <a href="#a7e5a9b5c5f87a0f7d2227881e84be8a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27774280441b6460e4183ab3054ea406">GetVBR</a> (uint64_t Val, const unsigned char *MatcherTable, unsigned &amp;Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetVBR - decode a vbr encoding whose top bit is set. <a href="#a27774280441b6460e4183ab3054ea406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee68bef4d94f4873f75267990914ac6">getSimpleVT</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSimpleVT - Decode a value in MatcherTable, if it's a VBR encoded value, use GetVBR to decode it. <a href="#a4ee68bef4d94f4873f75267990914ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a> (SmallVectorImpl&lt; SDNode * &gt; &amp;ChainNodesMatched, SelectionDAG *CurDAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandleMergeInputChains - This implements the OPC_EmitMergeInputChains operation for when the pattern matched at least one node with a chains. <a href="#aeb0bc3fb3008d1f61c5a1adb0b901c82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79923c0bb7ad7ead32b876800220d6b3">CheckSame</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, const SmallVectorImpl&lt; std::pair&lt; SDValue, SDNode * &gt; &gt; &amp;RecordedNodes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CheckSame - Implements OP_CheckSame. <a href="#a79923c0bb7ad7ead32b876800220d6b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c617a274bb807748be86583cf743f4">CheckChildSame</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, const SmallVectorImpl&lt; std::pair&lt; SDValue, SDNode * &gt; &gt; &amp;RecordedNodes, unsigned ChildNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CheckChildSame - Implements OP_CheckChildXSame. <a href="#a14c617a274bb807748be86583cf743f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142fa6e3475932e0718153a18ad20f70">CheckPatternPredicate</a> (unsigned Opcode, const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, const SelectionDAGISel &amp;SDISel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CheckPatternPredicate - Implements OP_CheckPatternPredicate. <a href="#a142fa6e3475932e0718153a18ad20f70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac991de895b0ff223cea1a86df733d619">CheckNodePredicate</a> (unsigned Opcode, const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, const SelectionDAGISel &amp;SDISel, SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CheckNodePredicate - Implements OP_CheckNodePredicate. <a href="#ac991de895b0ff223cea1a86df733d619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27ccd25e008885da31b6af396bbb0cf">CheckOpcode</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34708a5452c563dc4e8e3630abf6c24">CheckType</a> (MVT::SimpleValueType VT, SDValue N, const TargetLowering *TLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7849fd2c763a1dd266198c0dd4bf96bc">CheckChildType</a> (MVT::SimpleValueType VT, SDValue N, const TargetLowering *TLI, const DataLayout &amp;DL, unsigned ChildNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab015bad5b65423fd9921361c3c4e57">CheckCondCode</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab685ee3ee52df310a0f900c4d5084a5b">CheckChild2CondCode</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc7dc5a84a4f652c92ca80cd2afedc9">CheckValueType</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, const TargetLowering *TLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b4c2ad26caa75404a88bd3b6c4d8bf">decodeSignRotatedValue</a> (uint64_t V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ddd986b32899ac868a18ee9d1182a1">CheckInteger</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6550b720c223cefb6cf9dafefddca5c">CheckChildInteger</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, unsigned ChildNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617864a293ee07b291bef2224ea10567">CheckAndImm</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, const SelectionDAGISel &amp;SDISel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6699dbb00a8f802ae5f1db4599f93121">CheckOrImm</a> (const unsigned char *MatcherTable, unsigned &amp;MatcherIndex, SDValue N, const SelectionDAGISel &amp;SDISel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> (const unsigned char *Table, unsigned Index, SDValue N, bool &amp;Result, const SelectionDAGISel &amp;SDISel, SmallVectorImpl&lt; std::pair&lt; SDValue, SDNode * &gt; &gt; &amp;RecordedNodes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsPredicateKnownToFail - If we know how and can do so without pushing a scope, evaluate the current node. <a href="#a41976e1f6ca65fb7830e1f348d751000">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4902e6ca7996f26bec31c716ab8ffe59">EnableFastISelAbort</a>("fast-isel-abort", cl::Hidden, cl::desc("Enable abort calls when \"fast\" instruction selection " "fails to lower an instruction: 0 disable the abort, 1 will " "abort but for args, calls and terminators, 2 will also " "abort for argument lowering, and 3 will never fallback " "to SelectionDAG."))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad827524490db9e8663f2f63344fe3715">EnableFastISelFallbackReport</a>("fast-isel-report-on-fallback", cl::Hidden, cl::desc("Emit a diagnostic when \"fast\" instruction selection " "falls back to SelectionDAG."))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774e80a3fa946f0afc06add1fd80d419">UseMBPI</a>("use-mbpi", cl::desc("use Machine Branch Probability Info"), cl::init(true), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c34d5ecbdd39b69f53300a92c289d3">FilterDAGBasicBlockName</a>("filter-view-dags", cl::Hidden, cl::desc("Only display the basic block whose name " "matches this for all view-*-dags options"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3485631f8809018ee7106a365be6b3">ViewDAGCombine1</a>("view-dag-combine1-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the first " "dag combine pass"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac317c2daac0957142210c7dcce900eb0">ViewLegalizeTypesDAGs</a>("view-legalize-types-dags", cl::Hidden, cl::desc("Pop up a window to show dags before legalize types"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1297dee6caba111a1ecf213daf8ae480">ViewDAGCombineLT</a>("view-dag-combine-lt-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the post " "legalize types dag combine pass"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac109e903f71fbfa1181af7eaa27d19f9">ViewLegalizeDAGs</a>("view-legalize-dags", cl::Hidden, cl::desc("Pop up a window to show dags before legalize"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397222b5ec9f04f1cb8158de97f97b7b">ViewDAGCombine2</a>("view-dag-combine2-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the second " "dag combine pass"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ea416cca73b74c97cde839b763e0fe">ViewISelDAGs</a>("view-isel-dags", cl::Hidden, cl::desc("Pop up a window to show isel dags as they are selected"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c3579c2a72a89ebdb7221c60a8a58d">ViewSchedDAGs</a>("view-sched-dags", cl::Hidden, cl::desc("Pop up a window to show sched dags as they are processed"))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5f143cbc19c7808a79baf5fadcc262">ViewSUnitDAGs</a>("view-sunit-dags", cl::Hidden, cl::desc("Pop up a window to show SUnit dags after they are processed"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerscheduler/#a8fdd27818bcec505142aad630a5f05bf">RegisterScheduler::FunctionPassCtor</a>, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd806dfa5a44127c1115d31cd74e701f">ISHeuristic</a>("pre-RA-sched", cl::init(&createDefaultScheduler), cl::Hidden, cl::desc("Instruction schedulers available (before register" " allocation):"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ISHeuristic command line option for instruction schedulers. <a href="#acd806dfa5a44127c1115d31cd74e701f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9c076e229512f249fd9b86dddfb6bc">defaultListDAGScheduler</a>("default", "Best scheduler for the target", createDefaultScheduler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"isel"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00aa8f6216c5a65ac1712d9f0ffa5f03">ISEL_DUMP_DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-dump"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2a362c659d23c23b32a7280c436583">ISEL_DUMP</a>(X)&nbsp;&nbsp;&nbsp;...</td>
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

### CheckAndImm() {#a617864a293ee07b291bef2224ea10567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckAndImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> &amp; SDISel)</td>
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



<p>Definition at line 2991 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a9dcbd38183e29746d52bb60bdcd611ba">llvm::SelectionDAGISel::CheckAndMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a27774280441b6460e4183ab3054ea406">GetVBR</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckChild2CondCode() {#ab685ee3ee52df310a0f900c4d5084a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckChild2CondCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 2940 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckChildInteger() {#ae6550b720c223cefb6cf9dafefddca5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckChildInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned ChildNo)</td>
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



<p>Definition at line 2983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckChildSame() {#a14c617a274bb807748be86583cf743f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckChildSame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &gt; &amp; RecordedNodes, unsigned ChildNo)</td>
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

<p>CheckChildSame - Implements OP_CheckChildXSame.</p>

<p>Definition at line 2869 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckChildType() {#a7849fd2c763a1dd266198c0dd4bf96bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckChildType (<a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, unsigned ChildNo)</td>
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



<p>Definition at line 2925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckCondCode() {#aaab015bad5b65423fd9921361c3c4e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckCondCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 2933 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckInteger() {#a55ddd986b32899ac868a18ee9d1182a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 2970 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a27b4c2ad26caa75404a88bd3b6c4d8bf">decodeSignRotatedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a27774280441b6460e4183ab3054ea406">GetVBR</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckNodePredicate() {#ac991de895b0ff223cea1a86df733d619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckNodePredicate (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> &amp; SDISel, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>CheckNodePredicate - Implements OP_CheckNodePredicate.</p>

<p>Definition at line 2896 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a246bbdcb892a7c3ff35f94d404ead49e">llvm::SelectionDAGISel::CheckNodePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a9bcd7019459f96271977dc7b7a0e42c7">llvm::SelectionDAGISel::OPC_CheckPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a3f87dd8572fe9a5ce5bf3622e3adc25d">llvm::SelectionDAGISel::OPC_CheckPredicate0</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a>.</p>

</div>
</div>

### CheckOpcode() {#ae27ccd25e008885da31b6af396bbb0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 2906 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckOrImm() {#a6699dbb00a8f802ae5f1db4599f93121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckOrImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> &amp; SDISel)</td>
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



<p>Definition at line 3004 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a088862cded43bb2202369f9346535d3a">llvm::SelectionDAGISel::CheckOrMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a27774280441b6460e4183ab3054ea406">GetVBR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckPatternPredicate() {#a142fa6e3475932e0718153a18ad20f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckPatternPredicate (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> &amp; SDISel)</td>
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

<p>CheckPatternPredicate - Implements OP_CheckPatternPredicate.</p>

<p>Definition at line 2881 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a4092776a5fb47cdeb74ad864550fd5e0">llvm::SelectionDAGISel::CheckPatternPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a46a1f303e35f6feb3dabf3e588ef109b">llvm::SelectionDAGISel::OPC_CheckPatternPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ad23e1edee534c7aa42fe9b55324c678b">llvm::SelectionDAGISel::OPC_CheckPatternPredicate0</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a23f4b904d2aecb5cb55c5e16f35f2b1a">llvm::SelectionDAGISel::OPC_CheckPatternPredicateTwoByte</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a>.</p>

</div>
</div>

### CheckSame() {#a79923c0bb7ad7ead32b876800220d6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckSame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &gt; &amp; RecordedNodes)</td>
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

<p>CheckSame - Implements OP_CheckSame.</p>

<p>Definition at line 2860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckType() {#aa34708a5452c563dc4e8e3630abf6c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckType (<a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 2913 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1b85be3cd0fffad1d76673016015e02">llvm::isConsecutiveAccess</a>, <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a594ac8dc567913194b0d139e37c02dc5">ProfileExistsOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#aeb4fb92ed0bd689ff1e4534b84bba076">ProfileIsAOpInit</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### CheckValueType() {#a0bc7dc5a84a4f652c92ca80cd2afedc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE bool CheckValueType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 2948 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="#a4ee68bef4d94f4873f75267990914ac6">getSimpleVT</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### decodeSignRotatedValue() {#a27b4c2ad26caa75404a88bd3b6c4d8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t decodeSignRotatedValue (uint64_t V)</td>
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



<p>Definition at line 2960 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Referenced by <a href="#a55ddd986b32899ac868a18ee9d1182a1">CheckInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### dontUseFastISelFor() {#a7cc70f4d5f07cada554efd4e2c8386c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool dontUseFastISelFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a49e6c89ce42a55a93ddf38d21bbd198e">llvm::Function::args</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/optlevelchanger/#aba99f22828960fc870a5facbc25c6ef2">llvm::OptLevelChanger::OptLevelChanger</a>.</p>

</div>
</div>

### findNonImmUse() {#a7e5a9b5c5f87a0f7d2227881e84be8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findNonImmUse (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * ImmedUse, bool IgnoreChains)</td>
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

<p>findNonImmUse - Return true if "Def" is a predecessor of "Root" via a path beyond "ImmedUse".</p>


<p>We may ignore chains as they are checked separately.</p>


<p>Definition at line 2336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2998329e16665f7101fac0ae9faee5c7">llvm::SDNode::isOnlyUserOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2bb043b87aa8cdef6d1e9e14329aec6a">llvm::SDNode::op_values</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a>.</p>

</div>
</div>

### getSimpleVT() {#a4ee68bef4d94f4873f75267990914ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE MVT::SimpleValueType getSimpleVT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; MatcherIndex)</td>
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

<p>getSimpleVT - Decode a value in MatcherTable, if it's a VBR encoded value, use GetVBR to decode it.</p>

<p>Definition at line 2663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Reference <a href="#a27774280441b6460e4183ab3054ea406">GetVBR</a>.</p>


<p>Referenced by <a href="#a0bc7dc5a84a4f652c92ca80cd2afedc9">CheckValueType</a>, <a href="#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/resultstack/#a314645887ef1a5da942974d16ff180a4">anonymous{HexagonISelDAGToDAGHVX.cpp}::ResultStack::ResultStack</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### GetVBR() {#a27774280441b6460e4183ab3054ea406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE uint64_t GetVBR (uint64_t Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * MatcherTable, unsigned &amp; Idx)</td>
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

<p>GetVBR - decode a vbr encoding whose top bit is set.</p>

<p>Definition at line 2645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a617864a293ee07b291bef2224ea10567">CheckAndImm</a>, <a href="#a55ddd986b32899ac868a18ee9d1182a1">CheckInteger</a>, <a href="#a6699dbb00a8f802ae5f1db4599f93121">CheckOrImm</a>, <a href="#a4ee68bef4d94f4873f75267990914ac6">getSimpleVT</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### HandleMergeInputChains() {#aeb0bc3fb3008d1f61c5a1adb0b901c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue HandleMergeInputChains (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; ChainNodesMatched, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG)</td>
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

<p>HandleMergeInputChains - This implements the OPC_EmitMergeInputChains operation for when the pattern matched at least one node with a chains.</p>


<p>The input vector contains a list of all of the chained nodes that we match. We must determine if this is a valid thing to cover (i.e. matching it won't induce cycles in the DAG) and if so, creating a TokenFactor node. that will be used as the input node chain for the generated nodes.</p>


<p>Definition at line 2739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a926013f6dca240eca95aca66c8d3e74b">llvm::ISD::EntryToken</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### hasExceptionPointerOrCodeUser() {#ab3f525d3e208af9a6e3e547fb58196e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasExceptionPointerOrCodeUser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a> * CPI)</td>
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



<p>Definition at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### isFoldedOrDeadInstruction() {#afcde51fb6ab9a2fa51688c8558976c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFoldedOrDeadInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo)</td>
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

<p>isFoldedOrDeadInstruction - Return true if the specified instruction is side-effect free and is either dead or folded into a generated instruction.</p>


<p>Return false if it needs to be emitted.</p>


<p>Definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### IsPredicateKnownToFail() {#a41976e1f6ca65fb7830e1f348d751000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned IsPredicateKnownToFail (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Table, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, bool &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> &amp; SDISel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &gt; &amp; RecordedNodes)</td>
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

<p>IsPredicateKnownToFail - If we know how and can do so without pushing a scope, evaluate the current node.</p>


<p>If the current predicate is known to fail, set Result=true and return anything. If the current predicate is known to pass, set Result=false and return the MatcherIndex to continue with. If the current predicate is unknown, set Result=false and return the MatcherIndex to continue with.</p>


<p>Definition at line 3022 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="#a617864a293ee07b291bef2224ea10567">CheckAndImm</a>, <a href="#ab685ee3ee52df310a0f900c4d5084a5b">CheckChild2CondCode</a>, <a href="#ae6550b720c223cefb6cf9dafefddca5c">CheckChildInteger</a>, <a href="#a14c617a274bb807748be86583cf743f4">CheckChildSame</a>, <a href="#a7849fd2c763a1dd266198c0dd4bf96bc">CheckChildType</a>, <a href="#aaab015bad5b65423fd9921361c3c4e57">CheckCondCode</a>, <a href="#a55ddd986b32899ac868a18ee9d1182a1">CheckInteger</a>, <a href="#ac991de895b0ff223cea1a86df733d619">CheckNodePredicate</a>, <a href="#ae27ccd25e008885da31b6af396bbb0cf">CheckOpcode</a>, <a href="#a6699dbb00a8f802ae5f1db4599f93121">CheckOrImm</a>, <a href="#a142fa6e3475932e0718153a18ad20f70">CheckPatternPredicate</a>, <a href="#a79923c0bb7ad7ead32b876800220d6b3">CheckSame</a>, <a href="#aa34708a5452c563dc4e8e3630abf6c24">CheckType</a>, <a href="#a0bc7dc5a84a4f652c92ca80cd2afedc9">CheckValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="#a4ee68bef4d94f4873f75267990914ac6">getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a762f7415efdb5556233c801b1ec86509">llvm::SelectionDAGISel::OPC_CheckAndImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2abf1182c1e01bd858a9f62b3876cd7783">llvm::SelectionDAGISel::OPC_CheckChild0Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ac4ef97ce82a9ec47ffddf66e304a3790">llvm::SelectionDAGISel::OPC_CheckChild0Same</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a8c35dbaea22168300c0417f650be72a5">llvm::SelectionDAGISel::OPC_CheckChild0Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ae1cacf1d0774ce4a534d9d02631ccbd5">llvm::SelectionDAGISel::OPC_CheckChild0TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a6d0a13640edd0bf1ce7a5f11eddaff66">llvm::SelectionDAGISel::OPC_CheckChild0TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2aea2c4c9b4066fd1100bb2765caf73539">llvm::SelectionDAGISel::OPC_CheckChild1Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a8fa80a632f8f5c2348cdff0eb41e66fc">llvm::SelectionDAGISel::OPC_CheckChild1Same</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a5bd4c5f999490a0b61230d3ed58122b7">llvm::SelectionDAGISel::OPC_CheckChild1Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ad2fb704e11f169b195db843306ba3eb4">llvm::SelectionDAGISel::OPC_CheckChild1TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a29a97ec801bcc2db31cbdd0ee4371fce">llvm::SelectionDAGISel::OPC_CheckChild1TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a16f2593c7101b71a3e2c8dfd16de4853">llvm::SelectionDAGISel::OPC_CheckChild2CondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2abf9f3831ce11503ccc21b1f7998e2be1">llvm::SelectionDAGISel::OPC_CheckChild2Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a0a813f9abf776d7caaa06e5d72c94ecc">llvm::SelectionDAGISel::OPC_CheckChild2Same</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a7e7290f899b310f10094103102451001">llvm::SelectionDAGISel::OPC_CheckChild2Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a6965042b1792d90cf710a9128af2112e">llvm::SelectionDAGISel::OPC_CheckChild2TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ab3db72b7dff5d19c9df1e42a0f237f40">llvm::SelectionDAGISel::OPC_CheckChild2TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ae5b3f94e69a52bc07ced3b921e6e5644">llvm::SelectionDAGISel::OPC_CheckChild3Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2aaeb67823b90670973d26bbaa91c97ed2">llvm::SelectionDAGISel::OPC_CheckChild3Same</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a04f261bfda135591bf8341f6a20a665e">llvm::SelectionDAGISel::OPC_CheckChild3Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a5ca19f565faf4269be8168c18d049aa7">llvm::SelectionDAGISel::OPC_CheckChild3TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a6d114b2125edf22c35d57895605058a4">llvm::SelectionDAGISel::OPC_CheckChild3TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2af4320127500bc7987d4b2947d05254b0">llvm::SelectionDAGISel::OPC_CheckChild4Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a8f58a385e467906cfa60bb96ec84508f">llvm::SelectionDAGISel::OPC_CheckChild4Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ab2d8f0e6208bfec58650bbfa409fe586">llvm::SelectionDAGISel::OPC_CheckChild4TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2abda25ce60a444af74f49be173e746ef5">llvm::SelectionDAGISel::OPC_CheckChild4TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a378a8e72b2fc7c4a0cf9ac5ae724a0ea">llvm::SelectionDAGISel::OPC_CheckChild5Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a531ed89e0f46c5b1d934f233c1157223">llvm::SelectionDAGISel::OPC_CheckChild5TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2aa77b7d57f9a631a3377cbd01b1490543">llvm::SelectionDAGISel::OPC_CheckChild5TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a136ee3a03a1bab562927a4e0ac11fbbc">llvm::SelectionDAGISel::OPC_CheckChild6Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a6bb88e44867eba34e66cf41cbfbed023">llvm::SelectionDAGISel::OPC_CheckChild6TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a346e1bfd7fa525f013de9748cfefe4d0">llvm::SelectionDAGISel::OPC_CheckChild6TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a1fd783d02f34d56b77c1907ed6e71966">llvm::SelectionDAGISel::OPC_CheckChild7Type</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a959e093000e3e5bf62504959cfdf3be6">llvm::SelectionDAGISel::OPC_CheckChild7TypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a0bb1ee968805a26a05f098ac5e17f1b9">llvm::SelectionDAGISel::OPC_CheckChild7TypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a8f80287bd79b4dda1de0fb810dbb0ecd">llvm::SelectionDAGISel::OPC_CheckCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a797344a4f66b9d2c2c4487a3bcffa98f">llvm::SelectionDAGISel::OPC_CheckInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ae10cd161a6495fede5121b564d10ce2a">llvm::SelectionDAGISel::OPC_CheckOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a07f7c58b8c512a9e943c07c7210b6f72">llvm::SelectionDAGISel::OPC_CheckOrImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a46a1f303e35f6feb3dabf3e588ef109b">llvm::SelectionDAGISel::OPC_CheckPatternPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ad23e1edee534c7aa42fe9b55324c678b">llvm::SelectionDAGISel::OPC_CheckPatternPredicate0</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a26dfb942cf003f794bb169a3f8d63abe">llvm::SelectionDAGISel::OPC_CheckPatternPredicate1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a33c5469d6659ea2d685109fa03788d30">llvm::SelectionDAGISel::OPC_CheckPatternPredicate2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2af19ecb348b00ab317240b3b0bef887db">llvm::SelectionDAGISel::OPC_CheckPatternPredicate3</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a3e185b281dfb23b7bf5ca5095d5f8670">llvm::SelectionDAGISel::OPC_CheckPatternPredicate4</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a098925b621956a3c7fad469a517dab75">llvm::SelectionDAGISel::OPC_CheckPatternPredicate5</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a4af4ac72eb8b6f578cd53af9e508fb70">llvm::SelectionDAGISel::OPC_CheckPatternPredicate6</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a4c6b3ead9f604a61c17a8c92337f6658">llvm::SelectionDAGISel::OPC_CheckPatternPredicate7</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a23f4b904d2aecb5cb55c5e16f35f2b1a">llvm::SelectionDAGISel::OPC_CheckPatternPredicateTwoByte</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a9bcd7019459f96271977dc7b7a0e42c7">llvm::SelectionDAGISel::OPC_CheckPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a3f87dd8572fe9a5ce5bf3622e3adc25d">llvm::SelectionDAGISel::OPC_CheckPredicate0</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2abc13b4634655ecff98492533ec9fbfce">llvm::SelectionDAGISel::OPC_CheckPredicate1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2aaebe8fd36e71a074866f0aca4597c1b2">llvm::SelectionDAGISel::OPC_CheckPredicate2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a7b56478591ade4c9b4fcbf6f076b1874">llvm::SelectionDAGISel::OPC_CheckPredicate3</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a542dccbb8c1030bbe5c62a95bde94353">llvm::SelectionDAGISel::OPC_CheckPredicate4</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ac36e4438b00cae13a36df521d7a6517c">llvm::SelectionDAGISel::OPC_CheckPredicate5</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a6631daa7ba6f00c3d0f13ed41f2deec9">llvm::SelectionDAGISel::OPC_CheckPredicate6</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a20e2cfcc34e8c9faf9c7eda7d164ff83">llvm::SelectionDAGISel::OPC_CheckPredicate7</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ac17440039d284c65ee3b7d5f9989f50c">llvm::SelectionDAGISel::OPC_CheckSame</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ae3fd6bdaf8484f407123c016fac17bbb">llvm::SelectionDAGISel::OPC_CheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a7fe2b3cfa957ed14d4160849aaff8e81">llvm::SelectionDAGISel::OPC_CheckTypeI32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2ad2338671ace5fd50cc68c5773bfb1c09">llvm::SelectionDAGISel::OPC_CheckTypeI64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a0cb67066bfa7d2bd17608d5bbd759879">llvm::SelectionDAGISel::OPC_CheckTypeRes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a32bc192d568793fb156fd6d6b75cb3c2a25c8c32aaa6b79885859cebc7ff11ae6">llvm::SelectionDAGISel::OPC_CheckValueType</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a1ed864be04c93653277b0f5112a4f305">llvm::SelectionDAGISel::TLI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### mapWasmLandingPadIndex() {#a49830d163fb836dbd4d3af87150b1bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void mapWasmLandingPadIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a> * CPI)</td>
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



<p>Definition at line 1379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a73ad527c13c3bb6367aa1f507d28ac3e">llvm::FuncletPadInst::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#af8fcc98ff5354df31b46d4cac69514ab">llvm::FuncletPadInst::getArgOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a343bd9984aa0af780917fa6bb561e80d">llvm::MachineFunction::setWasmLandingPadIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### preserveFakeUses() {#a8b32e4502abf6ca6e3e14df151cff6a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void preserveFakeUses (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> End)</td>
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



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### processDbgDeclare() {#ad8e6a4fdd6c500cf5a2a6f253cd05e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool processDbgDeclare (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc)</td>
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



<p>Definition at line 1548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a4ce0a0358c0de36a6ea4413d7abcbca8">llvm::DIExpression::ApplyOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab804b15bb92ff685d7c1464b2816d608">llvm::DIExpression::prepend</a>, <a href="#a80eff7852e73a149806fca03c7df37b0">processIfEntryValueDbgDeclare</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac523d75b0141b2e47d95ebce7adc0ebc">llvm::MachineFunction::setVariableDbgInfo</a>.</p>


<p>Referenced by <a href="#a8a7021d757eccab56a01319353ebe04f">processDbgDeclares</a> and <a href="#a4e3d084d08365c418611e1002a444016">processSingleLocVars</a>.</p>

</div>
</div>

### processDbgDeclares() {#a8a7021d757eccab56a01319353ebe04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processDbgDeclares (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo)</td>
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

<p>Collect llvm.dbg.declare information.</p>


<p>This is done after argument lowering in case the declarations refer to arguments.</p>


<p>Definition at line 1598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> and <a href="#ad8e6a4fdd6c500cf5a2a6f253cd05e65">processDbgDeclare</a>.</p>

</div>
</div>

### processIfEntryValueDbgDeclare() {#a80eff7852e73a149806fca03c7df37b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool processIfEntryValueDbgDeclare (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc)</td>
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



<p>Definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a15f4de7989cc83855e8f65792ae94bc4">llvm::DIExpression::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ad8e6a4fdd6c500cf5a2a6f253cd05e65">processDbgDeclare</a>.</p>

</div>
</div>

### processSingleLocVars() {#a4e3d084d08365c418611e1002a444016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processSingleLocVars (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs">FunctionVarLocs</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * FnVarLocs)</td>
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

<p>Collect single location variable information generated with assignment tracking.</p>


<p>This is done after argument lowering in case the declarations refer to arguments.</p>


<p>Definition at line 1617 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs/#aa99e4e7d8afaee8fb8a1b3ca0158492a">llvm::FunctionVarLocs::getDILocalVariable</a>, <a href="#ad8e6a4fdd6c500cf5a2a6f253cd05e65">processDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs/#a82ac348d37f9d4342bf7f7c9433b213c">llvm::FunctionVarLocs::single_locs_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs/#aebd1b22de49da2b8b99ad3238bbdad46">llvm::FunctionVarLocs::single_locs_end</a>.</p>

</div>
</div>

### reportFastISelFailure() {#a292edc681e4846f695d627a99cb1560d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reportFastISelFailure (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed">OptimizationRemarkMissed</a> &amp; R, bool ShouldAbort)</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### STATISTIC() {#aa86b9a266a6b20065efd529aad768608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFastIselFailures, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> fast <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> failed on")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a9805b0bbd8f8390ae9649b189bc0d148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFastIselSuccess, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> fast <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> selected")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ad286fd7c3b789d38d762600a70adecd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFastIselBlocks, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> selected entirely by fast isel")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a6ee452fede10d0fbe5b777015d17a5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDAGBlocks, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> selected using DAG")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af7d237256bcb5b26f8dc10aa8212a35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDAGIselRetries, "Number of times dag <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> has to try another path")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a4b53c2ab01eb828cf84fdd36487c82ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumEntryBlocks, "Number of entry <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> encountered")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa6d2cbeca32ee1e338c4fe49b4025d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFastIselFailLowerArguments, "Number of entry <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> where fast <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> failed to lower arguments")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### defaultListDAGScheduler {#a3c9c076e229512f249fd9b86dddfb6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterScheduler defaultListDAGScheduler("default", "Best scheduler for the target", createDefaultScheduler)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### EnableFastISelAbort {#a4902e6ca7996f26bec31c716ab8ffe59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; EnableFastISelAbort("fast-isel-abort", cl::Hidden, cl::desc("Enable abort calls when \"fast\" instruction selection " "fails to lower an instruction: 0 disable the abort, 1 will " "abort but for args, calls and terminators, 2 will also " "abort for argument lowering, and 3 will never fallback " "to SelectionDAG."))</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagiselpass/#afbe031a5b54a7910faf25270aeeac0dc">llvm::SelectionDAGISelPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a32f14bc31f9990134e480ee3e0e0bd11">llvm::SelectionDAGISelLegacy::runOnMachineFunction</a>.</p>

</div>
</div>

### EnableFastISelFallbackReport {#ad827524490db9e8663f2f63344fe3715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableFastISelFallbackReport("fast-isel-report-on-fallback", cl::Hidden, cl::desc("Emit a diagnostic when \"fast\" instruction selection " "falls back to SelectionDAG."))</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### FilterDAGBasicBlockName {#ae9c34d5ecbdd39b69f53300a92c289d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; FilterDAGBasicBlockName("filter-view-dags", cl::Hidden, cl::desc("Only display the basic block whose name " "matches this for all view-*-dags options"))</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ISHeuristic {#acd806dfa5a44127c1115d31cd74e701f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RegisterScheduler::FunctionPassCtor, false, RegisterPassParser&lt; RegisterScheduler &gt; &gt; ISHeuristic("pre-RA-sched", cl::init(&amp;createDefaultScheduler), cl::Hidden, cl::desc("Instruction schedulers available (before register" " allocation):"))</td>
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

<p>ISHeuristic command line option for instruction schedulers.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### UseMBPI {#a774e80a3fa946f0afc06add1fd80d419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseMBPI("use-mbpi", cl::desc("use Machine Branch Probability Info"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a77e4cdd5d33f676fb695a8204f7b70ff">llvm::SelectionDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>.</p>

</div>
</div>

### ViewDAGCombine1 {#a7f3485631f8809018ee7106a365be6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewDAGCombine1("view-dag-combine1-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the first " "dag combine pass"))</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewDAGCombine2 {#a397222b5ec9f04f1cb8158de97f97b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewDAGCombine2("view-dag-combine2-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the second " "dag combine pass"))</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewDAGCombineLT {#a1297dee6caba111a1ecf213daf8ae480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewDAGCombineLT("view-dag-combine-lt-dags", cl::Hidden, cl::desc("Pop up a window to show dags before the post " "legalize types dag combine pass"))</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewISelDAGs {#a20ea416cca73b74c97cde839b763e0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewISelDAGs("view-isel-dags", cl::Hidden, cl::desc("Pop up a window to show isel dags as they are selected"))</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewLegalizeDAGs {#ac109e903f71fbfa1181af7eaa27d19f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewLegalizeDAGs("view-legalize-dags", cl::Hidden, cl::desc("Pop up a window to show dags before legalize"))</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewLegalizeTypesDAGs {#ac317c2daac0957142210c7dcce900eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewLegalizeTypesDAGs("view-legalize-types-dags", cl::Hidden, cl::desc("Pop up a window to show dags before legalize types"))</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewSchedDAGs {#a86c3579c2a72a89ebdb7221c60a8a58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewSchedDAGs("view-sched-dags", cl::Hidden, cl::desc("Pop up a window to show sched dags as they are processed"))</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ViewSUnitDAGs {#a0c5f143cbc19c7808a79baf5fadcc262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewSUnitDAGs("view-sunit-dags", cl::Hidden, cl::desc("Pop up a window to show SUnit dags after they are processed"))</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

### ISEL\_DUMP {#a4a2a362c659d23c23b32a7280c436583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISEL_DUMP(X)&nbsp;&nbsp;&nbsp;...</td>
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
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (<a href="/web-llvm/docs/api/namespaces/llvm/#a58509b852790f6ca23065ec638bc30ff">llvm::DebugFlag</a> &amp;&amp;                                                     \
        (isCurrentDebugType(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>) ||                                     \
         (isCurrentDebugType(<a href="#a00aa8f6216c5a65ac1712d9f0ffa5f03">ISEL_DUMP_DEBUG_TYPE</a>) &amp;&amp; MatchFilterFuncName))) { \
      <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>;                                                                       \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### ISEL\_DUMP\_DEBUG\_TYPE {#a00aa8f6216c5a65ac1712d9f0ffa5f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISEL_DUMP_DEBUG_TYPE&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-dump"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp">SelectionDAGISel.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
